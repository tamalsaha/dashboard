# dashboard

```console
> kubebuilder init --domain kubedb.dev --skip-go-version-check
> kubebuilder edit --multigroup=true

> kubebuilder create api --group dashboard --version v1alpha1 --kind Pgadmin
> kubebuilder create api --group dashboard --version v1alpha1 --kind Phpmyadmin
> kubebuilder create api --group dashboard --version v1alpha1 --kind Dbgate
> kubebuilder create api --group dashboard --version v1alpha1 --kind Superset
```
