# radverkehrstote


@[vega-lite](https://data.world/example.vl.json)


@import "https://github.com/vizsim/BerlinTrafficCounts/blob/master/jsons_trendcharts/plz_trendChart_10367.json" {as="vega-lite"}

```vega-lite
{
  "$schema": "https://vega.github.io/schema/vega-lite/v2.json",
  "description": "A simple bar chart with embedded data. An example vega-lite file.",
  "width": 360,
  "data": {
    "values": [
      {"a": "A","b": 28}, {"a": "B","b": 55}, {"a": "C","b": 43},
      {"a": "D","b": 91}, {"a": "E","b": 81}, {"a": "F","b": 53},
      {"a": "G","b": 19}, {"a": "H","b": 87}, {"a": "I","b": 52}
    ]
  },
  "mark": "bar",
  "encoding": {
    "x": {"field": "a", "type": "ordinal"},
    "y": {"field": "b", "type": "quantitative"}
  }
}
```
@import "https://vizsim.github.io/BerlinTrafficCounts/jsons_trendcharts/plz_trendChart_10367.json" {as="vega"}
