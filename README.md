[![Maven Package upon a push](https://github.com/mosip/mosip-file-server/actions/workflows/push_trigger.yml/badge.svg?branch=master)](https://github.com/mosip/mosip-file-server/actions/workflows/push_trigger.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?branch=master&project=mosip_mosip-file-server
&metric=alert_status)](https://sonarcloud.io/dashboard?branch=master&id=mosip-file-server)


# mosip-file-server
mosip-file-server is used to share .well-known URIs related to DIDs, Hubs, and Agents. with MOSIP partners, open-source communities, etc.
## .well-known
* For v2, provide the JSON files under `https://github.com/mosip/mosip-infra/tree/{branch-name}/deployment/sandbox-v2/roles/mosip-file-server/templates` in [mosip-infra](https://github.com/mosip/mosip-infra.git).
* For v3, provide the JSONs in `https://github.com/mosip/mosip-helm/blob/{branch-name}/charts/mosip-file-server/templates/configmaps.yaml` file in [mosip-helm](https://github.com/mosip/mosip-helm.git).
## mobileapp
* Provide the mobileapp apk/zip files under mosip-file-server's persistence volume storage.
