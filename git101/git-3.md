## Ramas

Existe algo llamado **ramas**, las ramas son copias de tu código en la que puedes hacer cambios que no se compartirán con el historial principal.


**Diagrama de ramas**

![Diagrama clásico de ramas](git101/assets/ramas.png)


## Crear una nueva rama

```sh
$ git checkout -b rama
```


## Mezlcas

```sh
$ git merge RAMA_REMOTA
```


## ¿Master? ¿O Main?

La mayor parte de la documentación mencionará la rama **master** como la rama principal.
Desde el 2020 hasta ahora, se cambió a **main**.


En lo personal, prefiero el esquema

`dev -> main`