**Repaso trabajo con markdown directamente en visual studio code (vs)**  NO BORRAR
En vs pincho y abro el fichero de texto ¨Memoria.md" y abajo a la dcha observo que lo trata como un document text, por tanto tengo que cambiarlo a formato Markdown y ahora observo que en el memú del fichero ha cambiado la marca y si lo pincho me sale una nueva opción de previsualizar. Por lo que puedo dividir la pantalla y colocar en una parte el fichero raw y en otra el previsualizado.
Después para ayudarme escribo los comandos y pulso ctrl+space y se me autocompleta.
Heading
bold
italic
list
link
image
Forma más rapída de insertar una imagen desde tu mismo repositorio https://code.visualstudio.com/assets/docs/languages/Markdown/drop-link.gif
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



Los errores que daba el sensordht11 y la placa eran que al conectar el pin data desde el principio, no ejecutaba el codigo, así que habia ue descoectarlo hasta quie se subía el código y ya se podía enchufar de nuevo.

Con el sensor y la placa finalmente funcionando, el siguiente paso era encontrar un lugar para guardar la información. Tuve que usar SQL y PHP para crear una tabla de datos en una base de datos creada en 000webhost.com. No tenía ni idea de cómo funcionaba SQL, pero encontré algunos tutoriales sencillos que me ayudaron a entenderlo un poco.

Después de mucha prueba y error, conseguí que la placa guardara las lecturas de humedad en la base de datos. Pero necesitaba un código que no sabía hacer para enviar esas lecturas a la base de datos. Investigué un poco más y aprendí sobre códigos de "post". Parecen raros de ver pero resulta que es como darle un papelito a la base de datos y decirle que lo guarde.
Creé una tabla en html y php para organizar las medidas y tenerlas guardadas, n hubo mucho problema en hacer esto.

Con el código "post" funcionando y la tabla hecha, tuve que subir todo lo que había hecho a GitHub. Al principio, GitHub me pareció un sitio rro de subir archivos, pero con paciencia, entendí cómo subir mis cosas allí. Ahora, cualquiera puede ver lo que hice.
# INTRODUCCIÓN
La meteorología es la ciencia que estudia el estado del tiempo, el clima y las condiciones atmosféricas de una determinada zona del planeta, la cual requiere conocer de manera simultánea un conjunto de parámetros meteorológicos como la temperatura, la presión, la humedad, el viento, la radiación solar, etc… para poder realizar los pronósticos o evaluar las condiciones climáticas que pudiesen afectar una determinada actividad en una zona. Es por ello que surge la necesidad de una instalación física como son las Estaciones Meteorológicas, las cuales son capaces de medir y registrar todas las variables meteorológicas mencionadas en tiempo real, para poder realizar dichos estudios y pronósticos, a través de un conjunto de instrumentos y sensores instalados de manera estratégica en su estructura. Las Estaciones meteorológicas cuentan con una diversidad de tipologías en su construcción, las cuales permiten realizar mediciones específicas de ciertas variables meteorológicas, que pudiesen afectar ciertas actividades en una determinada zona, como por ejemplo: la agricultura, la hidrología, la generación eléctrica en plantas solares, la aeronáutica, los riesgos climáticos en infraestructuras civiles entre otras. Las estaciones meteorológicas hoy en día cuentan con modernos sistemas automatizados con poca intervención humana, que permiten la medición, el registro y la transmisión en tiempo real y continua en cualquier parte del planeta de todas las variables meteorológicas de la zona, incluso el intercambio global de información entre estaciones, logrando así la precisión en los pronósticos y los estudios climáticos.
# OBJETIVOS DEL PROYECTO

# PASOS A SEGUIR

# MATERIALES NECESARIOS

### SENSOR TRA Y HUMEDAD
El sensor utilizado fue DS18B20, se trata de un sensor de temperatura en formato capsula, gracias a lo cual nos va a permitir medir la temperatura en ambientes muy húmedos e incluso de líquidos, al tratarse de una estación meteorológica buscamos medir la temperatura ambiente, por lo que gracias a su diseño encapsulado no tendremos que preocuparnos de proteger el sensor de la lluvia.
En cuanto a sus características técnicas, el DS18B20 cuenta con un rango de medición de entre -55 ºC a 125 ºC, además, proporciona lecturas de la temperatura de entre 9 y 12 bits, que podemos configurar, sobre una interfaz "1-Wire", con sólo un cable de señal (y tierra) estando conectado a un microprocesador central, y podemos utilizarlo con un voltaje de entre 3 y 5.5V.
A la hora de utilizar el sensor no nos encontramos con grandes problemas mas allá de un pequeño fallo en el código que hacia que el sensor nos diera una lectura errónea.
### SENSOR PRESIÓN (BMP280)
### SENSOR RADIACIÓN SOLAR
### PLUVIÓMETRO
### RESTO DE COMPONENTES



# CARACTERÍSTICAS
(De los sensores.Medición analógica, digital,protocolo de comunicación, Tablas de características, sensibilidad, precisión)

# MONTAJE Y ESQUEMAS DEL CONJUNTO
1. ESQUEMAS


2. CÓDIGO ARDUINO



3. CÓDIGO BASE DE DATOS





# INTERPRETACIÓN DE DATOS
NIVEL DE CLIMATIZACIÓN:
Una humedad igual o inferior al 40%
Una humedad igual o superior al 70%
Una humedad superior al 40% pero inferior al 70%; al mismo tiempo la temperatura actual es superior a 20°C (68°F) pero inferior a 27°C (80.6°F).

AVISO DE HELADAS
Si el aviso de heladas se encuentra activo y la temperatura exterior se
encuentra entre -1,0 y +2,9 °C (+30,2 y 37,3 °F) suena una alarma durante
unos 5 segundos y parpadea el símbolo

LLUVIA


# PROBLEMAS ENCONTRADOS
