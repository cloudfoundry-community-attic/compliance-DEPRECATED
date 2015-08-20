# Audit and Accountability

<a name="au-02"></a>
### [AU-02: Audit Events](https://web.nvd.nist.gov/view/800-53/Rev4/control?controlName=AU-2)

**CONTROL**: The organization (i) determines that the information system is capable of auditing the following events: [Assignment: organization-defined auditable events];
(ii) Coordinates the security audit function with other organizational entities requiring audit-related information to enhance mutual support and to help guide the selection of auditable events;
(iii) Provides a rationale for why the auditable events are deemed to be adequate to support after-the-fact investigations of security incidents; and
(iv) Determines that the following events are to be audited within the information system: [Assignment: organization-defined audited events (the subset of the auditable events defined in AU-2 a.) along with the frequency of (or situation requiring) auditing for each identified event].

**MAPPING**: Cloud Foundry and BOSH maintain an audit log of user events. It is the administrator's responsibility to ensure that log is stored and reviewed.

**DOCS**:
* [https://docs.cloudfoundry.org/concepts/security.html#logging](https://docs.cloudfoundry.org/concepts/security.html#logging)
* [https://github.com/cloudfoundry/dea_ng/blob/master/spec/unit/loggregator_spec.rb](https://github.com/cloudfoundry/dea_ng/blob/master/spec/unit/loggregator_spec.rb)
* [https://github.com/cloudfoundry/bosh/blob/master/bosh-director/spec/unit/event_log_spec.rb](https://github.com/cloudfoundry/bosh/blob/master/bosh-director/spec/unit/event_log_spec.rb)
