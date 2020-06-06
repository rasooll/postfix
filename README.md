postfix
=======
A SMTP relay host for transactional based emails from within a cluster.

Current chart version is `0.0.1`





## Chart Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| affinity | object | `{}` |  |
| fullnameOverride | string | `""` |  |
| image.pullPolicy | string | `"Always"` |  |
| image.repository | string | `"rasooll/postfix"` |  |
| image.tag | string | `"latest"` |  |
| nameOverride | string | `""` |  |
| nodeSelector | object | `{}` |  |
| postfix.relay_host | string | `nil` |  |
| postfix.relay_port | int | `25` |  |
| postfix.relay_tls | boolean | `false` |  |
| postfix.relay_myhostname | string | `nil` |  |
| postfix.relay_auth | boolean | `false` |  |
| postfix.relay_password | string | `nil` |  |
| postfix.relay_username | string | `nil` |  |
| postfix.limit_per_hour | int | `10` |  |
| replicaCount | int | `1` |  |
| resources | object | `{}` |  |
| service.port | int | `25` |  |
| service.type | string | `"ClusterIP"` |  |
| tolerations | list | `[]` |  |
