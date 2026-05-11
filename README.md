# external-apps-openwebui

External applications catalog for Cozystack with Open WebUI.

## Install

1. Push this repository to a public Git hosting.
2. Update `init.yaml` with your repository URL.
3. Apply bootstrap manifest:

```bash
kubectl --kubeconfig kubeconfig apply -f init.yaml
```

After Flux reconciliation, Open WebUI will appear in the Cozystack application catalog.

Create a test instance:

```bash
kubectl --kubeconfig kubeconfig apply -f examples/openwebui.yaml
```

## Repository layout

```text
init.yaml
packages/
  core/platform/
  apps/openwebui/
examples/
  openwebui.yaml
```
