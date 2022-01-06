# With ko builder

```
export SKAFFOLD_DEFAULT_REPO=***
```

None of the following commands port forwards:

```
skaffold debug
skaffold debug --port-forward
skaffold debug --port-forward=debug
skaffold debug --port-forward=pods
skaffold debug --port-forward=user
skaffold run --port-forward
```
