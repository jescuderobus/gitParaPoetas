# Ejemplos geojson

Fuente: https://github.blog/changelog/2022-03-17-mermaid-topojson-geojson-and-ascii-stl-diagrams-are-now-supported-in-markdown-and-as-files/

## Ejemplo 1 - Ciudades donde estuvo Nebrija

```geojson
{
  "type": "MultiPoint",
  "coordinates": [
      
          [-6.07529,36.92077],
          [-5.66388, 40.96882],
          [11.33875,44.49381],
          [-5.7974,38.97665],
          [-3.35996,40.48205]
      
  ]
}
```

## Ejemplo 2 - usando la web https://geojson.io

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {
        "marker-color": "#7e7e7e",
        "marker-size": "medium",
        "marker-symbol": "",
        "name": "Lebrija"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -6.04248046875,
          36.95208671786997
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "marker-color": "#7e7e7e",
        "marker-size": "medium",
        "marker-symbol": "",
        "name": "Salamanca"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -5.679931640625,
          40.959159772134896
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "marker-color": "#7e7e7e",
        "marker-size": "medium",
        "marker-symbol": "",
        "name": "Bolonia"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          11.35986328125,
          44.49650533109348
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "marker-color": "#7e7e7e",
        "marker-size": "medium",
        "marker-symbol": "",
        "name": "Coca"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -4.522247314453125,
          41.2186945608925
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "marker-color": "#7e7e7e",
        "marker-size": "medium",
        "marker-symbol": "",
        "name ": "Alcalá de Henares"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -3.4442138671875,
          40.482470524589516
        ]
      }
    }
  ]
}
```