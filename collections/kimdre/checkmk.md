A collection to protect [CheckMK](https://checkmk.com/) instance against common attacks:
 - CheckMK parser
 - CheckMK bruteforce detection

## Acquisition template

Example acquisition for this collection:

```yaml
---
filenames:
 - /omd/sites/*/var/log/web.log
labels:
  type: checkmk
```