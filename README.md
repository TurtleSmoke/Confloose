## Confloose command to have fun together for PEDAGOGICAL PURPOSES

### Reverse mouse direction

```shell
xinput --set-prop "$(xinput | grep "Mouse" | sed -e 's/.*id=\([0-9]*\).*/\1/g')" 152 1 0 0 0 1 0 0 0 -1
```

## Revert

```shell
xinput --set-prop "$(xinput | grep "Mouse" | sed -e 's/.*id=\([0-9]*\).*/\1/g')" 152 1 0 0 0 1 0 0 0 1
```
