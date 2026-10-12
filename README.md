# test123

```mermaid
pie
"Dogs" : 386
"Cats" : 85.9
"Rats" : 15
```


```mermaid
flowchart LR
    subgraph Bronze["Bronze layer"]
        RawSales[Raw sales]
        RawProducts[Raw products]
    end
    subgraph Silver["Silver layer"]
        CleanSales[Clean sales]
        CleanProducts[Clean products]
    end
    RawSales --> CleanSales
    RawProducts --> CleanProducts
```
