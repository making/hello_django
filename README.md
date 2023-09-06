# Hello Django


Deploy to Tanzu Application Platform


```
tanzu apps workload apply hello-django \
  --type web \
  --git-repo https://github.com/making/hello_django \
  --git-branch main \
  --app hello-django \
  --param clusterBuilder=full-jammy \
  --label apps.tanzu.vmware.com/has-tests=true \
  -n demo
```
