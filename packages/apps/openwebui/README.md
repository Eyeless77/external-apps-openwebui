# openwebui

Managed Open WebUI wrapper chart for Cozystack.

## Parameters

### Open WebUI parameters

| Name                            | Description                              | Type       | Value       |
| ------------------------------- | ---------------------------------------- | ---------- | ----------- |
| `openwebui`                     | Open WebUI configuration.                | `object`   | `{}`        |
| `openwebui.replicaCount`        | Number of replicas.                      | `int`      | `1`         |
| `openwebui.service`             | Service settings.                        | `object`   | `{}`        |
| `openwebui.service.type`        | Service type.                            | `string`   | `ClusterIP` |
| `openwebui.ingress`             | Ingress settings.                        | `object`   | `{}`        |
| `openwebui.ingress.enabled`     | Enable ingress.                          | `bool`     | `false`     |
| `openwebui.ingress.class`       | IngressClass name (usually tenant name). | `string`   | `""`        |
| `openwebui.ingress.host`        | Ingress host.                            | `string`   | `""`        |
| `openwebui.ingress.tls`         | Enable TLS section generation.           | `bool`     | `false`     |
| `openwebui.ingress.annotations` | Additional ingress annotations.          | `object`   | `{}`        |
| `openwebui.persistence`         | Storage settings.                        | `object`   | `{}`        |
| `openwebui.persistence.enabled` | Enable persistent volume claim.          | `bool`     | `true`      |
| `openwebui.persistence.size`    | Persistent volume size.                  | `quantity` | `10Gi`      |
| `openwebui.ollama`              | Embedded Ollama chart toggle.            | `object`   | `{}`        |
| `openwebui.ollama.enabled`      | Enable component.                        | `bool`     | `false`     |
| `openwebui.pipelines`           | Embedded Pipelines chart toggle.         | `object`   | `{}`        |
| `openwebui.pipelines.enabled`   | Enable component.                        | `bool`     | `true`      |

