# Detector-de-personas-y-Telegram
Con un sensor PIR HCSR501 podemos detectar movimiento y enviar una notificacion a Telegram
Crea una alarma que te notifique en Telegram cuando alguien es detectado sin permiso en tu propiedad.
Link del tutorial completo: 

Con esta tarjeta puedes conectar un sensor PIR HCSR501 al microcontrolador ESP 32 C3 (yo utilizo la versión Supermini) y así poder enviar una notificación a un grupo de Telegram cuando se detecte movimiento.
Te propongo utilizar este sistema para adaptarlo a tu casa u oficina pues así sera muy fácil saber aunque estés lejos cuando algun intruso esta en tu propiedad sin autorización y así poder tomar tus precauciones.
Aquí encuentras todo lo que necesitas para llevar a cabo la practica en protoboard o en circuito hecho en PCB.
Para la creación del código me apoye de la AI (DeepSeek), y en el tutorial te muestro como hacer la vinculación paso a paso con Telegram para que tengas las notificaciones sin falla.

Materiales:
1 Esp 32 C3
1 Sensor HCSR501
Jumpers

Materiales circuito PCB:
1 Esp32 C3
2 Borneras
1 Resistencias THT
4 Pines hembra
1 Porta pilas AA
1 Regulador voltaje AMS1117
1 Switch cola raton SMD

Promp DeepSeek:
crea un programa en ide arduino en donde utilizare el esp32 c3 que tiene conectado un sensor pir a la entrada GPIO20, y cuando el sensor detecte movimiento se tendra que encender un led que trae incluido el esp en el GPIO8 este led encendera cuando se detecte movimiento y permanecera encendido por 2 segundos para que posteriormente despues de cada deteccion espere 10 segundos antes de volver a detectar, y tambien hara exactamente lo mismo que hace el led pero enviando una sola notificacion a un grupo en telegram, utilizando las librerias WiFi.h

HTTPClient.h WiFiClientSecure.h, el SSID es ......, el password es ......., el tokenBot .......... el ChatID -100.......



NOTA!

Sustituye con tus datos en el programa o en el promp
SSID
Password
Token Bot
Chat ID

Link para generar el ID del chat

https://api.telegram.org/botTU_TOKEN_AQUI/getUpdates
