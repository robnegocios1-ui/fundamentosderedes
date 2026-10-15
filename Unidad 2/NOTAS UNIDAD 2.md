
### Red de area personal(PAN)
conecta dispositivos que pertenecen a una sola persona  estan a muy corta distancia entre si, normalmente pocos metors
Caractersitcas: Tiene un alcance de hasta 10 metros, bajo consumo de energia, y con frecuencia usa tecnologias inalambricas como Bluetooth en lugar de cable.


### Red de Área local(LAN)
conecta dispositivos dentro de un espacio fisico unico como una casa, oficina, salon de clases o un solo edificio
Caracteristicas: Es la red que una sola organización controla y administra por completo, suele tener alta velocidad y bajo costo por su alcance ilimitado

### Red Inalámbrica  de área local(WLAN)
Es una LAN que usa el espectro radioeléctrico en lugar de cables  para conectar los dispositivos dentro del mismo espacio 
Características:El acceso se hace a través de uno o más puntos de acceso(AP); a cambio de movilidad, el medio es compartido  y mas sensible a interferencia 

### Red de àrea amplia(WAN)
Conecta redes que están geográficamente distantes, a veces en distintas ciudades, paises o continentes
Caracteristicas: ya no lo administra una sola organización Suele depender de proveedores de telecomunicaciones y su costo y latencia son mayores que en una LAN

Comparacion por alcance de menor a mayor cobertura:PAN(una persona) -> LAN/WLAN(un edificio)->Campus area network(varios edificios de una organización)-.WAN(distintas ciudades o países)
Lo que las distingue no es la tecnologia que usan si no quien la administra y que tan lejos llega

### ¿El Internet es la WAN más grande del mundo?
Si

### ¿Que es el modelo TCP/IP?
Es un modelo de cuatro capas que describe cómo se comunican los dispositivos en una red real, se implementa tal cual en el internet y en la mayoria de las redes actuales
Nació del proyecto ARPANET en los años setenta , antes que el modelo OSI; por eso es el modelo práctico, construido desde la implementacion y no desde la teoría

### Capa de aplicación
Es donde viven los programas y servicios que el usuario reconoce como navegación web, correo, mensajeria.Agrupa lo que en OSI son tres capas separadas: aplicación, presentación y sesión.

### Capa de transporte
Divide el mensaje en segmentos, agrega números de puerta de origen y destino, y decide si la entrega necesita confirmación(TCP)o no(UDP)

### Capa de internet
Agrega las direcciones IP de origen y destino y es responsable de que el paquete encuentre s ruta entre redes distintas;aqui vive el protocolo IP

### Capa de Acceso a la red
Agrega la dirección MAC del siguiente salto y convierte los datos en señal para el medio fisicio;agrupa lo que en OSI son las capas de enlace y física

