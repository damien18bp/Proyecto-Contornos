# Pasos para la creacion de una Wiki

## Pasos Previos

Para el proceso de instalacion de esta tarea primero instale pyhton (marcando el PATH durante la instalación) en mi ordenador y crea una carpeta donde crearia este proyecto.

## Primer paso

Primero procedí a crear la carpeta y activar el entorno virtual y instalar mkDocs

![Primer paso](Imagenes/Primer%20paso.png)
  
## Segundo paso

Inicializamos el proyecto mkdocs creadno los dos archivos importantes y configuramos el tema Material

![Segundo paso](Imagenes/Segundo%20paso.png)
![Segundo paso2](Imagenes/Segundo%20paso2.png)

## Tercer paso

Creamos la estructura de la carpeta docs y editamos el archivo index con los datos que querrramos

![Tercer paso](Imagenes/Tercer%20paso.png)
![Tercer paso2](Imagenes/Terecer%20paso2.png)

## Cuarto paso

Inicializamos el repositorio en github y creamos el archivo .gitignore

![Caurto paso1](Imagenes/Cuarto%20paso.png)
![Caurto paso2](Imagenes/Cuarto%20paso2.png)

## Quinto paso

Creamos el archivo .github/workflows/deploy.yml en donde copiaremos el contenido que aparece en la guia del trabajo

![Quinto paso](Imagenes/Quinto%20paso.png)
![Quinto paso2](Imagenes/Quinto%20paso2.png)

## Sexto paso

Configuramos el github actions y el github pages

Para llegar aqui vamos a Settings - Actions - General - Workflow donde marcamos "Read and Write permision"
![Sexto paso](Imagenes/Sexto%20paso.png)

Configuracion - Pages - Build and deployment y cambiamos la rama a gh-pages
![Sexto paso2](Imagenes/Sexto%20paso2.png)

## Finalizacion

Una vez realizados estoss pasos y pusheado todos los archivos al reppositorio tendremos que comprobar que en el apartado actions todo funciona, en caso de ser asi nuestra pagina acaba de ser creada

![Sexto paso2](Imagenes/Ultimo%20paso.png)

[Pagina de mi trabajo](https://damien18bp.github.io/cd_6_2/)
