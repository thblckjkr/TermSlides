## **Git 101:** Respaldos y versiones de tu código sin morir en el intento

<!-- &#60;Teo González Calzada/&#62; -->
`<Teo González Calzada/>`



## Historia

Todos hemos tenido un proyecto, tarea, exámen o algo que organizamos de una forma parecida a esta:

```bash
- proyecto
|- proyecto
 |- sumar.py
 |- sumar_viejo.py
 |- sumar_v2.py
|-  proyecto_final
 |- sumar_v3.py
|- proyecto_final_final_ahorasi
 |- sumar_final.py
```

Note: Historia, el capítulo del punto de inflexión de SNK, en el que la serie toma un turno oscuro. La historia, siempre es importante.


### Problemas

- Es complicado de saber *cuando* se hizo un cambio
- No se tiene un *orden*
- Se *confunde* el primer por el último cambio con facilidad


### Sistemas de control de versiones

- Git
- Mercurial
- Subversion
- Team Foundation Version Control*

*[Microsoft ya no recomienda su uso](https://docs.microsoft.com/en-us/azure/devops/repos/tfvc/comparison-git-tfvc?view=azure-devops)



## Cosas que saber antes de empezar

**Git** es una herramienta

Git**hub** es un espacio para almacenar tu código

Un **repositorio** es un folder


## Instalación

En *linux*, generalmente viene preinstalado.

En *MacOS*, sólo es necesario ejecutar el comando `git --version`.

En *Windows*, se instala desde [git-scm.com](https://git-scm.com/download/win)


### Terminales

![terminal de windows](git101/assets/cmd.jpg)



## Primeros pasos

Primero, necesitamos abrir una terminal


## Configuración

```sh
$ git config --global user.name "Juan Pérez"
$ git config --global user.email "juanperez@gmail.com"
```

Note: Esto no ofrece ningún tipo de seguridad, sólo es para identificar



## Inicializar un **repositorio**

```sh
$ git init
```


## O **clonar** un repositorio existente

![terminal de windows](git101/assets/git-clone.png)


```sh
$ git clone https://github.com/rstudio/revealjs.git
```


## Comprobar el **estado**

```sh
$ git status
```



## Agregar tus **cambios**

Se puede hacer en lo general

```sh
$ git add *
```


 Y en lo particular

```sh
$ git add archivo
```


## Realizar un commit

```sh
$ git commit -m "Se agregó un archivo"
```

Note: Si les interesa un estándar para el nombre de commits, pueden utilizar *conventionalcommits*

## Subir tus cambios

```sh
$ git push
```


## Bajar nuevos cambios

```sh
$ git pull
```

