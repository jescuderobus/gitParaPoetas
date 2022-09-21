Aquí está toda la información necesaria para ir descubriendo Git y sus posibilidades. Funciona como una serie de tareas que tendrás que ir realizando cada día.

# día 0 - entender Git

- Ver el video [¿Que es Git?](https://www.youtube.com/watch?v=jGehuhFhtnE) para conocer esta herramienta y sus posibilidades.

  
- Unas pocas reglas antes de empezar para que el uso de este repositorio sea provechoso:
  - Un contenido no debe borrarse si no se considera terminado.
  - Siempre que podamos vamos a trabajar con texto Markdown, svg, etc... evitando subir ficheros binarios.
  - En markdown-github para escribir poesias hay que usar la _ruptura blanda_, los versos se terminan con dos espacios en blanco. Así se visualizan correctamente en github.com.

- Instala Git, VS code y clona el repositorio a tu ordenador, te pueden resultar útiles las indicaciones que se ven en este [video](https://www.youtube.com/watch?v=XycExtQ31GE).

```
git clone https://github.com/jescuderobus/gitParaPoetas.git
```

# día 1 - aprender Git

- Aprender el vocabulario asociado a la herramienta: push, pull, commit, fetch, merge, clone, branch, checkout ...
  
- Seguir completamente alguno de los multiples tutoriales que hay en la web para empezar con Git:
  - [Tutorial de Lucas Moy](https://www.youtube.com/watch?v=CK5ZcKZsMRs)
  - [Tutorial de Hola Mundo](https://www.youtube.com/watch?v=VdGzPZ31ts8)
  - [Tutorial de pildoras informáticas](https://www.youtube.com/watch?v=ANF1X42_ae4&list=PLU8oAlHdN5BlyaPFiNQcV0xDqy0eR35aU) (preferido)

- Añadir dos contenidos al repositorio (no tienen porque estar completos) y completar dos contenidos que ya estén.


# día 2 - aprender Git (2)

- (vuelves a hacer lo mismo que ayer) Añadir un contenido al repositorio (no tienen porque estar completos) y completar dos contenidos que ya estén. Así en apenas dos dias además de los 8-9 archivos originales habrá tres creados por tí y al menos 4 más con aportaciones tuyas.

- Termina de visualizar los videos que sugerimos el día de ayer, no continues a los días siguientes hasta que hayas completado la visualización de al menos uno de los tres sugeridos.

- Debes encontrarte cómodo con subir código con VS code, ver como se trabaja en el editor, y comprobar como aparecen los cambios en github.com.


# día 3 - git log, git help (primeros comandos en CLI)
- Ya debes tener este repositorio instalado en tu ordenador, haber hecho un a contribución de tres ficheros nuevos de los que tu seas el iniciador, y haber trabajado en otros cuatro o cinco ficheros más. Durante los últimos dos días has estado trabajando en este proyecto. 

- Vamos a abandonar la falsa seguridad que nos da el entorno gráfico, porque es verdad que nos oculta toda la complejidad de Git, pero tambien nos oculta toda su potencia.

- Abrimos el terminal y ejecutamos:

```
git help
```

```
git log
```

```
git status
```
observa cuidadosamente la salida de estos programas intentando entender la información que te aportan sobre la autoria de los distintos ficheros del proyecto.

# dia 4 - git pull, git add, git commit, git push

Una de las formas más habituales de trabajar es hacer un pull del repositorio al inicio de la jornada de trabajo y hacer un push cuando acabamos nuestra jornada.

- pull --> nos traemos el repositorio tal y como está en este momento.
```
git pull
``` 
- add --> añadir ficheros al repositorio.
```
git add "fichero"
```
- commit --> ponemos un comentario para acordarnos de los cambios realizados.
```
git commit -m "comentario con los cambios realizados"
```
- push --> aplicamos los cambios al repositorio remoto.
```
git push
```


# dia 5 - el branch meta

- dedica el día a completar si te faltara alguna de las tareas de los díaas anteriores.

- este repositorio tiene una rama dedicada a documentar y ampliar las tecnologías que se usan en él, explóralo en: https://github.com/jescuderobus/gitParaPoetas/tree/meta 








