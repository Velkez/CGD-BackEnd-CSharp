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

Para este punto me base en el articulo de CloudFlare llamado [¿Cómo funciona internet?](https://www.cloudflare.com/es-es/learning/network-layer/how-does-the-internet-work/#:~:text=Los%20ordenadores%20se%20conectan%20entre%20s%C3%AD%20y%20a%20Internet%20mediante%20cables,luego%20interpreta%20el%20ordenador%20receptor.). Recomiendo su lectura, explica de forma mas profunda sobre lo hablado en esta sección.