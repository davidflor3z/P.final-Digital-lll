# P.final-Digital-lll

# idea de proyecto final:
Se busca realizar un carrito que pueda transportar un paquete dese un punto A hasta un punto B. Para dicha operación el carrito contará con un sensor de ultra sonido con el cual va a evitar chocar con los diferentes obstáculos que se le presenten. Se propone que el punto A y el punto B estén en una línea recta , es decir, que el carrito se ponga en una posición especifica para que en un principio solo tenga que avanzar en hacia el frente. Además, este solo se moverá hacia 4 direcciones (adelante, atrás, derecha , izquierda) según lo indique el obstáculo (no se moverá en diagonal). Se propone así para poder ingresar una distancia entre A y B, y así, cuando el carrito recorra toda la distancia AB se detenga.

# requisitos funcionales:
- Para comunicarle al dispositivo la distancia AB, se desarrollará un control que envíe de forma inalámbrica esta información al dispositivo.
- El control debe estar diseñado con 3 botones, uno para aumentar la distancia, otro para disminuirla , y el ultimo para que el dispositivo empiece su recorrido. Además, el mismo control debe tener 3 dispalys de 7 segmentos en los que se verá la distancia AB establecida.
- El dispositivo debe tener la capacidad de diferenciar la dirección en la que se está moviendo (adelante, atrás, derecha, izquierda).
- Para que el dispositivo llegue al punto B de forma correcta, debe tener en cuenta la distancia que se mueve en cada dirección
- El dispositivo tendrá incorporado un botón que debe ser presionado por el destinatario cuando llegue al punto B con la entrega, para notificarle al remitente que el paquete fue entregado.

# requisitos no funcionales 
- Principalmente, el dispositivo debe ser capaz de proporcionarle a los usuarios la comodidad de no tener que moverse del lugar en el que están para poder intercambiar objetos.
- El dispositivo debe ser capaz de transportar objetos cuyo peso no sea mayor a 1kg
- Como se desea que el dispositivo sea capaz de transportar objetos en un entorno pequeño (hogar, oficina, etc…) el error en la distancia AB que se manejará rondará los 10 cm.
- El dispositivo debe ser capaz de detectar un obstáculo a una distancia de alrededor 15 cm para que pueda cambiar su dirección si riesgos de chocar.
- La interfaz de usuario en el control y en el dispositivo debe ser intuitiva para los usuarios.

# escenario de pruebas 
El escenario de pruebas para el dispositivo debe ser un lugar cuyo espacio sea similar al de un apartamento o una oficina, donde se encuentren algunos obstáculos (sillas, mesas, zapatos, bolsos, etc) que el dispositivo pueda superar para poder entregarle al destinatario el paquete enviado por el remitente. Para que la necesidad que el dispositivo quiere cumplir tenga sentido, también se necesitan los usuarios (remitente y destinatario) y el objeto que se desea enviar. dicho objeto no debe pesar mas de un 1kg y debe ser compacto y sus dimensiones no deben superar los 15 cm^3.

# costos 
Transmisor wifi $12.000

dispaly 7 segmentos x3 $4000

3 botones $3000

Circuito impreso para el control $15000


Receptor wi fi $12000

Raspberry pi pico $32000

Base del auto con llantas $40000

Sensor ultrasonido $8000

Servo motor $10000

4 motorreductores $40000

Baterías del carrito $36000

total $212000
