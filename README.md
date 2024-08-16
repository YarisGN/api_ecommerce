# api_nodejs

La API proporciona una interfaz robusta y flexible para interactuar con la base de datos, que contiene información sobre libros. Cada libro tiene un identificador (id), título, autor y edición.

## Captura de Pantalla

![Alt text](captura_de_pantalla.png)

### Obtener
GET http://localhost:9000/api HTTP/1.1

### Mandar-agregar
POST http://localhost:9000/api HTTP/1.1
Content-Type: application/json

{
    "titulo": "La relatividad del tiempo",
    "autor": "Einstein",
    "edicion": 3
}

### Eliminar con ID
DELETE http://localhost:9000/api/6 HTTP/1.1

### Actualizar con ID
PUT http://localhost:9000/api/4 HTTP/1.1
Content-Type: application/json

{
    "titulo": "La relatividad del tiempo",
    "autor": "Einstein",
    "edicion": 14
}






# Instalación
## Instalación local de paquetes
Solo se recomienda instalar paquetes localmente para cada proyecto individual.

Para instalar un paquete localmente, navega hasta el directorio de la aplicación de tu sitio (no el directorio /public). 

### El comando para instalar un paquete es:

`npm install`

## Actualizar paquetes
### Primero, verifica qué paquetes deben actualizarse:

`npm outdated`


### Puedes actualizar un solo paquete con:

`npm update -S <package_name>`

    
### Puedes actualizar todos los paquetes locales con:

`npm update -S`



## Actualizar paquetes globales
### Primero, verifica qué paquetes deben actualizarse:

`npm outdated -g --depth=0`


### Puedes actualizar un solo paquete con:

`npm outdated -g <package_name>`

  
### Puedes actualizar todos los paquetes globales con:

`npm update -g`


## Correr el proyecto
`npm start`


## Base de datos 
`library`


## MIT

![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)


## Licencia

Este proyecto está bajo la [Licencia MIT](LICENSE)