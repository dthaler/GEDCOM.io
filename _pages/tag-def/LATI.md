---
title: LATI
permalink: /terms/v7/LATI.html
layout: none
redirect-from:
  - /terms/v7/LATI
...

```

%YAML 1.2
---
lang: en-US

type: structure

uri: https://gedcom.io/terms/v7/LATI

standard tag: LATI

specification:
  - Latitude
  - |
    A latitudinal coordinate. The payload is either N (for a coordinate north
    of the equator) or S (for a coordinate south of the equator) followed by a
    decimal number of degrees. Minutes and seconds are not used and should be
    converted to fractional degrees prior to encoding.
    
    18 degrees, 9 minutes, and 3.4 seconds North would be formatted as
    N18.150944.

label: 'Latitude'

payload: http://www.w3.org/2001/XMLSchema#string

substructures: {}

superstructures:
  "https://gedcom.io/terms/v7/MAP": "{1:1}"
...

```
