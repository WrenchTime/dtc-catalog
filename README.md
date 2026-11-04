# dtc-catalog

Generic OBD-II trouble-code titles the WrenchTime app downloads, one flat
`{ "CODE": "short title" }` file per language, keys uppercase and sorted.

Built daily by [archive-sync](https://github.com/WrenchTime/archive-sync)
from the YAML under `data/generic/` of [WrenchTime/OBDex](https://github.com/WrenchTime/OBDex),
a fork of [foerbsnavi/OBDex](https://github.com/foerbsnavi/OBDex). Only the
short `title` of each entry is kept.

Licence: **CC0-1.0**, as the OBDex data.

- OBDex commit: `372378bff153408e5ab2c9e1ddbf264c60273fbf`
- `dtc-generic-en.json`: 9533 codes
- `dtc-generic-de.json`: 9533 codes

Do not edit by hand: the next run overwrites every file.
