# Uso De Mkdocs (Windows)

## Python  
antes que nada debemos tener python instalado, en caso de que no lo tengamos deberemos ir a la pagina de [python](https://www.python.org/) y descargar e instalarlo.  

Una vez tengamos instalado python crearemos un entorno virtual donde alojaremos la pagina web de mkdocs. Ejecutaremos el terminal como administrador y ejecutaremos el siguiente comando `python -m venv mkdocsenv`.  
Cada vez que queramos activar este entorno deberemos ejecutar 
`mkdocsenv\Scripts\activate` desde la carpeta en la que hayamos creado el entorno.

## Creamos el Proyecto
Situandonos en la carpeta en la que queramos tener el proyecto,
lo crearemos con el comando `mkdocs new Nombre_del_proyecto` se nos creara un directorio con un archivo .yml y una carpeta que contendra los archivos .md. 

## Visualizacion de la Pagina Web
Para esto deberemos instalar mkdocs en la carpeta del del proyecto con `pip install mkdocs` asi habremos creado una libreria de python que usaremos para nuestra pagina web.
Para iniciar el servicio de la pagina usaremos `mkdoc serve` 
segido de esto debera mosrtar varios mensajes informativos, el ultimo de ellos el la direccion de nuestra pagina.