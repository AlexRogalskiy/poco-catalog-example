# Poco Catalog Example
[Documentation](https://getpoco.io)

`poco-catalog.yml` example:
```
hello-world:
  file: poco.yaml
  git: git@github.com:shiwaforce/poco-example-hello-world.git
  repository_dir: poco-example-hello-world
```

Add to your poco repo
```
poco repo add my-catalog git@github.com:shiwaforce/poco-catalog-example.git
```

List project:
```
poco catalog
```

Start project:
```
poco up hello-world
```
