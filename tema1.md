
# Ingenieria de sistemas moviles

Las redes han sufrido un enorme auge en los ultimos años que le han llevado a una mayor demanda de aplicaciones web.

Inalámbrico vs móvil, todo lo inalambrico no es un dispositivo movil, como por ejemplo una impresora. Si un dispositivo siempre tiene que estar conectado a una red inalambrica, no 
se considera un dispositivo móvil.


# Redes de ordenadores
- Desde un enfoque de desarrollo de sistemas móviles. Los elementos mas relevantes, son el protocolo de comuncación, la topología, la seguridad, y el medio de transmisión.

- El medio de transmision de las comunicaciones inalambricas es el espectro electromagnetico que coloquialmente denominamos aire.

a) Infrarrojos, es muy utilizada en las comunicaciones, sobre todo en las comunicaciones punto a punto
b) Microondas, conexiones punto a punto
c) Radiofrecuencias

Según el alcance, nos podemos encontrar,
- Redes de área personal inalambrica
- Redes de area local
- ...

### Redes de personales inalambricas (WPAN)
- Es importante el blueooth, logra de los 10 m a los 70m. En lo normal, dependiendo de los obstaculos llega entre 10 y 20. Es una conexión master-slave. Y es una de las que más ha 
mejorado ultimamente.
- Cambiaron el estar siempre estar conectado, al estar conectado un momento, pasar paquetes e identificar a los dispositivos de manera inequivoca. Esto es dado sobre todo al auge de las IOT.


#### DECT. WPAN
- Se desarrollo para suplantar al telefono

#### IRDA
- Infrared Data Association, utiliza los infrarrojos y es muy utilizada a lo largo del tiempo. Se utilizaba con las pda para conectarse con el ordenador.


#### NFC

Near Feal Communications. Es novedoso, surgio de la union de phillips y sony y sacaron este standard, trabaja sbre los 13 mhz. La distancia de comunicación ha de ser inferior a 10 cm.
Modos de uso, tiene dos modos un modo activo y un modo pasivo

Como funciona la NFC.

- descubrimiento de dispositivos
- Autenticacion
- Negociacion
- Transferencia de informacion y confirmacion

Incorpora un elemento seguro. Tiene una zona donde toda la informacion esta encriptada de la misma forma que una tarjeta de credito.

NFC por sí solo no sirve ya que solo llega a 10 cm. Para ello es necesarop otra con mayor ancho de banda como son bluetooth. Es mucho más rápida que otras ya que su conexion esta
al orden de los 200 ms.

### Arquitectura de un dispositivo movil NFC.

1. Una bobina/antena en el telefono
2. El chip NFC
3. El denominado elemento seguro
  Antiguamente este elemento seguro estaba en hardware. Hoy en dia o bien esta en una especie de tarjeta de memoria o en una sim.
  Hay distintos tipos de configuraciones.
  
  - Modo de tarjeta inteligente.
  Como si fuera una tarjeta de credito/seguridad
  
  - Modo pee to peer donde los dispositivos pueden comunicarse. La transferencia de datos no es demasiado grande son pequeños trozos de informacion
  
  - Modo lector/grabador con capacidad de lectura y escritura de etiquetas  o tags.
  
  Tags NFC 






