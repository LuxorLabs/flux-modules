# Notes

## Linkerd

- Manifests were generated with the following linkerd version
```bash
$ linkerd version  
Client version: stable-2.14.10
Server version: unavailable
```

- Prior to adding linkerd perform the following
```bash
$ linkerd check --pre 
```

```bash
$ linkerd install --crds > manifests/linkerd/crds/manifests.yaml
```