# Evaluación de Redes y Sistemas Operativos

|         Nombre:         |   Fecha:    | Matrícula: |
|-------------------------|-------------|------------|
| Yanet González García   | 22/08/2024  | 21620273   |

## Instrucciones

Responde las siguientes preguntas de manera clara y concisa. Cada sección tiene un peso específico, así que distribuye tu tiempo en consecuencia.

## Sección 1: Componentes de un Sistema de Red (20%)

Pregunta de Opción Múltiple:<br>
Identifica cuáles de los siguientes elementos son componentes fundamentales de un sistema de red:<br>

- [X] Switch
- [X] Router
- [ ] Monitor
- [X] Cableado
- [ ] CPU
- [X] Firewall

Pregunta Abierta:<br>
Explica la función de un router en una red y cómo se diferencia de un switch.<br>
___Respuesta___
Un router es un dispositivo que se encarga de dirigir el tráfico de datos entre diferentes redes. Su principal función es encontrar la mejor ruta para enviar los paquetes de datos a su destino, incluso si deben atravesar múltiples redes. A diferencia de un switch, que opera a nivel de capa 2 (enlace de datos) conectando dispositivos dentro de una misma red local, el router opera en la capa 3 (red) y conecta diferentes redes entre sí.

Pregunta de Emparejamiento:<br>
Relaciona los siguientes componentes de una red con su función principal:<br>

| Componente                      | Función principal |
|---------------------------------|-------------------|
| [D] Servidor                    | A) Protege la red de accesos no autorizados. |
| [A] Firewall                    | B) Facilita la conectividad inalámbrica. |
| [B] Punto de acceso inalámbrico | C) Transmite datos entre dispositivos de la red. |
| [C] Cable de par trenzado       | D) Proporciona recursos a los usuarios de la red. |

## Sección 2: Protocolo de Conexión TCP/IP (20%)

Pregunta Verdadero/Falso:<br>
TCP/IP es un protocolo que se utiliza exclusivamente para redes privadas, como las LANs.

- [ ] Verdadero
- [X] Falso

Justifique su respuesta.<br>
___Respuesta___
Falso. TCP/IP es un conjunto de protocolos utilizado para la comunicación en redes tanto privadas como públicas, incluyendo Internet. Es el estándar para la transmisión de datos en una red, permitiendo que dispositivos de diferentes tipos se comuniquen entre sí.

Pregunta Abierta:<br>
Describe las diferencias clave entre TCP y UDP en términos de fiabilidad y uso.<br>
___Respuesta___
TCP es más fiable, asegurando la entrega ordenada de datos y corrigiendo errores. UDP es más rápido pero menos fiable, no garantiza la entrega ni el orden. TCP se usa en aplicaciones donde la fiabilidad es esencial, mientras que UDP se prefiere para transmisiones rápidas como video en tiempo real.

Pregunta de Desarrollo:<br>
Explica cómo se utilizan las direcciones IP y las máscaras de subred en el protocolo TCP/IP para enrutar datos a través de una red.<br>

___Respuesta___
En el protocolo TCP/IP, las direcciones IP identifican de manera única a los dispositivos en una red y se utilizan para dirigir los paquetes de datos al destino correcto. La máscara de subred divide una dirección IP en dos partes: la parte de la red y la parte del host. Esto permite a los routers determinar en qué subred está un dispositivo y a dónde deben enviar los paquetes. Si el destino está en la misma subred, el paquete se entrega directamente. Si está en otra subred, el paquete se envía a través de un router para llegar a la red correcta.

## Sección 3: Normas y Estándares de la Industria (10%)

Pregunta de Selección Múltiple:<br>
¿Cuál de los siguientes es un estándar de la industria para redes inalámbricas?<br>

- [ ] IEEE 802.3
- [X] IEEE 802.11
- [ ] IEEE 802.15
- [ ] IEEE 802.16

Pregunta de Desarrollo:<br>
Explica la importancia de seguir normas y estándares de la industria al diseñar redes en una organización. Proporcione ejemplos de dos normas específicas.<br>

