# Configuration Management


<a name="cm-02"></a>
### [CM-02: Baseline Configuration](https://web.nvd.nist.gov/view/800-53/Rev4/control?controlName=CM-2)

**CONTROL**: The organization develops, documents, and maintains under configuration control, a current baseline configuration of the information system.

**MAPPING**: Cloud Foundry uses BOSH to configure and provision servers. BOSH stemcell creation is documented using version control. Administrators are responsible for documenting changes of BOSH manifests.

**DOCS**:
* [https://bosh.io/docs/stemcell.html](https://bosh.io/docs/stemcell.html)
* [https://github.com/cloudfoundry/bosh/blob/master/CHANGELOG.md](https://github.com/cloudfoundry/bosh/blob/master/CHANGELOG.md)
* [https://bosh.io/docs/deployment-manifest.html](https://bosh.io/docs/deployment-manifest.html)
* [https://github.com/cloudfoundry/bosh/blob/master/bosh-stemcell/OS_IMAGES.md](https://github.com/cloudfoundry/bosh/blob/master/bosh-stemcell/OS_IMAGES.md)


<a name="cm-03"></a>
### [CM-03: Configuration Change Control](https://web.nvd.nist.gov/view/800-53/Rev4/control?controlName=CM-3)

**CONTROL**: The organization:
(i) Determines the types of changes to the information system that are configuration-controlled;
(ii) Reviews proposed configuration-controlled changes to the information system and approves or disapproves such changes with explicit consideration for security impact analyses;
(iii) Documents configuration change decisions associated with the information system;
(iv) Implements approved configuration-controlled changes to the information system;
(v) Retains records of configuration-controlled changes to the information system for [Assignment: organization-defined time period];
(vi) Audits and reviews activities associated with configuration-controlled changes to the information system; and
(vii) Coordinates and provides oversight for configuration change control activities through [Assignment: organization-defined configuration change control element (e.g., committee, board)] that convenes [Selection (one or more): [Assignment: organization-defined frequency]; [Assignment: organization-defined configuration change conditions]].

**MAPPING**: BOSH and Cloud Foundry maintain audit logs of all changes made to the platform. The organization needs to establish a review process for BOSH manifest and Cloud Foundry Runtime configuration changes.

**DOCS**:
* [https://docs.cloudfoundry.org/concepts/security.html#logging](https://docs.cloudfoundry.org/concepts/security.html#logging)


<a name="cm-06"></a>
### [CM-06: Configuration Settings](https://web.nvd.nist.gov/view/800-53/Rev4/control?controlName=CM-6)

**CONTROL**: The organization:
(i) Establishes and documents configuration settings for information technology products employed within the information system using [Assignment: organization-defined security configuration checklists] that reflect the most restrictive mode consistent with operational requirements;
(ii) Implements the configuration settings;
(iii) Identifies, documents, and approves any deviations from established configuration settings for [Assignment: organization-defined information system components] based on [Assignment: organization-defined operational requirements]; and
(iv) Monitors and controls changes to the configuration settings in accordance with organizational policies and procedures.

**MAPPING**: BOSH and Cloud Foundry default configurations are restrictive in their nature. Automated notification of changes can be set up in BOST to monitor changes.

**DOCS**:
* [https://bosh.io/docs/monitoring.html](https://bosh.io/docs/monitoring.html)
