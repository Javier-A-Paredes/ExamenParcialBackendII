# ExamenParcialBackendII

## Instrucciones para verificar:

Dentro del reino deberán haber 2 clientes, uno para el gateway con id gateway-client y otro para el microservicio de bills con id bills-client.

Se deberá crear un usuario, que para propositos de ejemplos se uso uno llamado Javier.

Luego se crearan roles de reino y cliente que se vincularan entre ellos y se le asignaran a este usuario. Estos se llamaron ***app_usuario*** y ***usuario*** respectivamente

Este usuario seria el que tiene acceso al endpoint *bills/all*

#### NOTA: 
> En la configuración del gateway se quitó la opción que agregaba las partes de **api/** y **v1/**.
> De esta forma la peticion se deberia hacer al **localhost:9090/bills/all**
