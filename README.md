# Cartas QR por Zona

## Tabla de Contenido

- [Cartas QR por Zona](#cartas-qr-por-zona)
  - [Tabla de Contenido](#tabla-de-contenido)
  - [Idea y Concepto](#idea-y-concepto)
  - [Especificación Tecnica](#especificación-tecnica)
  - [Ordenamiento de Archivo](#ordenamiento-de-archivo)
  - [Variables](#variables)
  - [Utilización de la API](#utilización-de-la-api)

---
## Idea y Concepto
Clonar Repositorio:
~~~
git clone https://github.com/Tiago-Pujia/QR-por-zona
~~~

El proyecto trata sobre un almacen de cartas QR que se van obteniendo de diversos negocios (restaurantes, cafeterias, etc...), donde se puede filtrar por categoria o zona, y obtener una rapides para su obtension a los enlaces

---
## Especificación Tecnica
  
**Softwares necesarios:**
- MySQL (database)
- PHP (api)
- JSON (formato en red)
- JavaScript (web)
- CSS (web)
- HTML (web)
- Bootstrap (CSS FrameWork)

La Base de Datos contiene las tablas:

> **tbl_cartas**
>  - ID_CARTA
>  - ID_ZONA
>  - ID_CATEGORIA
>  - URL
>  - DESCRIPCION
>  - FECHA_ELIMINADO

> **tbl_categoria**
> - ID_CATEGORIA
> - CATEGORIA

> **tbl_zonas**
> - ID_ZONA
> - ZONA

---
## Ordenamiento de Archivo
La relación de archivos de la página web incluye:
~~~
index.html 	-> Archivo de inicio y punto de acceso principal.
script.js	-> Lógica de programación implementada en JavaScript.
~~~

La base de datos y la API se administran con:
~~~
database.sql    -> Estrucutra de la base de datos
API/index.php   -> Comunicación cliente<->BD
API/crud.php    -> Clase para la administracion sencilla entre la API y la base de datos
~~~
---
## Variables
Estas son variables que deben de cambiarse en los siguientes archivos, segun la adaptación del proyecto a un area:

---
## Utilización de la API
Para conectarse a la API utilizamos el archivo "API.php" donde especificamos el metodo de la peticion y el tipo de acción.

> ### Tipo GET
 
> ### Tipo POST

> ### Tipo PUT

> ### Tipo DELETE