## kubectl-testkube generate tests-crds

Generate tests CRD file based on directory

### Synopsis

Generate tests manifest based on directory (e.g. for ArgoCD sync based on tests files)

```
kubectl-testkube generate tests-crds <manifestDirectory> [flags]
```

### Options

```
  -h, --help   help for tests-crds
```

### Options inherited from parent commands

```
  -a, --api-uri string      api uri, default value read from config if set
  -c, --client string       client used for connecting to Testkube API one of proxy|direct (default "proxy")
      --namespace string    Kubernetes namespace, default value read from config if set (default "testkube")
      --oauth-enabled       enable oauth
      --telemetry-enabled   enable collection of anonumous telemetry data
      --verbose             show additional debug messages
```

### SEE ALSO

* [kubectl-testkube generate](kubectl-testkube_generate.md)	 - Generate resources commands