___Respuesta___
Seguir normas y estándares de la industria al diseñar redes es fundamental para garantizar la compatibilidad, la interoperabilidad y la seguridad de los sistemas de comunicación. Estas normas aseguran que los dispositivos y software de diferentes fabricantes funcionen juntos sin problemas, lo que facilita la expansión y el mantenimiento de la red. Por ejemplo, el estándar IEEE 802.11 garantiza que diferentes dispositivos Wi-Fi puedan conectarse y comunicarse en una red inalámbrica. Otro ejemplo es el estándar IEEE 802.3, que regula la tecnología Ethernet, garantizando una comunicación eficiente y confiable en redes cableadas.

Pregunta de Análisis de Caso:<br>
Una empresa está planeando la expansión de su red. Describe cómo aplicarías las normas y estándares de la industria para garantizar la compatibilidad y el rendimiento.<br>

___Respuesta___
Para garantizar la compatibilidad y el rendimiento en la expansión de la red de la empresa, comenzaría evaluando los estándares existentes en la red actual, como los protocolos de enrutamiento y las tecnologías de transmisión de datos. Implementaría estándares como IEEE 802.3 para asegurar una transmisión confiable en las conexiones cableadas y IEEE 802.11 para la conectividad inalámbrica. También me aseguraría de que todos los nuevos equipos y dispositivos sean compatibles con estos estándares, lo que facilitaría la integración de la nueva infraestructura con la ya existente, evitando problemas de incompatibilidad y optimizando el rendimiento de la red.

## Sección 4: Sistemas Operativos (10%)

Pregunta de Comparación:<br>
Compara las características principales de dos sistemas operativos populares (por ejemplo, Windows y Linux) en el contexto de su uso en redes.<br>

___Respuesta___
Windows Server y Linux son dos sistemas operativos ampliamente utilizados en entornos de red. Windows Server es conocido por su interfaz gráfica fácil de usar y su integración con otros productos de Microsoft, lo que facilita la gestión de redes y servicios dentro de un entorno Windows. Sin embargo, suele ser más costoso debido a las licencias. Linux, en cambio, es un sistema operativo de código abierto que ofrece mayor flexibilidad y personalización. Es conocido por su estabilidad y seguridad, siendo una opción popular para servidores web y redes donde se requiere un control detallado y bajo costo.

Pregunta Abierta:<br>
Explica cómo se puede seleccionar un sistema operativo adecuado para un servidor en una organización.<br>

___Respuesta___
Para seleccionar un sistema operativo adecuado para un servidor en una organización, es importante considerar factores como las necesidades específicas de la red, la compatibilidad con las aplicaciones que se van a utilizar, el presupuesto disponible y el nivel de soporte requerido. Por ejemplo, si la organización ya utiliza muchas aplicaciones de Microsoft, Windows Server podría ser la mejor opción debido a su compatibilidad y facilidad de integración. Por otro lado, si la organización busca una solución flexible y económica con un alto nivel de seguridad, Linux podría ser más adecuado.

Pregunta de Opción Múltiple:<br>
¿Cuál de los siguientes sistemas operativos es conocido por su estabilidad y seguridad en entornos de red?<br>

- [ ] Windows Server
- [ ] macOS
- [X] Linux
- [ ] Android

## Sección 5: Diseño de Redes Aplicando Normas y Estándares (10%)

Pregunta de Escenario:<br>
Tienes la tarea de diseñar una red para una oficina de 100 empleados. Describe los pasos que tomarías para asegurarte de que el diseño cumpla con las normas y estándares vigentes.<br>

___Respuesta___
Primero, realizaría un análisis de los requisitos de la red, considerando el número de usuarios, los dispositivos, y los tipos de aplicaciones que se utilizarán. Luego, seleccionaría tecnologías y equipos que cumplan con estándares como IEEE 802.3 para la red cableada e IEEE 802.11 para la red inalámbrica. Aseguraría que todos los dispositivos sean compatibles con IPv6, ya que es el estándar actual para direcciones IP. Finalmente, implementaría medidas de seguridad siguiendo normas como ISO/IEC 27001 para proteger la red contra accesos no autorizados.


Pregunta de Desarrollo:<br>
Explica el impacto de no seguir normas y estándares oficiales en el diseño de una red. Proporciona ejemplos de posibles problemas.<br>

