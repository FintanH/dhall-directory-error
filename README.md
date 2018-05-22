# To Reproduce

```bash
cd Inner/Dir2
dhall <<< "./type"
```

# Does work if:

```bash
dhall <<< "./Inner/Dir2/type"
```

or

```bash
cd Inner
dhall <<< "./Dir2/type"
```
