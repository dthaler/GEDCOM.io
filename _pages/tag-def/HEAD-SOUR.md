---
title: HEAD-SOUR
permalink: /terms/v7/HEAD-SOUR.html
layout: none
redirect-from:
  - /terms/v7/HEAD-SOUR
...

```

%YAML 1.2
---
type: structure

uri: https://gedcom.io/terms/v7/HEAD-SOUR

standard tag: SOUR

descriptions:
  - Source
  - An identifier for the product producing this dataset. A registration
    process for these identifiers existed for a time, but no longer does. If an
    existing identifier is known, it should be used. Otherwise, a URI owned by
    the product should be used instead.

payload: http://www.w3.org/2001/XMLSchema#string

substructures:
  "https://gedcom.io/terms/v7/CORP": "{0:1}"
  "https://gedcom.io/terms/v7/HEAD-SOUR-DATA": "{0:1}"
  "https://gedcom.io/terms/v7/NAME": "{0:1}"
  "https://gedcom.io/terms/v7/VERS": "{0:1}"

superstructures:
  "HEAD pseudostructure": "{0:1}"
...

```