# angi-test-charts
Helm Charts for angi-test

This repo contains helm charts for:
- [`Argo CD Applications`](./argo_applications/)
- [`Application helm charts`](./helm_charts/)

> `values.yaml` in argo_applications makes an assumption that you will be running argoCD on the same kubernetes cluster where you want to deploy applications. If that is not true, you must update the `destination.server` in [argo_applications/envs/dev/values.yaml](argo_applications/envs/dev/values.yaml)
