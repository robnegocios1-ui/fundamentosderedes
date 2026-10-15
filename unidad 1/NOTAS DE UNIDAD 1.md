### 5 PILARES DE UNA RED COMPUTACION

-NODOS:el origen y destino:son los dispositivos que envían o reciben información.
**-ENLACES:el camino fisico** :es el camino por donde viaja la información.
**-DIRECCIONES:identidad digital**:es como la dirección de una casa, pero para un dispositivo en una red.
**-PROTOCOLOS:el lenguaje comun**:Son las reglas que indican cómo deben comunicarse los dispositivos.
**-ENRUTAMIENTO: Gestion de rutas**:Es el proceso de decidir por qué camino debe viajar la información para llegar a su destino.

TCP:es un protocolo orientado a la conexión y fiable
UDP:es un protocolo sin conexión y rápido

### 4 caracteristicas que deben tener las redes 

1.Tolerancia a fallas: es la capacidad de una red para seguir operando cuando falla un enlace o dispositivo, sin que la comunicación se detenga por completo 
2.Escabilidad:es la capacidad de una red para crecer sin tener que rediseñarla desde cero cada vez que crece
3.Calidad de servicio(QoS):La calidad de servicio es el conjunto de mecanismos que decide qué trafico se atiende primero cuando la red no tiene capacidad suficiente para todos al mismo tiempo
4.Seguridad: se refiere a proteger la red y información que circula por ella contra accesos, modificaciones o interrupciones no autorizadas

Ataces mas comunes cuando entran a la red

1.Suplantacion de MAC/IP(spoofing)
2.Ataque de intermediario(man-in-the-middle)
3.Denegación de servicios(Dos/Ddos)
4.Acceso no autorizado a un punto de acceso inalámbrico 
5.Pishing ingeniería social

### Arquitectura de redes
La arquitectura de red es el conjunto de reglas y decisiones de diseño que definen cómo se organiza una red para que la comunicación funcione:qué función cumple cada parte, orden se procesan los datos y quién tienen el control sobre qué 
### Modelos de referencia 
Una red se diseña dividiéndola en capas independientes, donde cada capa resuelve un problema especifico sin necesitar saber como trabajan las demás 

Un ejemplo de modelo referencia es el **modelo OSI** que tiene siete capas que son fisica, enlace, red, transporte, sesión, presentación y aplicación que describe todas las funciones que intervienen en una comunicación de red(hay otra capa que no se conoce otra que es la 8 capa que es usuario)

Otro ejemplo de modelo de referencia es el Modelo TCP/IP que tiene cuatro capas que son acceso a red, internet, transporte 

###### Cómo funciona el modelo TCP/IP

Sigue el recorrido de un mensaje: baja por las capas del emisor ganando un encabezado en cada una, cruza el medio físico, y sube por las capas del receptor perdiendo esos encabezados en orden inverso.
![[Screenshot 2026-09-17 at 3.46.18 p.m..png|435]]

