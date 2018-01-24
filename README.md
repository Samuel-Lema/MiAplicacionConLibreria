# Mi Aplicacion Con Libreria

Aplicación sencilla con una librería que se puede actualizar utilizando la herramienta de 'submodule' de git.

## Documentación

* [Libro Git](https://git-scm.com/book/en/v2/Git-Tools-Submodules) - Git tools Submodule

## Comandos claves

Una vez creado el proyecto se añade un directorio para incluir las fuentes de la librera como submodulo.

```
$ git submodule add https://github.com/damiannogueiras/MiLibreria.git Lib 
```

Este directorio (Lib) lo incluímos en los directorios fuentes del proyecto, en nuestro caso en Netbeans.

(`Project Properties -> Sources -> Add Folder`)

Para actualizar la libreria:

```
$ git submodule update --remote Lib
```

## Para profundizar

[SubTree](https://www.atlassian.com/git/articles/alternatives-to-git-submodule-git-subtree)
