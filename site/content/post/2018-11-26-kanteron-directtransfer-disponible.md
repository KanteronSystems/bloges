---
date: 2018-11-26T20:14:57+00:00
title: Kanteron Systems anuncia la disponibilidad de DirectTransfer - Adiós a cortafuegos, SSL o NAT
tags: ["kanteron", "producto"]
images: "https://images.unsplash.com/photo-1531765408077-9a1f85f90df1?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=5552dcbc19e44defbe7327577f0a2835&auto=format&fit=crop&w=1352&q=80"
comments: true     # set false to hide Disqus comments
share: true        # set false to share buttons
thumbnailImagePosition: right
thumbnailImage: https://images.unsplash.com/photo-1531765408077-9a1f85f90df1?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=5552dcbc19e44defbe7327577f0a2835&auto=format&fit=crop&w=1352&q=80
coverImage: https://images.unsplash.com/photo-1531765408077-9a1f85f90df1?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=5552dcbc19e44defbe7327577f0a2835&auto=format&fit=crop&w=1352&q=80
metaAlignment: center
coverMeta: out

---
Kanteron Systems anuncia la disponibilidad de una nueva manera de conectar dispositivos de imágenes médicas.

<!--more-->

*DirectTransfer de Kanteron*; permitirá a las redes hospitalarias lograr mayores velocidades de transferencia, reducir costos y establecer redes de telemedicina a gran escala sin problemas mediante la aplicación de nuevos protocolos de red y algoritmos informáticos.

Kanteron Systems desarrolló este un nuevo hito de la industria en 2016, pero no ha sido hasta ahora, cuando los proveedores de telecomunicaciones han actualizado sus redes, que se puede ofrecer esta nueva tecnología en determinados mercados. Gracias al soporte completo de esta tecnología por parte de Telefónica, los primeros países en los que se ofrece son: Perú, Brasil y México. En unos meses se ampliará a otros muchos países, como Alemania, Malasia, Tailandia, Japón, Australia, etc.

Esta innovación surge del aprovechamiento de los últimos protocolos de red diseñados para la multimedia _online_ y la aplicación de las lecciones aprendidas de la Internet de las cosas (IoT), para lograr un enrutamiento y procesamiento de paquetes de datos más eficiente, flujos de datos dirigidos, simplificación de la configuración de red, y seguridad reforzada.

> Los sistemas de imágenes y datos médicos existentes se basan en mecanismos que tienen décadas de antigüedad&, dijo Jorge Cortell, director general de Kanteron Systems. Mediante la aplicación de las últimas tecnologías disponibles y el aprovechamiento de nuevos algoritmos informáticos, nuestra plataforma establece un nuevo estándar en el intercambio de datos e integración de la salud

En términos técnicos, esta nueva era de la conectividad de datos de la salud significa:

  * Pasar de la emisión _broadcast_ a multidifusión (unicast o)
  * De la traducción de direcciones de red (NAT) a una conectividad de extremo a extremo con una configuración simplificada de la red (dirección de la autoconfiguración)
  * De las transmisiones indiscriminadas a la Calidad de Servicio (QoS)

¿Qué significa este nuevo código base para el usuario? Por ejemplo, cuando se manejan de muchas imágenes (como la patología digital) o conjuntos de datos complejos (como secuenciación genómica de nueva generación), DirectTransfer de Kanteron realiza las peticiones al servidor de forma _multiplex_, con lo que la descarga de imágenes y los conjuntos de datos ocurren en paralelo, lo que significa velocidades mucho más rápidas que cualquier otro método disponible en el mercado hoy en día, incluyendo _streaming_.

Más allá de la velocidad, la fiabilidad es otra de las claves para el intercambio de datos en la asistencia sanitaria. DirectTransfer de Kanteron permite conectarse a más de un proveedor de servicios al mismo tiempo. Así que si un servicio falla, las sesiones de comunicación se pasan automáticamente a otro.

La fiabilidad se mejora aún más gracias a la autoconfiguración. Los sistemas más antiguos se basan en servidores DHCP (o engorrosas configuraciones manuales que consumen preciosos recursos del departamento de sistemas) para asignar direcciones de red a los dispositivos, que pueden causar problemas en las instituciones más grandes, proporcionando información contradictoria o el cambio de direcciones después de reinicios. Con DirectTransfer de Kanteron, todo esto es en gran medida innecesario debido a la configuración automática _stateless_. Lo que significa la conectividad sin fisuras entre un número virtualmente ilimitado de dispositivos médicos.

Con DirectTransfer de Kanteron, cada dispositivo médico en una red, literalmente puede tener su propia dirección única. La mayoría de las instituciones de salud sólo tienen varias direcciones IP en Internet, asignadas al router que los conecta con su proveedor de servicios. El router a su vez emite direcciones IP internamente a los dispositivos que se conectan a ella, pero debe monitorear continuamente el tráfico al que pertenece a cada dispositivo, y traducir la dirección IP desde la interna a la pública con el fin de facilitar las comunicaciones con otras instituciones sanitarias. DirectTransfer de Kanteron no necesita nada de eso, lo que significa una integración de datos entre las instituciones de salud más rápida y sencilla, más fiable, segura y transparente.

Pero tal vez la innovación más importante y radical de DirectTransfer de Kanteron se encuentra en la seguridad de los datos. La mayoría de los mecanismos de conexión existentes no han sido diseñados pensando en la seguridad. Por lo tanto, los sistemas de salud se basan en cortafuegos y SSL, engorrosos y a menudo vulnerables, que sólo funcionan en parte de la transmisión de datos. Con esos sistemas también es más difícil de implementar y solucionar problemas de seguridad porque utilizan NAT, que interrumpen la trazabilidad, y por lo tanto las pistas de auditoría de seguridad, considerado por algunos protocolos de seguridad como una violación de la seguridad.

La seguridad de Kanteron de DirectTransfer también incluye:

  * Capa especial de seguridad incorporada, cifrando cada paquete individual
  * Algoritmos de autenticación basados en firmas destinadas a que el tráfico de datos seguro llegue a su destino correcto sin ser interceptado
  * Permitir intercambios de claves digitales y túneles virtuales
  * Un algoritmo adicional que proporciona confidencialidad, y la autenticación de la fuente
  * Integridad sin conexión del paquete interno
  * Antireplay
  * Confidencialidad del flujo de tráfico limitado

Para asegurar la compatibilidad con redes hospitalarias existentes, DirectTransfer es compatible con estructuras de redes anteriores. Esto asegura la conectividad entre redes antigüas y nuevas mediante el _dual stack_.
