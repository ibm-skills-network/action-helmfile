# Breaking Changes

# What’s new in Chart Version 2.2.33

With ibm-object-storage-plugin chart version 2.2.33, the following new features are available:

* ROKS v4.17 cluster support
* IKS 1.31 cluster support

# Fixes
* None 


# Prerequisites
Install [Helm client v3](https://cloud.ibm.com/docs/containers?topic=containers-helm#install_v3) on your local machine.

**NOTE:** For IBM Cloud Kubernetes Service(IKS), it is strongly recommended to [migrate from helm v2 to v3](https://cloud.ibm.com/docs/containers?topic=containers-helm#migrate_v3). For IBM Cloud Private(ICP), no need to update the helm client.

# Documentation
For install/upgrade, follow instructions [here](https://cloud.ibm.com/docs/containers?topic=containers-object_storage#object_storage).

# Version History

| Chart | Date | Kubernetes Required | Image(s) Supported | Breaking Changes | Details |
| ----- | ---- | ------------ | ------------------ | ---------------- | ------- |
| 2.2.33| Nov 21, 2024|>= 1.26.0| 1.8.88| None | Update golang to 1.22.9, Fix CVEs - CVE-2024-3596, CVE-2024-5535, ROKS v4.17 cluster support, IKS 1.31 cluster support |
| 2.2.32| Sep 27, 2024|>= 1.26.0| 1.8.87| None | Fixed mount issue with coreos9 roks 4.16 cluster |
| 2.2.31| Sep 24, 2024|>= 1.26.0| 1.8.86| None | s3fs-fuse version updated to v1.94, Update golang to 1.22.7, Fix CVEs - CVE-2024-34158, CVE-2024-34155 & CVE-2024-34156 |
| 2.2.30| Aug 29, 2024|>= 1.26.0| 1.8.85| None | Update golang to 1.21.13, Fix CVEs - CVE-2024-6104, CVE-2024-24791, CVE-2023-45288, CVE-2024-2398, CVE-2024-37370 & CVE-2024-37371 |
| 2.2.29| July 30, 2024|>= 1.25.0| 1.8.84| None | Enable ubuntu24 cluster support |
| 2.2.28| July 17, 2024|>= 1.25.0| 1.8.83| None | Update golang base image to fix vulnerabilities - CVE-2023-2953, CVE-2024-28182 |
| 2.2.27| June 28, 2024|>= 1.23.0| 1.8.82| None | Update golang base image to fix vulnerabilities - CVE-2024-24789, CVE-2024-24790 |
| 2.2.26| June 05, 2024|>= 1.23.0| 1.8.81| None | HPCS support for cos s3fs plugin, Update golang base image to fix vulnerabilities - CVE-2023-7008, CVE-2024-2961, CVE-2024-33599, CVE-2024-33600, CVE-2024-33601, CVE-2024-33602 |
| 2.2.25| Apr 24, 2024|>= 1.23.0| 1.8.80| None | Fix plugin installation issue on CoreOS8 cluster, Update package dependencies to fix vulnerabilities - CVE-2023-45288, CVE-2024-24785, CVE-2023-44487, CVE-2023-45288 |
| 2.2.24| Feb 22, 2024|>= 1.21.0| 1.8.79| None | ROKS v4.15 cluster support, Fix plugin installation issue on CoreOS cluster |
| 2.2.23| Jan 29, 2024|>= 1.21.0| 1.8.78| None | Replaced UBI image with scratch image to fix CVEs - CVE-2023-3446, CVE-2023-3817, CVE-2023-5678 |
| 2.2.22| Nov 20, 2023|>= 1.21.0| 1.8.77| None | Golang updated to 1.21.4 to fix CVEs - CVE-2023-45283, CVE-2023-45284, UBI image updated to 8.9-1029 to fix CVEs - CVE-2023-22745, CVE-2007-4559, CVE-2023-40217, CVE-2023-4641 |
| 2.2.21| Nov 13, 2023|>= 1.21.0| 1.8.76| None | s3fs fuse version updated to v1.93, Golang updated to 1.21.3, Updated ibmc plugin to create release namespace with privileged labels for enforcing Pod Security Standards |
| 2.2.20| Oct 30, 2023|>= 1.21.0| 1.8.75| None | UBI image updated to 8.8-1072.1697626218 to fix CVE-2023-44487, Dependency updates to fix CVE-2023-39325 |
| 2.2.19| Oct 12, 2023|>= 1.21.0| 1.8.74| None | UBI image updated to 8.8-1072.1696517598 to fix CVEs- CVE-2023-29491, CVE-2023-4911, CVE-2023-4527, CVE-2023-4806, CVE-2023-4813 |
| 2.2.18| Sep 07, 2023|>= 1.21.0| 1.8.73| None | RHCOS 4.13 support for cos s3fs plugin, UBI image updated to 8.8-1037 to fix CVEs - CVE-2023-27536, CVE-2023-2602, CVE-2023-2603, CVE-2023-34969, CVE-2023-28321, CVE-2023-28484, CVE-2023-29469, Golang updated to 1.19.12 to fix CVE CVE-2023-29409 |
| 2.2.17| July 31, 2023|>= 1.21.0| 1.8.72| None | UBI image updated to 8.8-1014 to fix CVEs - CVE-2020-24736, CVE-2023-1667, CVE-2023-2283, CVE-2023-26604 Golang updated to 1.19.11 to fix CVE CVE-2023-29406 |
| 2.2.16| July 03, 2023|>= 1.21.0| 1.8.71| None | Allow auto creation and deletion for user defined bucket name |
| 2.2.15| June 19, 2023|>= 1.21.0| 1.8.70| None | UBI image updated to 8.8-860 to fix CVEs - CVE-2022-43552, CVE-2022-3204, CVE-2023-27535, CVE-2022-36227, CVE-2022-35252, Golang updated to 1.19.10 to fix CVEs - CVE-2023-29403, CVE-2023-29404, CVE-2023-29405, CVE-2023-29402, CVE-2023-29400, CVE-2023-24540, CVE-2023-24539, Dependency updates to fix CVEs - CVE-2023-29401, CVE-2023-26125, CVE-2022-3172 |
| 2.2.14| May 02, 2023|>= 1.21.0| 1.8.68| None | UBI image updated to 8.7-1107 to fix CVEs - CVE-2023-0361, Golang updated to 1.19.8 to fix CVEs - CVE-2023-24536, CVE-2023-24537, CVE-2023-24538, Enable PVC metrics export to node stats |
| 2.2.13| Apr 03, 2023|>= 1.21.0| 1.8.66| None | UBI image updated to 8.7-1085.1679482090 to fix CVEs- CVE-2022-4304,CVE-2022-4450,CVE-2023-0215,CVE-2023-0286, Fix for helm chart installation failing on regions with no Regional COS endpoint |
| 2.2.12| Mar 20, 2023|>= 1.21.0| 1.8.65| None | Golang updated to 1.19.7 for fixing CVE-2023-24532, Rebuild image to fix CVE-2023-23916 |
| 2.2.11| Mar 03, 2023|>= 1.21.0| 1.8.63| None | Golang updated to 1.19.6 for fixing  CVE-2022-41723 and CVE-2022-41724,  UBI image updated to ubi-minimal:8.7-1085 for fixing CVE-2022-4415, CVE-2020-10735, CVE-2021-28861, CVE-2022-45061, CVE-2022-40897 |
| 2.2.10| Feb 20, 2023|>= 1.21.0| 1.8.62| None | Default values for CPU request and CPU limit are updated to 100m & 500m respectively. Default values for Memory request and Memory limit are updated to 128Mi & 500Mi respectively. UBI image updated to 8.7-1049.1675784874 for fixing CVE-2022-47629. |
| 2.2.9|Feb 13, 2023|>= 1.21.0| 1.8.61| None | Option to disable reading secret from cross namespace for PVC creation, Auto populate the object store endpoint in the storage classes based on 'storage class' and 's3 provider' parameters for Satellite clusters, Support for Wasabi & AWS s3 provider on Satellite clusters|
| 2.2.8|Jan 23, 2023|>= 1.19.0| 1.8.60| None | UBI Image Update to 8:8.7-1049 for fixing CVE-2022-43680, CVE-2022-42010, CVE-2022-42011, CVE-2022-42012, CVE-2022-3821, CVE-2022-35737, CVE-2021-46848,Define PriorityClass for driver and plugin pods,Add tolerations for driver pod, Integrate keyprotect root key crn while creating buckets|
| 2.2.7|Jan 5, 2023 |>= 1.19.0| 1.8.59| None | GoLang updated to 1.18.9 - CVE-2022-41717, CVE-2022-41720, Rename flex StorageClasses to Smart |
| 2.2.6|Dec 15, 2022|>= 1.19.0| 1.8.58| None | Set tls-cipher-suite value to "default" in storage classes for redhat/openshift clusters |
| 2.2.5|Dec 09, 2022|>= 1.19.0| 1.8.58| None | UBI Image updated to 8.7-923.1669829893 to fix CVE-2022-42898, Default value of ephemeralStorageLimit parameter updated to 100Mi |
| 2.2.4|Dec 05, 2022|>= 1.19.0| 1.8.57| None | Golang updated to 1.18.8 - CVE-2022-41715,CVE-2022-2879,CVE-2022-2880 |
| 2.2.3|Nov 16, 2022|>= 1.19.0| 1.8.56| None | UBI Image updated to 8.7-923 - CVE-2016-3709,CVE-2022-30698,CVE-2022-30699,CVE-2022-1304 |
| 2.2.2|Nov 08, 2022|>= 1.19.0| 1.8.55| None | UBI Image updated to 8.6-994 - CVE-2022-37434,CVE-2020-35525,CVE-2020-35527,CVE-2022-3515,CVE-2022-2509,CVE-2022-40674 |
| 2.2.1|Sept 20, 2022|>=1.19.0| 1.8.54| None | UBI Image updated to 8.6-941, GoLang version updated to 1.18.6 for CVE-2022-27664|
| 2.2.0|Sept 12, 2022|>=1.19.0| 1.8.53| None | Recertification of charts, UBI Image updated to 8.6-902.1661794353 for fixing CVE-2022-32206,CVE-2022-32208,CVE-2022-2526|
| 2.1.21| Aug 24, 2022|>=1.19.0| 1.8.52| None | Golang updated to 1.18.5- CVE-2022-1962, UBI Image updated to 8.6-902- CVE-2022-1586, CVE-2022-2068, CVE-2022-1292, CVE-2022-2097|
| 2.1.20|Aug 17,  2022|>=1.19.0| 1.8.51| None | RedHat 8.6 support |
| 2.1.19|Jul 26,  2022|>=1.19.0| 1.8.50| None | Mount  /etc/os-release or /etc/lsb-release as read only file, Mount /etc/kubernetes  instaed of /etc or /usr/libexec/kubernetes to install the FlexVolume binary on the Nodes, Mount /usr/local/bin instead of /usr/local to install s3fs binary |
| 2.1.18| Jul 14, 2022|>=1.19.0| 1.8.49| None | UBI Image: 8.6-854, CVE-2022-29824, CVE-2021-40528, CVE-2022-22576, CVE-2022-27774, CVE-2022-27776, CVE-2022-27782, CVE-2022-25313, CVE-2022-25314, Golang-1.18.3|
| 2.1.17| Jun 27, 2022|>=1.19.0| 1.8.48| None | UBI Image: 8.6-751.1655117800, CVE-2022-1271, s3fs-fuse update to fix segfault issue, Add support to configure ephemeral storage of plugin and driver pods|
| 2.1.16| May 25, 2022|>=1.19.0| 1.8.47| None | UBI Image: 8.6-751, CVE-2021-3634,CVE-2021-3737,CVE-2021-4189, Enable adding ips via pvc annotation for configBucketAccess, Enable crftoken to be fetched from storage-secret-store|
| 2.1.15| May 06, 2022|>=1.19.0| 1.8.46| None | UBI Image: 8.5-243.1651231653, CVE-2022-1271, GoLang update to 1.17.9|
| 2.1.14| Apr 11, 2022|>=1.19.0| 1.8.45| None | UBI Image: 8.5-240.1648458092, support quota-limit option for COS buckets, support 2 stable versions of s3fs fuse, New version of helm ibmc plugin|
| 2.1.13| Mar 24, 2022|>=1.19.0| 1.8.44| None | UBI Image: 8.5-240, Golang updated to v1.16.15, s3fs fuse updated to v1.91|
| 2.1.12| Mar 10, 2022|>=1.19.0| 1.8.42| None | CVEID: CVE-2022-24407, UBI Image - 8.5-230.1645809059|
| 2.1.11| Feb 28, 2022|>=1.19.0 | 1.8.41| None | CVEID: CVE-2022-23772,CVE-2022-23773,CVE-2022-23806, GoLang update to 1.16.14 |
| 2.1.10| Feb 17, 2022|>=1.19.0 | 1.8.40| None | CVEID: CVE-2021-3538,CVE-2018-14632,CVE-2020-26160, UBI image update ubi-minimal:8.5-230 |
| 2.1.9 | Jan 24, 2022| >=1.19.0 | 1.8.39| None | CVEID: CVE-2021-44716, CVE-2021-44717 |
| 2.1.8 | Jan 17, 2022| >=1.19.0 | 1.8.38| None | UBI Base image 8.5-218, Bug fix to mask the keys in PVC log, CVE-2021-3712 |
| 2.1.7 | Nov 18, 2021| >=1.19.0 | 1.8.37| None | Gosec errors are fixed, UBI Base image 8.5-204, Golang 1.16.10 updated, CVE-2021-41772, CVE-2021-41771, CVE-2021-22947 |
| 2.1.6 | Oct 21, 2021| >=1.19.0 | 1.8.36| None | s3fs-fuse upgraded to V1.90,  Dependent packages upgraded. |
| 2.1.5 | Oct 4, 2021 | >=1.10.1-0 | 1.8.34| None | CVE-2021-36221, CVE-2021-29923, CVE-2021-33196, UBI Base image upgrade,Pull Golang Docker base image from artifactory, COS Endpoint update for jp-tok and uk-south region, COS Location Constraint Change for Sao Paulo 01, Option to deploy plugin in kube-system namespace when bucketAccessPolicy is enabled, Support dynamic provisioning for non-default regions in AWS s3 instance.|
| 2.1.4 | Aug 31, 2021| >=1.10.1-0 | 1.8.33| None | UBI Base image upgrade to fix CVE-2021-36221,CVE-2021-29923,CVE-2021-33196. GoLang Update  to v1.17  . Migrate from `ibmcom` public repository to `icr.io/cpopen` repo.  Fix for timeoutSeconds issue in livenessProbe and readinessProbe.|
| 2.1.3 | Aug 19, 2021| >=1.10.1-0 | 1.8.32| None | UBI Base image upgrade to fix CVE-2021-3520,CVE-2021-3516,CVE-2021-3517,CVE-2021-3518,CVE-2021-3537,CVE-2021-3541,CVE-2021-33196,CVE-2021-33198,CVE-2021-33195,CVE-2021-33197 and CVE-2021-34558. New version of ibmc plugin. ibm-object-storage-plugin support on ibm satellite cluster and aws s3 static provisioning. Support ibm-object-storage-plugin install in airgap environment. Default s3fs plugin install moved to `ibm-object-s3fs` namespace instead of `kube-system` namespace. ReadOnlyRootFilesystem enabled for plugin and driver pods. GoLang Update  to v1.16.6|
| 2.1.2 | June 21, 2021| >=1.10.1-0 | 1.8.30| None | New version of helm-ibmc plugin v2.0.5 and CVE-2021-31525,CVE-2021-33194,CVE-2021-27219 |
| 2.1.1 | June 03, 2021| >=1.10.1-0 | 1.8.29 | None | Issue in upgrading the chart using 'helm ibmc' upgrade command is fixed. New version of helm ibmc plugin is available. "default" value can be set in the PVC for tls-cipher-suite. CVE-2020-28851. |
| 2.1.0 | May 26, 2021| >=1.10.1-0 | 1.8.28 | None | UBI base image update to 8.4-200 |
| 2.0.9 | May 10, 2021| >=1.10.1-0 | 1.8.27 | None | UBI base image update to 8.3-298.1618432845. CVE-2021-20305. Flex has been replaced by Smart Tier in StorageClasses. Update in IAM Endpoints. Update in object-store-endpoint. Update ResourceConfiguration Endpoint. Fix pvc mount issue in private only VPC clusters.|
| 2.0.8 | Apr 19, 2021| >=1.10.1-0 | 1.8.25 | None | Fixed GoLang vulnerabilities and UBI Base image. GoLang update to 1.15.9, CVE-2021-3449, CVE-2021-3450, CVE-2021-27919, CVE-2021-27918 |
| 2.0.7 | Mar 26, 2021| >=1.10.1-0 | 1.8.24 | None | Fixed GoLang vulnerabilities and UBI Base image. GoLang update to 1.15.8, CVE-2021-3114, CVE-2021-3115, CVE-2020-28852, CVE-2020-28851 |
| 2.0.6 | Dec 19, 2020| >=1.10.1-0 | 1.8.23 | None | Enabled optional default parameters like secret name, bucket name and other for storage class, GoLang update to 1.15.5, Enabled image signing and updated images labels  and Fixed CVE-2020-28362 CVE-2020-28367 CVE-2020-28366 |
| 2.0.5 | Nov 25, 2020| >=1.10.1-0 | 1.8.22 | None | Fixed NilPointer error and CVEs CVE-2018-20843 CVE-2019-13050 CVE-2019-13627 CVE-2019-14889 CVE-2019-1551 CVE-2019-15903 CVE-2019-16168 CVE-2019-16935 CVE-2019-19221 CVE-2019-19906 CVE-2019-19956 CVE-2019-20218 CVE-2019-20386 CVE-2019-20387 CVE-2019-20388 CVE-2019-20454 CVE-2019-20907 CVE-2019-5018 CVE-2020-10029 CVE-2020-13630 CVE-2020-13631 CVE-2020-13632 CVE-2020-14422 CVE-2020-1730 CVE-2020-1751 CVE-2020-1752 CVE-2020-6405 CVE-2020-7595 CVE-2020-8177 |
| 2.0.4 | Oct 07, 2020| >=1.10.1-0 | 1.8.21 | None | Updated s3fs-fuse to fix IAM Apikey token refresh issue, Upgraded Golang to v1.15.2 for fixing CVE-2020-24553 |
| 2.0.3 | Sep 23, 2020| >=1.10.1-0 | 1.8.20 | None | Enabled Bucket AccessPolicy for VPC-Gen2 clusters, Upgraded Golang to v1.13.15 for fixing CVE-2020-16845 and CVE-2020-24553, Upgraded UBI base image to 8.2-349 for fixing CVE-2020-14352 |
| 2.0.2 | Aug 06, 2020| >=1.10.1-0 | 1.8.19 | None | Upgraded Golang to v1.13.14 for fixing CVE-2020-15586 and CVE-2020-14039, Fix for plugin deployment in custom namespace for IKS cluster |
| 2.0.1 | July 10, 2020| >=1.10.1 | 1.8.18 | None | Update UBI base Image, Set default values for `auto-create-bucket`, `auto-delete-bucket` and `bucket` annotations in PVC |
| 2.0.0 | June 16, 2020| >=1.10.1 | 1.8.17 | None | Cert 2.0 Certification, Restrict COS Access Secret for selected namespaces, Allowed re-using existing bucket with `auto-create-bucket: true`, GoLang: v1.13.5 |
| 1.1.4 | Mar 10, 2020| >=1.10.1 | 1.8.13 | None | Resolved security issue CVE-2020-1712, Updated s3fs-fuse to use latest commit, Enabled support for 'auto_cache' option from pvc spec, GoLang: v1.13.4 |
| 1.1.3 | Feb 13, 2020| >=1.10.1 | 1.8.12 | None | Resolved security issues CVE-2019-13734 and CVE-2019-18408, Updated `ibmc` helm plugin to support object-storage plugin installation/upgradation with `helm v2` and `helm v3`, Updated helm chart to auto-recreate plugin pods when upgrading plugin, GoLang: v1.13.4 |
| 1.1.2 | Dec 09, 2019| >=1.10.1 | 1.8.11 | None | Non-root user access broken for K8S >= 1.15.4, GoLang: v1.13.4 |
| 1.1.1 | Nov 22, 2019| >=1.10.1 | 1.8.10 | None | Golang update to version 1.13.4, Gosec enabled in plugin code; GoLang: v1.13.4, PSIRT image vulnerability fix |
| 1.1.0 | Oct 25, 2019| >=1.10.1 | 1.8.9 | None | Updated helm chart to support plugin deployment on `VPC` clusters, Updated `ibmc` helm plugin to detect VPC cluster and deploy plugin accordingly, Disabled mounting of `/` directory inside object-storage-plugin driver pods; GoLang: v1.12.9 |
| 1.0.9 | Sep 09, 2019| >=1.10.1 | 1.8.8 | None | Upgraded GoLang to v1.12.9 for fixing GoLang vulnerability issue, Setting 'default_acl=private' in driver, when using HMAC credentials; GoLang: v1.12.9 |
| 1.0.8 | Jun 24, 2019| >=1.10.1 | 1.8.7 | None | Updated chart to set cpu and memory limits for object-storage plugin pods, Updated registry URL to `icr.io`, Updated helm repo from `iks-charts` to `ibm-charts`, Updated chart to create storageclasses with `tls-cipher-suite` as per worker node's operating system family(`Debian/Red Hat`), Updated `ibmc` plugin to use `--set workerOS=<debian / redhat>` while installing/upgrading object-storage plugin depending on worker node's operating system family, Build images on Red Hat UBI (Universal Base Image) for red-hat-openshift support, README Update; Readiness probes configured in driver/plugin containers; GoLang: v1.12.1 |
| 1.0.7 | May 17, 2019| >=1.10.1 | 1.8.6 | None | Allow late binding and dynamic provisioning of volume, Updated helm chart to deploy on managed openshift on IBM Kubernetes Service(IKS), Updated `ibmc` plugin to install/uninstall chart `without tiller`, Updated `ibmc` plugin to install specific version of the chart, Updated `ibmc` plugin to fix the issue while installing the chart with lower version of `kubectl` client; GoLang: v1.12.1 |
| 1.0.6 | May 02, 2019| >=1.10.1 | 1.8.6 | None | Use ibm-cos-sdk instead of AWS SDK; Mask IAM credentials in driver log; Change helm repo from ibm to iks-charts  |
| 1.0.5 | Apr 18, 2019| >=1.10.1 | 1.8.5 | None | Mount bucket as per AccessMode defined in PVC; Exposed s3fs options from PVC, like use-xattr and readwrite-timeout; Enabled deployment on RHEL and CentOS; GoLang: v1.12.1 |
| 1.0.4 | Apr 05, 2019| >=1.9.1 | 1.8.4 | None | Updated COS endpoints; updated storageclass templates for `Mexico` datacenter; drop `ALL` capabilities from plugin containers; replaced beta apiVersion with stable apiVersion for underlying plugin components; added option `useCustomPSP` to install plugin using custom PSP for ICP; updated `ibmc` helm plugin upgrade logic; replaced deprecated `kubernetes-incubator/external-storage` package with `kubernetes-sigs/sig-storage-lib-external-provisioner`; added support to override `tls-cipher-suite` through PVC annotations; updated Golang version to 1.12.1 for security fixes; restore original sshd_config file on worker nodes after installing driver binary; README update. |
| 1.0.3 | Feb 21, 2019| >=1.9.1 | 1.8.3 | None | Enabled deployment of custom PSP for cos volume plugin for ICP; enabled deployment of plugin under custom namespace for ICP;  added support to have secret and PVC in different namespace; added support to override `curldbg`, `dbglevel`, `connect_timeout`, `readwrite_timeout`, `stat_cache_expire` and `use_xattr` options through PVC annotations; README update. |
| 1.0.2 | Jan 11, 2019| >=1.9.1 | 1.8.2 | None | Storageclass templates update for `San Jose`, `Tokyo`, `Milan` and `London` datacenters; update chart to conform to Hybrid Content Standards and Guidelines; enhance `ibmc` helm plugin to support ICP and IKS. |
| 1.0.1 | Sep 10, 2018| >=1.9.1 | 1.8 | None | Modify storageclasses templates and installation doc updates. |
| 1.0.0 | Aug 31, 2018| >=1.8.3 | 1.8 | None | Installation doc updates. |
| 0.0.2 | Aug 03, 2018| >=1.8.3 | 1.8 | None  | Added --update option to ibmc helm plugin for helm plugin upgrade support and installation doc updates. |
| 0.0.1 | Jul 23, 2018| >=1.8.3 | 1.8 | None | Chart includes dynamic provisioner (ibmcloud-object-storage-plugin), driver (ibmcloud-object-storage-driver) and Storageclasses (ibmc-s3fs...). |
