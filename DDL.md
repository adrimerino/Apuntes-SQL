# Apuntes SQL-DDL
> Estos apuntes han sido preparados recopilando información en clase y por mi cuenta para facilitarme el entendimiento de las distintas funciones de SQL de cara al examen.
## Índice
- [Qué es el sublenguaje DDL](#QUÉ-ES-EL-SUBLENGUAJE-DDL)
- [Tipos de datos](#TIPOS-DE-DATOS)

## QUÉ ES EL SUBLENGUAJE DDL
EL ```DDL``` (Data Definition Language) permite dentro de un sistema gestor de base de datos definir las estructuras de la base de datos como también los procedimientos de consulta de esos datos.
Las tres principales sentencias dentro de este sublenguaje son:
- ```CREATE```
- ```ALTER```
- ```DROP```

## TIPOS DE DATOS
Dentro del DDL, hay muchísima variedad de datos, pero varias según el gestor que estemos utilizando. A Continuación se mostrará una tabla de una selección de los que vamos a usar.
| Dato          | Función                                                                                  |
|---------------|------------------------------------------------------------------------------------------|
| **texto**     |                                                                                          |
| CHAR(n)       | de longitud fija                                                                         |
| VARCHAR(n)    | de longitud variable                                                                     |
| TEXT          | lonixutde variable e ilimitada                                                           |
| **numeros**   |                                                                                          |
| INTEGER       | número entero                                                                            |
| DECIMAL(n,m)  | número decimal con precisión (n=entero, m=decimal)                                       |
| REAL          | número aproximado                                                                        |
| **fecha**     |                                                                                          |
| DATE          | 'aaaa-mm-dd', formato de sólo de fecha                                                   |
| TIME          | 'hh:mm:ss', formato solo de hora                                                         |
| TIMESTAMP     | 'aaaa-mm-dd hh:mm:ss', combinación de las dos anteriores                                 |
| **otros**     |                                                                                          |
| BOOLEAN       | TRUE[1] o FALSE[0]                                                                       |
| MONEY         | Uso para moneda de hasta 4 cifras decimales                                              |
| UUID          | identificador universal único de 128 bits                                                |
| JSON          | para archivos JSON (JavaScript Object Notation)                                          |