___Respuesta___
No seguir normas y estándares oficiales en el diseño de una red puede resultar en problemas de compatibilidad, seguridad, y rendimiento. Por ejemplo, si no se sigue el estándar IEEE 802.11 para redes inalámbricas, es posible que los dispositivos de diferentes fabricantes no puedan conectarse entre sí, lo que dificultaría la operación diaria. Además, la falta de adherencia a estándares de seguridad como ISO/IEC 27001 podría dejar la red vulnerable a ataques cibernéticos, exponiendo datos confidenciales y afectando la reputación de la organización.

## Sección 6: Metodologías para el Análisis, Diseño e Instalación de Redes (10%)

Pregunta de Ensayo Corto:<br>
Describe brevemente una metodología comúnmente utilizada en el análisis y diseño de redes, como la metodología OSI.<br>

___Respuesta___
La metodología OSI es un modelo de referencia que divide las funciones de una red en siete capas, desde la capa física hasta la capa de aplicación. Cada capa tiene funciones específicas y se comunica con las capas adyacentes, lo que facilita el análisis, diseño y solución de problemas en redes. Este modelo es ampliamente utilizado para entender y diseñar redes complejas, asegurando que cada aspecto de la comunicación de datos se aborde de manera estructurada y eficiente.

Pregunta de Caso Práctico:<br>
Un cliente te ha pedido que diseñes e instales una red para su nueva sucursal. Explica cómo utilizarías una metodología para abordar este proyecto, desde el análisis de requerimientos hasta la instalación.<br>

___Respuesta___
Primero, realizaría un análisis de requerimientos para entender las necesidades del cliente, incluyendo el número de usuarios, dispositivos y aplicaciones. Luego, diseñaría la red utilizando una metodología estructurada como el modelo OSI, asegurando que cada capa de la red cumpla con los estándares adecuados. Posteriormente, seleccionaría los equipos y tecnologías que mejor se ajusten al diseño, planificando la instalación de acuerdo a un cronograma. Finalmente, instalaría y configuraría la red, realizando pruebas para asegurar su correcto funcionamiento y capacitando al personal en su uso.

## Sección 7: Seguridad en Redes (10%)

Pregunta de Opción Múltiple:<br>
¿Cuál de las siguientes medidas es más efectiva para proteger una red de accesos no autorizados?<br>

- [X] Cortafuegos
- [ ] Antivirus
- [ ] Actualizaciones de software
- [ ] Contraseñas seguras

Seleccione la respuesta correcta.

Pregunta de Desarrollo:<br>
Explica la importancia de implementar medidas de seguridad en una red y cómo estas pueden proteger la información confidencial de una organización.<br>

___Respuesta___
Implementar medidas de seguridad en una red es crucial para proteger la información confidencial de accesos no autorizados, ciberataques y filtraciones de datos. Medidas como el uso de cortafuegos, cifrado de datos y autenticación de usuarios previenen que actores malintencionados accedan a la red y comprometan la seguridad de la organización. Estas acciones no solo protegen la integridad y privacidad de la información, sino que también evitan daños financieros y reputacionales.

## Sección 8: Resolución de Problemas en Redes (10%)

Pregunta de Caso Práctico:<br>
Un usuario informa que no puede acceder a Internet desde su computadora. Describe los pasos que seguirías para identificar y resolver el problema.<br>

___Respuesta___
Primero, verificaría que la computadora esté conectada a la red, comprobando los cables o la conexión Wi-Fi. Luego, revisaría la configuración de red para asegurarse de que la dirección IP esté asignada correctamente. Si el problema persiste, probaría el acceso a Internet desde otro dispositivo para descartar un fallo del proveedor de servicios. También reiniciaría el router o el switch si es necesario. Finalmente, revisaría los registros de la red en busca de errores o bloqueos.

Pregunta de Desarrollo:<br>
Explica la importancia de tener habilidades para la resolución de problemas en redes y cómo estas pueden impactar en la eficiencia y productividad de una organización.<br>

___Respuesta___
Tener habilidades para la resolución de problemas en redes es esencial para garantizar la continuidad operativa de una organización. Cuando surge un problema, una rápida y efectiva resolución minimiza el tiempo de inactividad, evitando interrupciones en el trabajo y manteniendo la productividad alta. Estas habilidades permiten identificar la causa raíz de los problemas y aplicar soluciones adecuadas, lo que reduce la frecuencia de futuros inconvenientes y mejora la eficiencia general de la red.
