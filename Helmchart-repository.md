# Creating a helm chart repository:

Check if the directory is ok:
```
helm lint charts/helloworld/
```

Make a robots.txt file:
```
echo -e "User-Agent: *\nDisallow: /" > robots.tx
```

Create a package:
```
$ helm package charts/helloworld
```

Create index.yaml file:
```
$ helm repo index --url https://mario21ic.github.io/helloworld-helmchart/ .
``

Based on https://www.opcito.com/blogs/creating-helm-repository-using-github-pages
