# PracticaApiRestExpressMongo

Esta práctica responde a la creación de una API Rest con Express, donde se elabora un CRUD, guardando la información en una Base de datos MongoDB, utilizando su driver nativo.
El esqueleto de la aplicación, se ha generado con "express-generator".

Siguiendo las indicaciones de dicha práctica, se han realizado las validaciones pertinentes, usando "express-validator", utilizando además estos datos:

"agenda", es nombre de la BD donde queremos insertar los datos. Si no ha creado una base de datos, se crea automáticamente El primer documento se insertaría en la colección(tabla), 
llamada "contacts", pero no es necesario que cree la tabla primero La tabla se crea automáticamente cuando inserta el primer documento en ella. 
Como atributos tiene "name", "surnames", "age", "dni", "birthday", favouriteColour, "sex" y "notes", además del "_id", que se crea automáticamente, y es único.

Lo primero que hay que hacer es ejecutar "npm install", desde el terminal para instalar todas las dependencias. Después, ejecutaremos la aplicación, escribiendo en el Terminal "node ./bin/www".
La base de datos Mongo, tiene que estar también en ejecución

Se han probado todos los endpoints del CRUD con Postman y se han visualizado todos los cambios, mediante la aplicación "MongoDB Compass".

Los archivos utilizados se encuentran en el repositorio: https://github.com/AnaAlvarezA/PracticaApiRestExpressMongo
