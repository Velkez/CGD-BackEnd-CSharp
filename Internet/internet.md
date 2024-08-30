# Internet.
A rasgos generales, Internet es un conjunto extenso de redes, los cuales son un grupo de computadoras interconectadas entre si a nivel mundial, las cuales se comparten información por medio de protocolos y servicios. 

Los protocolos son elementos que permiten la unión de la red, y consigo, la transmisión de información. Para este fin, estos fragmentan, unen y traducen todos los mensajes que son enviados por Intenet. Por otro lado, los servicios son aquellos que permiten a toda persona el el acceso a la información, ejemplos cotidianos pueden ser el correo electronico, los chats como Whatsapp, o incluso, las redes sociales que todos conocemos.

## ¿Cómo funciona Internet?
En el parrafo anterior se describio mas o menos como es el funcionamiento de internet, pero para profundizar esta pregunta, tenemos que ver dos conceptos, los paquetes, y el ya antes mencionado, protocolo.

### Paquetes.
Los paquetes son pequeños fragmentos de mensajes mas grandes, estos fragmenos contienen datos e información de estos datos, los cuales son conocidos como "_cabecera_", y este va al principio del paquete para que la maquina que lo recibe pueda entender el uso de ese paquete, practicamente como una especie de manual de instrucciones.

El envio de datos seria mas o menos de la siguiente forma. Los datos se dividen en paquetes, luego son traducidos en bits, se enrutan a su destino por distintos dispositivos de red, [enrutadores](https://www.cloudflare.com/learning/network-layer/what-is-a-router/) y [conmutadores](https://www.cloudflare.com/learning/network-layer/what-is-a-network-switch/). Al llegar los paquetes a su destino, el dispositivo que los recibio procede a ensamblar los paquetes en orden y luego usa o muestra el dato recibido.

Un dato interesante respecto a esto, es que los paquetes se envian por internet por medio de una tecnica llamada conmutación de paquetes, en palabras simples, es lo que se menciono antes sobre la fragmentación de datos en paquetes y el procedimiento posterior. Los enrutadores  conmutadores intermediarios pueden procesar los paquetes independientemente unos de otros, sin tener en cuenta su origen o destino, se hizo de esta forma para que ninguna conexión dominara en la red, pues internet es libre para todos. Si este procedimiento no se hiciera, probablemente los datos tardarian mucho mas en llegar, y aparte, se necesitara mucho mas cableado, solo dos personas podrian utilizar internet a la vez, lo cual seria tedioso.

### Protocolo.
Ya se hablo sobre los protocolos antes, pero en esta pequeña sección vamos mencionar un poco mas sobre ellos. 

Los protocolos son como reglas o estandares, una de las dificultades de los creadores de Internet fue que ordenadores con distintos hardware y software pudiesen conectarse, y los protocolos solucionaron este problema. Estos estandarizan determinadas acciones y dan formato a los datos para que dos o mas dispositivos se puedan comunicar efectivamente entre si.


Para este punto me base en el articulo de CloudFlare llamado _[¿Cómo funciona internet?](https://www.cloudflare.com/es-es/learning/network-layer/how-does-the-internet-work/#:~:text=Los%20ordenadores%20se%20conectan%20entre%20s%C3%AD%20y%20a%20Internet%20mediante%20cables,luego%20interpreta%20el%20ordenador%20receptor.)_ Recomiendo su lectura, explica de forma mas profunda sobre lo hablado en esta sección.

## ¿Qué es HTTP?
Estes es un protocolo de transferencia de hipertexto, el cual se utiliza para cargar las paginas web mediante enlaces de hipertexto. Este es un protocolo de capa de aplicación diseñado para comprartir información entre los dispositivos conectados en la red. HTTP se ejecuta sobre otras capas del conjunto de protocolos orientados a la red. Este practicamente funciona cuando una maquina cliente solicita datos de un servidor, y este este responde enviando el dato solicitado.

### Solicitud HTTP.
esta es la manera en la que una herramienta de comunicación a internet, como los navegadores web, piden información para el cargue de paginas web.

Estos llevan una serie de datos codificados los cuales tiene información de la solicitud. Usualmente, una solusitud http contiene los siguiente datos:
  - Tipo de versión HTTP: existen varias como: 
    - HTTP/0.9 (protocolo de una linea) .
    - HTTP/1.0 (desarrollo de flexibilidad y expación).
    - HTTP/1.1 (protocolo estandar).
    - HTTP/2 (protocolo con mayor rendimiento).
  - Una URL: dirección que es dada a un recurso unico en la web.
  - Un metodo HTTP: es la acción que la solicitud HTTP espera del servidor consultado.
  - Encabezados de la solicitud HTTP: contienen información de texto almacenada en pares ***clave-valor***. Estos contienen información basica que tipo de navegador usa el cliente y qué datos solicita.
  - Cuerpo de solicitud HTTP: este contiene toda la información que se envia al servidor web, como correo, contraseña u otro dato enviado por medio de un formulario.

### Respuesta HTTP.
Es lo que el cliente web (como navegadores, por ejemplo) reciben tras su solicitud HTTP en al servidor, estas respuestas contienen la información basada en lo que se pidio anteriormente.

Una respuesta HTTP comúnmente contiene lo siguiente:
  - Codigo de estado HTTP: son codigos de 3 digitos que se usan con mayor frecuenciapara indicar si una solicitud HTTP fue completada con exito o hubo algun problema. Estos se dividen en 5 bloques: 
    - 100... (informativo).
    - 200... (Exito).
    - 300... (Redirección).
    - 400... Errores de cliente.
    - 500... Error de servidor.
  - Encabezados de respuesta HTTP: esta es informacion importante, como idioma, formato de los datos que se envian en el cuerpo de la respuesta.
  - Cuerpo de respuesta HTTP: Son los datos HTML que un navegador web convertirá en una pagina web, practicamente.

Al igual que el punto anterior, me base en un articulo publicado por la empresa CloudFlare llamado _[¿Qué es HTTP?](https://www.cloudflare.com/es-es/learning/ddos/glossary/hypertext-transfer-protocol-http/)_ Tambien recomiendo su lectura, incluso podran ver que varios fragmentos de este texto son de esa pagina web, pero es porque no me supe explicar con mis palabras :trollface:. Aparte explica de forma mas detallada todo lo que quise decir acá.
