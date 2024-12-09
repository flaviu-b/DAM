# Actividad 1
Utilizar un sistema de control de versiones como Git. Este sistema permite gestionar los cambios en el código fuente de manera eficiente y segura, evitando conflictos y permitiendo la recuperación de versiones anteriores.

## Procedimiento diario 

### Clonación del repositorio:
Joan y Miquel clonan el repositorio remoto en su ordenador local. Esto crea una copia local del proyecto.
Creación de ramas:

Cada desarrollador crea una rama nueva para trabajar en su función específica. Esto evita que los cambios de un desarrollador afecten el trabajo del otro.
### Desarrollo local:
Joan y Miquel trabajan en el código fuente localmente, realizando cambios y añadiendo nuevas funciones.
### Commits:
Los desarrolladores realizan commits para guardar los cambios realizados en el código fuente local. Cada commit debe tener un mensaje claro que describa los cambios realizados.
### Push al repositorio remoto:
Los desarrolladores suben sus cambios al repositorio remoto, permitiendo que los demás vean sus progresos.
### Fusionar ramas:
Cuando un desarrollador ha terminado su función, fusiona su rama con la rama principal (o otra rama que se haya acordado). Este proceso combina los cambios de la rama del desarrollador con el código principal.
### Resolución de conflictos:
En caso de que haya conflictos entre las ramas, los desarrolladores deberán resolverlos manualmente, aceptando los cambios de una u otra rama o haciendo modificaciones para combinarlos.
### Revisión del código:
Antes de fusionar la rama, es recomendable que otro desarrollador revise el código para asegurarse de que los cambios son correctos y que no hay errores.
### Repetir el proceso:
Joan y Miquel repiten el proceso para cada nueva función que desarrollen.

# Actividad 2 
este podria ser una estructura

└── proyecto  
    ├── trunk  
    │   ├── fase1  
    │   │   └── src  
    │   │       └── <código fuente de la fase 1>  
    │   ├── fase2  
    │   │   └── src  
    │   │       └── <código fuente de la fase 2>  
    │   └── ...  
    │       └── src  
    │           └── <código fuente de la fase 5>  
    ├── branches  
    │   ├── release-1.0  
    │   │   └── src  
    │   │       └── <código fuente de la versión 1.0>  
    │   ├── release-1.1  
    │   │   └── src  
    │   │       └── <código fuente de la versión 1.1>  
    │   └── ...  
    │       └── src  
    │           └── <código fuente de la versión 1.5>  
    └── tags  
        ├── v1.0  
        │   └── src  
        │       └── <código fuente de la versión 1.0>  
        ├── v1.1  
        │   └── src  
        │       └── <código fuente de la versión 1.1>  
        └── ...  
            └── src  
                └── <código fuente de la versión 1.5>  

# Actividad 3
## RCS
**co (checkout):** Extrae una copia del código fuente del repositorio.  
**ci (checkin):** Guarda los cambios realizados en el código fuente en el repositorio.  
## Subversion
**svn co (checkout):** Extrae una copia del código fuente del repositorio.  
**svn ci (checkin):** Guarda los cambios realizados en el código fuente en el repositorio.  
**svn st (status):** Muestra el estado de los archivos del proyecto, indicando si están modificados, añadidos, eliminados, etc.  
**svn add:** Añade nuevos archivos al control de versiones.  
**svn up (update):** Actualiza la copia de trabajo del repositorio con los cambios realizados por otros desarrolladores.  

Las órdenes co y ci en RCS y Subversion realizan la misma función.  
Sin embargo, existen algunas diferencias:  

**RCS:** La orden co extrae una copia del código fuente en un directorio específico, mientras que la orden ci guarda los cambios en el repositorio.  
**Subversion:** La orden svn co extrae una copia del código fuente en un directorio específico, mientras que la orden svn ci guarda los cambios en el repositorio.

En resumen, la principal diferencia es que Subversion utiliza un comando svn antes de las órdenes co y ci, mientras que RCS las utiliza directamente.