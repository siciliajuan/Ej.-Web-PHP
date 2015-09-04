------------------------------------------------------------------------------------
-------------------         PRINCIPIOS DEL EJERCICIO         -----------------------
------------------------------------------------------------------------------------ 


Ejercicio para aprender a desarrollar un proyecto web con el siguiente stack tecnológico:
-HTML5 -> Web semántica, fluida y responsive.
-CSS3 -> principales efectos CSS3 usando SASS.
-jQuery 2.x -> Uso de Cookies
-AJAX
-PHP -> gestion se sesiones
-PHPunit -> teses
-API REST en php
-MySQL
-Twig -> gestion de plantillas
-Symphony -> el desarrollo será MVC.

El desarrollo se realizará usando IntelliJ y Sublime text 3 como IDE`s y GIT como gestor de versiones.

Todo esto se realizará apoyados en la metodología TDD y respetando los fundamentos SOLID.
-TDD se aplicara usando como block de notas de meses el archivo libreta.txt

Arbol de carpetas del proyecto:

[project] (carpeta que contiene todo el proyecto)
    |
    |__[pages] (contienen las distintas páginas del proyecto)
    |
    |__[css] (contiene archivos hojas del estilos)
    |
    |__[js] (contiene archivos javascript)
    |
    |__[img] (contiene las imágenes usadas en el proyecto)
    |
    |__[plugin] (contiene plugins de terceros)
    |
    |__[scr] (contiene el código donde se desarrolla la lógica en servidor)
         |
         |__[manager] (archivos con la lógica del negocio)
         |
         |__[controller] (controlador entre la vista y la logica de negocio)
         |
         |__[DAO] (archivos con la responsabilidad de tratar directamente con BBDD)
         |
         |__[properties] (Archivos de configuración externa)


Durante el desarrollo de código todas las configuraciones que deban ser exclusivas del entorno donde se desarrolle el proyecto, se incluirán en la carpeta properties dentro de la carpeta project


------------------------------------------------------------------------------------
-------------------           EJERCICIO A DESARROLLAR        -----------------------
------------------------------------------------------------------------------------ 

La idea es desarrollar una web con una home informativa que muestra entradas de un blog y un apartado apartado donde loguearte en el sistema.
En la home habrán varios elementos que se mostrarán de una manera u otra según las visitas que el usuario haya realizado.
Una vez loqueado se mostrará un apartado en la misma página donde se podrá introducir, editar o eliminar entradas del blog.

------------------------------------------------------------------------------------
-------------------             HISTORIAS DE USUARIO         -----------------------
------------------------------------------------------------------------------------ 

En este ejercicio SCRUM no es un objetivo, si bien hago un guiño con la definición de historias, esta deifico será liviana.  