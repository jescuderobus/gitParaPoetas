
## Mapa Político de Europa en tiempos de Nebrija 

- http://geacron.com/map/atlas/mapal.html?lang=es
- https://chronas.org/
- openhistoricalmap.org


## Ciudades donde estuvo Nebrija (geojson)

```geojson
{
  "type": "MultiPoint",
  "coordinates": [
      [
          [-6.07529,36.92077],
          [-5.66388, 40.96882],
          [11.33875,44.49381],
          [-5.7974,38.97665],
          [-3.35996,40.48205]
      ]
  ]
}
```

## Ciudades donde estuvo Nebrija (topojson)

```topojson
 {
  "type": "Topology",
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "properties": {
            "prop0": "value0"
          },
          "coordinates": [102, 0.5]
        },
        {
          "type": "LineString",
          "properties": {
            "prop0": "value0",
            "prop1": 0
          },
          "arcs": [0]
        },
        {
          "type": "Polygon",
          "properties": {
            "prop0": "value0",
            "prop1": {
              "this": "that"
            }
          },
          "arcs": [[-2]]
        }
      ]
    }
  },
  "arcs": [
    [[102, 0], [103, 1], [104, 0], [105, 1]],
    [[100, 0], [101, 0], [101, 1], [100, 1], [100, 0]]
  ]
}
```