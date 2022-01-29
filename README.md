# PROGRAMAR ARDUINO CON CH340
## Breve Introducción
Como se sabe existe en el mercado la Tarjeta Arduino Pro Mini, la cual es de bajo costo y que trabaja tan igual como un Arduino Uno, la única desventaja es que no cuenta con conversor USB a TTL, por lo que debemos de utilizar un dispositivo adicional para cargar nuestros Programas.
En esta ocasión, veremos los pasos necesarios para programar nuestro Arduino Pro Mini haciendo uso de un conversor USB-TTL basado en el Chip CH340.

## Diagrama de Conexiones
Se presenta el diagrama de conexiones necesarias, recordando tener presente el voltaje de trabajo del Arduino Pro Mini, para las conexiones respectivas.
Se usaron cables jumper Macho - Hembra, de esta forma no fue tan obligatorio utilizar un protoboard o breadboard para otros. En total son necesarios 4 cables.

## Cargando nuestros Códigos
Para cargar nuestros códigos, simplemente conectamos el conversor USB-TTL a nuestra PC y seleccionamos el Puerto Com que es el atribuido. Si es necesario cambiar el tipo de placa que estamos usando, en este caso Arduino Pro Mini.
Es importarte tener presente que se debe conectar directamente a nuestra PC el Conversor USB-TTL CH340.
En este caso se selecciono Atmega328P 3.3V, ya que el ejemplo se realizo con un Arduino Pro Mini de 3.3V, en caso el nivel de tensión de trabajo es de 5V, se deberá elegir la opción correspondiente.
Como el conversor USB-TTL que estamos usando no cuenta con pin de DTR, debemos de presionar el botón de reset del Arduino Pro Mini por aproximadamente 1 segundo, esto lo haremos cuando el estado de carga cambie de compilando a subiendo.
A continuación si hay alguna duda, te invito a que revises el video instructivo completo y paso a paso, siempre bienvenido a dejar tus comentarios.

✅ Tutorial: https://youtu.be/ytdgPlsENiM

## FABRICANTE DE PCB
Una vez que terminamos nuestra placa de desarrollo; es hora de traerlo a la vida. Para fabricar nuestra placa, utilizaremos los servicios de JLCPB. En caso de que aún no tenga una cuenta, consulte el siguiente enlace
►JLCPCB: https://jlcpcb.com/IAT

## Como Hacer Pedidos en JLCPCB ?
Una vez que nos registramos e iniciamos sesión en nuestra cuenta, estamos listos para enviar un pedido y recibir nuestra placa en muy poco tiempo. En este caso, primero debemos actualizar los archivos gerber, que contienen toda la información necesaria para construir la pcb. Puede obtener los archivos gerber en el siguiente enlace.

### Sube tus archivos Gerber
### Indicar las características
### Agrega tu dirección de envío
Esta parte es muy importante, aquí debe escribir su dirección actual, donde le gustaría recibir sus prototipos de PCB. No es común pero a veces muy rara vez, tendrás que pagar feeds extra, pero como te dije, es muy rara vez.
### Realiza el pago y finaliza el pedido
Después de que indiques esta información, continuamos con la sección de pago, esta es la sección donde puedes aplicar tus cupones o códigos de descuento. Básicamente, podemos completar el pago de dos formas generales, Paypal o tarjeta de crédito.
### Recibe tu PCB
Días después, 7 días o unos pocos más, de acuerdo con su ubicación y el proceso del agente de aduanas, recibirá sus prototipos de PCB.

## ¿Por qué JCLPCB?
JLCPCB ha estado a la vanguardia de la industria de PCB. Con más de 14 años de innovación y mejora continuas basadas en las necesidades de los clientes, hemos crecido rápidamente y nos hemos convertido en un fabricante líder mundial de PCB, que proporciona la producción rápida de PCB rentables y de alta confiabilidad y crea la mejor experiencia para el cliente en la industria. En caso de que aún no tenga una cuenta, consulte el siguiente enlace.
►JLCPCB: https://jlcpcb.com/IAT
- Las soluciones de PCB más eficientes, económicas e innovadoras
- Las soluciones de PCB más eficientes, económicas e innovadoras
- Mejor calidad
- Costo más bajo
- Entrega más rápida

## THANKS
Thank to:
### ► JLCPCB: https://jlcpcb.com/IAT
## SUBSCRIBE:
### ✅ Youtube: https://bit.ly/3adS4mV
