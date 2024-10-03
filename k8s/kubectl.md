## kubectl Quick Reference
---
 - [kubectl Quick Reference](https://kubernetes.io/docs/reference/kubectl/quick-reference/)
 - delete all resources
`kubectl delete all --all`
### Kustomize
- configuration management tool for Kubernetes
- Base and overlays
### Helm
> `helm create` <*name*>
> 
> `helm install` <*release name*> <*path*>
> - --debug
> - --dry-run
>  
> `helm install --debug --dry-run` <*release name*> <*path*>
- retrieve the release and view the current loaded template `helm get manifest` <*release name*>
>
> `helm uninstall` <*release name*>
- template directive
> {{`namespaced.objects`}}
- package helm charts
   `helm package` <*path*>
