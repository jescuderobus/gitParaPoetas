### Doble autenticación en PC

Este tutorial lo vamos a realizar para el sistema operativo Windows usando una de las aplicaciones recomendadas por el SOS para el PC.  

#### Paso 1

Nos descargamos [_OPT Manager_](https://apps.microsoft.com/store/detail/otp-manager/9NBLGGH6HNGN?hl=es-es&gl=es) desde Microsoft Store.

FOTO 1

Le damos a "Obtener en la aplicacion Microsoft Store" y pulsamos en "Abrir Microsoft Store"

FOTO 2

#### Paso 2

Ahora activamos el servicio en [2fa.us.es](https://2fa.us.es)

Primero nos logueamos y le damos a "Activar doble factor". En el primer paso, descargar una aplicacion, le damos a "Hecho"

FOTO 3

El paso 2 es el mas importante, le damos a "Mostrar" y seguidamente a "Mostrar los párametros de configuración"

FOTO 4,5,6

Abrimos la aplicación "OPT Manager" 
FOTO 7

Pulsamos en "Agregar manualmente" y nos aparece la siguiente pantella

FOTO 8

Ahora vamos añadiendo los parámetros de configuración necesarios para poder activar la doble autenticacion.

En _Etiqueta_ ponemos nuestro correo corporativo.
En _Secreto_ tenemos que pegar la cadena larga de caracteres que nos aparece en la opcion "secreto o clave" en los parámetros de configuración.
En _Editor_ ponemos TOTP y le damos a guardar

FOTO 9, 10

En la aplicacion de la universidad le damos a "Hecho" al paso 2 y en el paso 3 nos pide el código que nos aparece en la aplicacion "OTP Manager", lo introducimos y le damos a "Activar"

Ahora si intentamos entrar en cualquiera de las plataformas que nos pide la doble autenticación (p.ej. VPNCubo), al poner el código de 6 dígitos que nos aparece en la aplicacion "OTP Manager" podremos entrar. Hay que tener en cuenta que este número cambia cada 30 segundos por lo que hay que estar un poco rápido al realizar este paso.





