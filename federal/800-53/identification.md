# Identification and Authentication


<a name="ia-02"></a>
### [IA-02: User Identification and Authentication](https://web.nvd.nist.gov/view/800-53/Rev4/control?controlName=IA-2)

**CONTROL**: The information system uniquely identifies and authenticates organizational users (or processes acting on behalf of organizational users).

**MAPPING**: Cloud Foundry uses [UAA](https://docs.cloudfoundry.org/concepts/architecture/uaa.html) for identity management. Users are uniquely identified and their actions are tied with their UUID.

**DOCS**:
* [https://docs.cloudfoundry.org/concepts/architecture/uaa.html](https://docs.cloudfoundry.org/concepts/architecture/uaa.html)

#### Enhancements:
<a name="ia-02i"></a>
##### [Network Access To Privileged Accounts](https://web.nvd.nist.gov/view/800-53/Rev4/control?controlName=IA-2#enhancement-1)

**ENHANCEMENT**: The information system implements multifactor authentication for network access to privileged accounts.

**MAPPING**: Cloud Foundry does not provide multi factor authentication out of the box but it integrates with services that can provide them using [SAML](https://en.wikipedia.org/wiki/Security_Assertion_Markup_Language).

**DOCS**:
* [https://github.com/cloudfoundry/login-server](https://github.com/cloudfoundry/login-server)

<a name="ia-02ii"></a>
##### [Network Access To Non-Privileged Accounts](https://web.nvd.nist.gov/view/800-53/Rev4/control?controlName=IA-2#enhancement-2)

**ENHANCEMENT**: The information system implements multifactor authentication for network access to non-privileged accounts.

**MAPPING**: Cloud Foundry does not provide multi factor authentication out of the box but it integrates with services that can provide them using [SAML](https://en.wikipedia.org/wiki/Security_Assertion_Markup_Language).

**DOCS**:
* [https://github.com/cloudfoundry/login-server](https://github.com/cloudfoundry/login-server)
