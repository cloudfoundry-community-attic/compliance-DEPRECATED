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
