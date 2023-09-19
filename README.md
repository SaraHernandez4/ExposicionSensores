# Departamento de Sistemas y Computación
# Ing. En Sistemas Computacionales
# Sistemas Programables 23a

## Autor (es): Hernández Sáenz Sara Jazmín
## Fecha de revisión: 19/Septiembre/2023

**_Objetivo_**
Aprender más de GitHub y explorar las distintas cosas que ofrece en su plataforma.


# Exposición Sensor PIR Motion Sensor

**_Marco Teórico_**
## Sensores
El uso de sensores se ha convertido en una herramienta habitual en muchos sectores industriales y empresariales, pues **permiten controlar de forma remota distintos parámetros interesantes**. Por ejemplo, un sensor de movimiento es un elemento que se utiliza en seguridad para identificar el tránsito de personas y puede implementarse en sistemas de alarma, cámaras de videovigilancia y similares. A continuación, hablaremos de los sensores de movimiento PIR, cómo funciona un sensor de movimiento de este tipo y por qué son tan populares en la actualidad.

![](https://sites.google.com/a/utecnologica.edu.bo/iot-wearablesensaludutb/_/rsrc/1458974819461/sobre/marco-teorico/sensores/robotica-introduccin-17-638.jpg)

## ¿Qué es el sensor PIR?
Los detectores pasivos infrarrojos o PIR (Passive Infrared) son dispositivos que detectan variaciones de la radiación infrarroja en el área de cobertura, por lo que son especialmente útiles para detectar la presencia de personas o animales a través del calor que emiten sus cuerpos. El concepto pasivo del nombre de PIR hace referencia a que no generan de forma activa ninguna señal y solo reciben radiaciones para su funcionamiento.

![](https://www.puntoflotante.net/SENSOR-HC-SR501-1000-M.jpg)

Un sensor PIR está compuesto principalmente por un componente (sensor piroeléctrico) que se encarga de detectar variaciones en las radiaciones infrarrojas que recibe y las procesa como una señal electrica

**_Ficha Técnica_**
### ¿Cómo funciona un sensor de movimiento de pasivos infrarrojos?
Un sensor PIR o piroeléctrico funciona comparando la temperatura que desprende un objeto con la de su alrededor, de forma que puede detectar con precisión una presencia en un lugar determinado.

![](https://i0.wp.com/blog.330ohms.com/wp-content/uploads/2020/12/destacada.png?resize=696%2C392&ssl=1)

Cuando se activa, un sensor de este tipo realiza un calibrado o chequeo del ambiente, determinando los distintos niveles de radiación de los objetos presentes. De esta manera puede detectar una variación sustancial en la radiación infrarroja, como la que emitiría una persona o un animal.

El sensor de movimiento realiza un pulso cada cierto tiempo (parámetro ajustable) para verificar si las condiciones han cambiado. Si en este proceso detecta un cambio significativo en la variación de radiación, activa un aviso de que ha detectado una persona o un animal.

### Principales usos de los sensores de movimiento PIR
**Sistemas de iluminación automática.** Se utilizan en sistema de iluminación automática para encender una luz cuando se detecta el movimiento o presencia de una persona. Es muy útil en sistemas de alumbrado automatizados para ahorrar energía, ya que el sistema se activa solo cuando es necesario.

![](https://imagenes.elpais.com/resizer/6R915_uHvEsm-uRsGsFZD1MGX9Q=/414x0/cloudfront-eu-central-1.images.arcpublishing.com/prisa/AQ6HIA3NL5DRPACANEIIUQUSIM.jpg)

**Sistemas de apertura automática.** Se implementan en sistemas de apertura para proceder a activarlas de forma automática cuando detectan movimiento. En este tipo de sistemas tenemos la apertura de puertas y barreras, los grifos de agua y puertas de ascensor y similares.

![](https://autopuerta.net/wp-content/uploads/2023/06/como-funciona-el-mecanismo-de-una-puerta-automatica.jpg)

**Sistemas de seguridad.** Para activar una alarma o iniciar la grabación de cámaras de seguridad únicamente cuando detecten movimiento de personas o animales.

![](https://cuadernosdeseguridad.com/wp-content/uploads/2018/01/cctv-cra.jpg)

