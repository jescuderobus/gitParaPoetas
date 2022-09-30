# STL

STL es uno de los formatos añadidos a la integración con markdown en Github.

STL (Standard Triangle Language), o tambien STereoLithography, es un tipo de fichero que contiene una superficie es definida por una malla (Mesh) de triángulos. Estos ficheros pueden ser binarios o de texto, Github sólo puede interpretar los de texto, por ello los binarios habria que convertirlos.

- https://www.meshconvert.com/

- https://www.vanderveer.io/github-markdown-render-stl/


# cubo

Este es el primer fichero que hemos procesado, y el más fácil de encontrar.

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

