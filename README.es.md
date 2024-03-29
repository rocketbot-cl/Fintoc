# Fintoc
  
Módulo para conectarse a Fintoc  

*Read this in other languages: [English](README.md), [Portugues](README.pr.md), [Español](README.es.md).*

## Como instalar este módulo
  
__Descarga__ e __instala__ el contenido en la carpeta 'modules' en la ruta de Rocketbot.  


## Como usar este modulo

1. Se debe obtener previamente el link_token de los Links que hayan conectado con su cuenta de Fintoc. Las consultas sobre los links que se realicen desde el módulo siempre devolverán el link_token con valor Null, por lo que no se puede obtener el link_token de un link que ya se haya conectado. Estos link_token sólamente se pueden obtener una vez, si se pierde el link_token, se debe volver a conectar el link con su cuenta de Fintoc. 
2. Para poder conectarse, deberán consultar su Secret key desde la sección de API Keys de su cuenta de Fintoc.


## Overview


1. Login Fintoc  
Conecta con Fintoc utilizando tu Secret Key

2. Listar Links  
Enumera todos los Links que has creado. Los Links listados se devuelven ordenados, siendo el último Link creado el primero.

3. Obtener Link  
Obtiene los detalles de un Link, incluyendo las cuentas asociadas y sus saldos.

4. Listar Facturas  
Listar todas las facturas

5. Listar Cuentas  
Lista todas las cuentas asociadas a un Link

6. Obtener Cuenta  
Obtener una cuenta por su ID.

7. Listar Movimientos  
Obtiene una lista de movimientos de una cuenta dada.

8. Obtener Movimiento  
Obtiene un movimiento por su ID y el ID de la cuenta a la que pertenece.  




----
### OS

- windows
- mac
- linux
- docker

### Dependencies
- [**python-requests**](https://pypi.org/project/python-requests/)
### License
  
![MIT](https://camo.githubusercontent.com/107590fac8cbd65071396bb4d04040f76cde5bde/687474703a2f2f696d672e736869656c64732e696f2f3a6c6963656e73652d6d69742d626c75652e7376673f7374796c653d666c61742d737175617265)  
[MIT](http://opensource.org/licenses/mit-license.ph)