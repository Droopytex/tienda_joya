# tienda_joya
Para entrega de desafío 5 de unidad Backend con Node y Express

## Descripción
La tienda de joyas My Precious Spa necesita cambiar su aplicación de escritorio por una moderna y dinámica. Para realizar esta tarea, contactó a un desarrollador Full Stack Developer que desarrolle la API REST de una aplicación cliente para satisfacer las necesidades puntuales de sus usuarios de una forma eficiente, mantenible y eficaz.
Deberás crear una API REST que permita:
1. Límite de recursos
2. Filtro de recursos por campos
3. Paginación
4. Ordenamiento
5. Estructura de datos HATEOAS

## Requerimientos
👌 1. Crear una ruta GET /joyas que:
    a. Devuelva la estructura HATEOAS de todas las joyas almacenadas en la base
       de datos. 
    b. Reciba en la query string los parámetros (2 puntos):
        i. limits: Limita la cantidad de joyas a devolver por página
        ii. page: Define la página
        iii. order_by: Ordena las joyas según el valor de este parámetro, ejemplo: stock_ASC


👌 2. Crear una ruta GET /joyas/filtros que reciba los siguientes parámetros en la query string: (3.5 puntos)
a. precio_max: Filtrar las joyas con un precio mayor al valor recibido
b. precio_min: Filtrar las joyas con un precio menor al valor recibido.
c. categoria: Filtrar las joyas por la categoría
d. metal: Filtrar las joyas por la categoría

👌 3. Implementar middlewares para generar informes o reportes de alguna actividad o evento específico que ocurra en cada una de las rutas.

👌 4. Usar try catch para capturar los posibles errores durante una consulta y la lógica de cada ruta creada.

👌 5. Usar las consultas parametrizadas para evitar el SQL Injection en la consulta a la base de datos relacionada con la ruta GET /joyas/filtros


## Registro
![Captura de Pantalla 2024-09-29 a la(s) 16 59 34](https://github.com/user-attachments/assets/56778861-bd71-482f-a228-8d01cc2ae2a1)

Probando rutas GET por thunderClient
![Captura de Pantalla 2024-09-29 a la(s) 17 40 01](https://github.com/user-attachments/assets/2eb7eb3e-bbe7-4331-9bd5-a5996089ce5f)

![Captura de Pantalla 2024-09-29 a la(s) 17 40 12](https://github.com/user-attachments/assets/acb60799-2586-498d-9947-20423b3abc14)

![Captura de Pantalla 2024-09-29 a la(s) 17 31 20](https://github.com/user-attachments/assets/c5b166df-d84e-474a-a388-233ebe28dfe0)

![Captura de Pantalla 2024-09-29 a la(s) 17 13 40](https://github.com/user-attachments/assets/1650fd7b-a9a6-4e7f-a732-00e7d3763b5c)


## Construido con 🛠️

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - El lenguaje utilizado
- [Node](https://nodejs.org/en)- Node.js
- [Express](https://expressjs.com/es/)- Express
- [Nodemon](https://www.npmjs.com/package/nodemon)- Nodemon
- [Pg](https://www.npmjs.com/package/pg)- PG
- [Pg-format](https://www.npmjs.com/package/pg-format) - Pg - format
- [CORS](https://developer.mozilla.org/es/docs/Web/HTTP/CORS)- CORS
<hr>
**Andres Velásquez** ⚡  - [Andres Velásquez](https://github.com/Droopytex)
