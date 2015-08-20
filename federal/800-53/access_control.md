## Access Control

<a name="ac-01"></a>
### [AC-01: Access Control Policy and Procedures][https://web.nvd.nist.gov/view/800-53/Rev4/control?controlName=AC-1]

**CONTROL**: The organization develops, disseminates, and periodically reviews/updates: (i) a formal, documented, access control policy that addresses purpose, scope, roles, responsibilities, and compliance; and (ii) formal, documented procedures to facilitate the implementation of the access control policy and associated access controls.

**MAPPING**: Cloud Foundry integrates with an organization's Identity Provider (IDP) which dictates further account management policies.

**DOCS**: See [https://github.com/cloudfoundry/uaa/blob/master/docs/UAA-LDAP.md](https://github.com/cloudfoundry/uaa/blob/master/docs/UAA-LDAP.md)


<a name="ac-02"></a>
### [AC-02: Account Management](https://web.nvd.nist.gov/view/800-53/Rev4/control?controlName=AC-2)

**CONTROL**: The organization manages information system accounts, including establishing, activating, modifying, reviewing, disabling, and removing accounts. The organization reviews information system accounts [Assignment: organization-defined frequency].

**MAPPING**: Roles and Groups within Cloud Foundry (both for BOSH and for Runtime) can be mapped to the organization's integrated IDP.

**DOCS**:
* [http://docs.pivotal.io/pivotalcf/opsguide/ldap-uaa.html](http://docs.pivotal.io/pivotalcf/opsguide/ldap-uaa.html)
* [http://docs.pivotal.io/pivotalcf/adminguide/uaa-user-management.html](http://docs.pivotal.io/pivotalcf/adminguide/uaa-user-management.html)
* [http://docs.pivotal.io/pivotalcf/concepts/architecture/uaa.html](http://docs.pivotal.io/pivotalcf/concepts/architecture/uaa.html)
* [https://github.com/cloudfoundry/uaa/blob/master/docs/Sysadmin-Guide.rst](https://github.com/cloudfoundry/uaa/blob/master/docs/Sysadmin-Guide.rst)
