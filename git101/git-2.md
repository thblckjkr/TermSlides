
## Gitignore

Sirve para ignorar archivos de forma automática.

Se recomienda NO subir archivos de configuración o ambiente que contengan passwords.


No se suben archivos *pesados* a git, git es un sistema para control de *CÓDIGO*.

Notes: Casi todos los repositorios tienen un límite duro de 100 MB como máximo.


### Administradores de paquetes

Aunque git es un sistema de control de código, se recomienda sólo subir el de tu proyecto y no las librerías de las que depende.


Ejemplo:

Para `NodeJS` utilizar `npm` y no subir el folder `node_modules`

Para `PHP` utilizar `composer` y no subir el folder `vendor`

Para `Python` utilizar `pip`

Note: Esto aplica principalmente para librerías públicas que están bien distribuidas y documentadas


## Ejemplo

```bash
# .gitignore

*.exe # Ignora todos los archivos EXE

node_modules # Ignora la carpeta node_modules
.env # Ignora un archivo llamado .env
```
