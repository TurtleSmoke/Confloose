## Confloose command to have fun together for PEDAGOGICAL PURPOSES

### Reverse mouse direction

```shell
xinput --set-prop  "$(xinput | grep -o "[a-zA-Z][a-zA-Z ]*Mouse")" 152 1 0 0 0 1 0 0 0 -1
```

## Revert

```shell
xinput --set-prop  "$(xinput | grep -o "[a-zA-Z][a-zA-Z ]*Mouse")" 152 1 0 0 0 1 0 0 0 1
```
