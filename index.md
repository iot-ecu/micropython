{% include ads.html %}

# Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/micropython{{post.url }}">{{post.title}}</a>
    </li>
  {% endfor %}
</ul>

# Primeros pasos con MicroPython
![MicroPython][MicroPython]
Para quienes se quieren iniciar en este mundo de utilizar microcontroladores para crear proyectos de:
- Electrónica
- IOT (Internet De las Cosas)
- Domótica
- Automatización
- Y muchas aplicaciones más.

Debes entender conceptos fundamentales, que te explicaremos a continuación:
## ¿Qué es un microcontrolador?
Es un circuito lógico que responde y procesa las operaciones lógicas y aritméticas que hacen funcionar a nuestras equipos que desarrollaran tareas especificas. En definitiva, es su cerebro.
A diferencia del microprocesador que es desarrollado para cumplir tareas generales, este se dearrolla para dar solución a un problema particular.
![microcontrolador][micro] 
## ¿Qué es IOT?
Es la interconexion de todos los dispositivos (de hay el nombre de internet de las cosas) tan basicos como un foco, ventilador, hasta refrigeradoras y demás a traves de internet, con el fin de recolectar datos y poder contralar a todas las "cosas".
![IOT][iot] 
## ¿Cuál es la tendencia ?
Ahora vamos a entrar al tema más interesante, Gartner predice que habrá cerca de 20 mil millones de dispositivos conectados al IoT para 2020, y los proveedores de productos y servicios de IoT generarán más de 300 mil millones de dólares en ingresos..

# Todo conectado
2018 será el año de IoT para el consumidor más que el IoT industrial. Habrá una gran cantidad de oportunidades en el espacio industrial de Internet, donde los dispositivos y redes conectadas aprovecharán el análisis en tiempo real, la retroalimentación, etc.

# Nueva infraestructura de datos
La recopilación de datos de sensores es buena, pero el objetivo final es obtener información procesable a partir de esos datos, y eso requerirá una nueva infraestructura de datos.

# Entra en juego el Edge Computing

El procesamiento se extiende al borde de IoT en 2018, se espera ver tejidos de datos y computación que abarquen las instalaciones locales en múltiples nubes. 

# Los ataques de IoT estarán motivados por las ganancias financieras

Cisco predice que hasta 1 millón de nuevas conexiones por hora se agregarán a Internet para 2020, expandiendo la superficie de ataque y haciendo que las vulnerabilidades de IoT sean más críticas y más peligrosas.

## ¿Qué es MicroPython?
MicroPython es 
## Dispositivos compatibles
- [Pyboard]
- [WiPy]
- [ESP8266]
- [ESP32]


[pyboard]: <https://store.micropython.org/>
[WiPy]: <https://www.adafruit.com/product/3338>
[ESP8266]: <https://es.aliexpress.com/store/product/NodeMCU-V3-Lua-WIFI-module-integration-of-ESP8266-extra-memory-32M-flash-USB-serial-CP2102/1950989_32779738528.html?spm=a219c.12010615.0.0.50b246fd8VsCwn>
[ESP32]: <https://es.aliexpress.com/store/product/Lolin-ESP32-OLED-wemos-for-Arduino-ESP32-OLED-WiFi-Modules-Bluetooth-Dual-ESP-32-ESP-32S/1983387_32807531243.html?spm=a219c.search0104.3.3.403e6f61OdnCLU&ws_ab_test=searchweb0_0,searchweb201602_1_10152_10151_10065_10344_10068_10342_10343_10340_10341_10084_10083_10618_10307_5711211_10313_10059_10534_100031_10103_10627_10626_10624_10623_10622_5722411_10621_10620_5711311-5722411_10620,searchweb201603_25,ppcSwitch_5&algo_expid=596a44ad-9bbc-41cb-8286-8cf1c8ba23be-0&algo_pvid=596a44ad-9bbc-41cb-8286-8cf1c8ba23be&priceBeautifyAB=0>

[iot]: img/iot.jpg "Internet De las Cosas"
[micro]: img/microcontrolador.jpg "Microcontrolador"
[MicroPython]: img/microPython.jpg "MicroPython"

>>>>>>> f0165c526f32ac9728f9f72c460932c9c95e2b18
>>>>>>> f0165c526f32ac9728f9f72c460932c9c95e2b18
