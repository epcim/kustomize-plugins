## CrdGenerator

Given a definition like:
```
---
apiVersion: agilicus/v1
kind: CrdGenerator
metadata:
  name: not-used-crd
resources: 
  - git@git.agilicus.com:kcharts/elastic.git
```

Fetch the CRD from the given resources, strip all but them, and relay them out.
