# History from 16679935 to 16679975

```shell
stellar-core catchup 16679975/41
horizon db reingest range 16679935 16679975

# run stellar-core with SUPPORTED_META_VERSION=2
stellar-core catchup 16679975/41
horizon expingest verify-range --from 16679935 --to 16679975
```
