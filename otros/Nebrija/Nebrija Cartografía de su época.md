
http://geacron.com/map/atlas/mapal.html?lang=es



## Instrucciones para crear los mapas en Windows

- En windows "Win"+"ImpPant" guarda la captura de pantalla directamente en un fichero en la carpeta "Imagenes"
- Para recortar el trozo que nos importa usamos xnView, que ademas nos renombra los ficheros.
- He montado el carrusel buscando un javascript que lo haga con efecto crossfade.

```geojson
{
  "type": "Polygon",
  "coordinates": [
      [
          [-5,37],
          [12,41],
          
      ]
  ]
}
```

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

```stl
solid Mesh
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 10.000000 0.000000 0.000000
      vertex 10.000000 -20.000000 20.000000
      vertex 10.000000 -20.000000 0.000000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 10.000000 0.000000 20.000000
      vertex 10.000000 -20.000000 20.000000
      vertex 10.000000 0.000000 0.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex -10.000000 -20.000000 0.000000
      vertex -10.000000 0.000000 20.000000
      vertex -10.000000 0.000000 0.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex -10.000000 -20.000000 20.000000
      vertex -10.000000 0.000000 20.000000
      vertex -10.000000 -20.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex -10.000000 -20.000000 20.000000
      vertex 10.000000 0.000000 20.000000
      vertex -10.000000 0.000000 20.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 10.000000 -20.000000 20.000000
      vertex 10.000000 0.000000 20.000000
      vertex -10.000000 -20.000000 20.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex -10.000000 0.000000 0.000000
      vertex 10.000000 -20.000000 0.000000
      vertex -10.000000 -20.000000 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 10.000000 0.000000 0.000000
      vertex 10.000000 -20.000000 0.000000
      vertex -10.000000 0.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex -10.000000 0.000000 0.000000
      vertex 10.000000 0.000000 20.000000
      vertex 10.000000 0.000000 0.000000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex -10.000000 0.000000 20.000000
      vertex 10.000000 0.000000 20.000000
      vertex -10.000000 0.000000 0.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 10.000000 -20.000000 0.000000
      vertex -10.000000 -20.000000 20.000000
      vertex -10.000000 -20.000000 0.000000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 -0.000000
    outer loop
      vertex 10.000000 -20.000000 20.000000
      vertex -10.000000 -20.000000 20.000000
      vertex 10.000000 -20.000000 0.000000
    endloop
  endfacet
endsolid Mesh

  
```

