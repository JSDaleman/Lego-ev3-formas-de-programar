# Lego-ev3-formas-de-programar
**Autor:** Juan Sebastian Daleman 

Este repositorio encontraras diferentes metodos con los que se puede usar el robot Lego mindstorms ev3. Entre lo que encontraras a:
- EV3-G el cual es el entorno creado por lego para programación de forma grafica o por bloques.
- Scratch es otro entorno creado por Lego el cual permite una programación por bloques muy sencilla de entender.
- ROBOTC el cual permite la programación de lenguaje C como simulación del robot.
- LeJOS EV3 el cual es un entorno para programación en lenguaje Java.
- el Toolbox MINDSTORMS de MATLAB el cual es un paquete para poder crear scripts en matlab que manejan el hardware de Lego mindstorms ev3.
- ev3dev el cual es un sistema basado en linux debian que permite la programación del robot en diferentes lenguajes y trabajar diferentes herramientas de linux.
- micropython es una forma tambien implementada por Lego la cual usando el IDE de Visual Studio Code permite el manejo con python del robot.

# Robot para trabajar
Ya que con el kit de lego presenta muchas configuraciones por facilidad en la demostración de diferentes ejemplos la configuración que se usara es la de (base motriz)[https://assets.education.lego.com/v3/assets/blt293eea581807678a/blt6e7360758df8f1ea/5ec7c6dd2238e044d39d24b0/ev3-rem-driving-base.pdf?locale=es-es]
Con los sensorese de:
- (Tactil)[https://assets.education.lego.com/v3/assets/blt293eea581807678a/blt21b1ad4aeb504517/5ec6621356542b5199dba9df/ev3-touch-sensor-driving-base.pdf?locale=es-mx] en el puerto 1
- (Giro sensor)[https://assets.education.lego.com/v3/assets/blt293eea581807678a/blt92a6038ac499624e/5ec638edf555a0037565aa22/ev3-gyro-sensor-driving-base.pdf?locale=es-es] en el puerto 2
- (Ultra sonido)[https://assets.education.lego.com/v3/assets/blt293eea581807678a/bltedef29b6f889ec04/5ec7bfe42de1237ddb71fd6a/ev3-ultrasonic-sensor-driving-base.pdf?locale=es-mx] en el puerto 3
- (Color)[https://assets.education.lego.com/v3/assets/blt293eea581807678a/bltb5bea28afb585684/5ec7c907cd4cf750c888fad6/ev3-rem-color-sensor-down-driving-base.pdf?locale=es-mx] en el puerto 4

Motores:
- De tracción en los puertos B y C
- (Motor mediano)[https://assets.education.lego.com/v3/assets/blt293eea581807678a/blt5c3aa94ebe1a56ac/5ec7c08df1de13036f79abf7/ev3-medium-motor-driving-base.pdf?locale=es-mx] en el puerto A

Lo cual dejara un robot de la siguien manera:

![Ev3](https://github.com/JSDaleman/Lego-ev3-formas-de-programar/assets/70998067/9ec99b21-3901-43e4-9654-21d5d1aeb689)

# Elementos extras necesarios

Dependiendo de como desees programar tu robot Lego ev3 son necesarias algunas herramientas extras como:
- Micro SD
- Antena WI-FI
- USB HUB

**Nota:** Antes de comprar te recomiendo leer en datalle las siguientes secciones donde se se recomiendan tener cuidado con ciertas cosas

## Micro SD
El robot Lego mindstorms tiene una capacidad de leer una memoria micro SD hasta 32GB con tecnologia HC por lo cual una más grande presentara problemas o no sera compatible. Algunas recomendaciones tecnicas de la (micro SD)[https://github.com/ev3dev/ev3dev/wiki/Selecting-a-microSD-card] podras verlas en ese enalce en los enlaces de la pagina podras ver más a detalle algunas cosas como velocidades de procesamiento y entre marcas cual puede ser mejor para su uso.

## Antena wi-fi
Si deseas una antena wi-fi que sea compatible con todos los sistemas lego recomienda la [Netgear N150](https://www.lego.com/es-es/service/help/mindstorms_ev3_sets/mindstorms_ev3/mindstorms_ev3/connecting-your-lego-mindstorms-ev3-to-wi-fi-kA009000001dcjmCAA) esta antena puede ser muy costosa otra opción oficial es EW-7811Un cuyo chitset es compatible o una opción aun más economica es RTL8188CUS 802.11n el cual tambien tene un chitset compatible y puede ser más facil de adquirir. 

Ya si vas a usar LeJOS o ev3dev la gama de antenas disponibles es mucho más grande teniendo algunas comparativas para (LeJOS)[https://lejosnews.wordpress.com/2015/02/03/comparing-wifi-adapters/] y recomendaciones para (ev3dev)[https://github.com/ev3dev/ev3dev/wiki/USB-Wi-Fi-Dongles].

**Nota:** Cuando veas las secciones de LeJOS y ev3dev se trabaja con la antena TP-LINK TL-WN725N 150Mbps

## USB HUB
Dependiendo de que proyectos desees hacer con el robot ev3 puede llegar a ser necesario o no. En algunos proyectos es necesario para alimentar sensores o sistemas como en el proyecto de mapeo con (sensor lidar)[https://www.ev3dev.org/projects/2016/08/07/Mapping/].

**Nota:** En casos como el del proyecto mencionado puede ser necesario modificar cables lo cual puedes hacer o si prefieres puedes diseñar una PCB para hacer la adaptación con el (conector hembra)[https://es.aliexpress.com/item/1005006719724490.html?spm=a2g0o.productlist.main.51.36c5TCqaTCqaU9&algo_pvid=b9375f0f-a6b0-443f-833c-dac1e098fae9&algo_exp_id=b9375f0f-a6b0-443f-833c-dac1e098fae9-25&pdp_npi=4%40dis%21COP%212125.29%211059.94%21%21%213.93%211.96%21%402103297417159717785081762eeb32%2112000038087232559%21sea%21CO%213174043039%21AB&curPageLogUid=qOCUA5WVkecq&utparam-url=scene%3Asearch%7Cquery_from%3A]

# EV3-G

![image](https://github.com/JSDaleman/Lego-ev3-formas-de-programar/assets/70998067/9192525b-cc8c-40f6-b059-2c73236f5703)

Este software esta basado en una programación gráfica fue desarrollado por National Instruments el cual se basa en bloques de programación los cuales se basan en secciones de acción, flujo de control, sensores, operaciones matemáticas, manejo de mensajes y bloques personalizados.

[Conoce más](https://github.com/JSDaleman/Lego-ev3-formas-de-programar/blob/main/EV3-G/EV3-G.md)


# Scratch

# ROBOTC

# LeJOS EV3

# el Toolbox MINDSTORMS

# ev3dev

# micropython
