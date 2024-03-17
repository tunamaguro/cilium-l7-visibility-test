# cilium-l7-visibility-test

1. deploy demo app
```bash
$ argocd app create --file apps/demo-app.yaml 
```

2. create `CiliumNetworkPolicy`
```bash
$ argocd app create --file apps/demo-app.yaml 
```

3. view hubble
```bash
$ cilium hubble ui
```

or

```bash
$ cilium hubble port-forward&
$ hubble observe
```