---
title: IDNO
permalink: /terms/v7/IDNO.html
layout: none
redirect-from:
  - /terms/v7/IDNO
...

```

%YAML 1.2
---
type: structure

uri: https://gedcom.io/terms/v7/IDNO

standard tag: IDNO

descriptions:
  - Identification number
  - An Individual Attribute. See also INDIVIDUAL_ATTRIBUTE_STRUCTURE.
  - identifying number
  - A number or other string assigned to identify a person within some
    significant external system. It must have a TYPE substructure to define
    what kind of identification number is being provided.

payload: http://www.w3.org/2001/XMLSchema#string

substructures:
  "https://gedcom.io/terms/v7/ADDR": "{0:1}"
  "https://gedcom.io/terms/v7/AGE": "{0:1}"
  "https://gedcom.io/terms/v7/AGNC": "{0:1}"
  "https://gedcom.io/terms/v7/ASSO": "{0:M}"
  "https://gedcom.io/terms/v7/CAUS": "{0:1}"
  "https://gedcom.io/terms/v7/DATE": "{0:1}"
  "https://gedcom.io/terms/v7/EMAIL": "{0:M}"
  "https://gedcom.io/terms/v7/FAX": "{0:M}"
  "https://gedcom.io/terms/v7/NOTE": "{0:M}"
  "https://gedcom.io/terms/v7/OBJE": "{0:M}"
  "https://gedcom.io/terms/v7/PHON": "{0:M}"
  "https://gedcom.io/terms/v7/PLAC": "{0:1}"
  "https://gedcom.io/terms/v7/RELI": "{0:1}"
  "https://gedcom.io/terms/v7/RESN": "{0:1}"
  "https://gedcom.io/terms/v7/SDATE": "{0:1}"
  "https://gedcom.io/terms/v7/SNOTE": "{0:M}"
  "https://gedcom.io/terms/v7/SOUR": "{0:M}"
  "https://gedcom.io/terms/v7/TYPE": "{1:1}"
  "https://gedcom.io/terms/v7/UID": "{0:M}"
  "https://gedcom.io/terms/v7/WWW": "{0:M}"

superstructures:
  "https://gedcom.io/terms/v7/record-INDI": "{0:M}"
...

```