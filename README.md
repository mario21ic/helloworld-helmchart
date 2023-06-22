# Helm Chart repository:


Add repository:
```
helm repo add myrepo https://mario21ic.github.io/helloworld-helmchart/
```

Search helm charts inside myrepo:
```
helm search repo myrepo
```

Install:
```
helm install hello-helmchart-repo myrepo/helloworld
helm list -A
```
