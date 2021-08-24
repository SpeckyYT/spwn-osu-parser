# osu-parser

SPWN parser for `.osu` files.

## Usage

```spwn
parse = import osu-parser

map = $.readfile('myMap.osu')
parsedMap = parse(map)
$.print(parsedMap)
```
