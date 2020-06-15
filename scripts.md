# Add to every query

```
for rq in *.rq; do { echo -e '<text to add>'; cat "$rq"; } >"$rq.tmp" && mv "$rq.tmp" "$rq"; done
```
