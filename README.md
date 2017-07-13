Spark Analytics
===============

```
cat selected | awk  '{ print ",\x22"$1"\x22" }' | tee -a ../save-filter-table.scala 
```

