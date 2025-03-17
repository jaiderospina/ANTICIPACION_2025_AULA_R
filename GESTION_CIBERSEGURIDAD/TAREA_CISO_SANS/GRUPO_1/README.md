# CISO MIND MAP

## GRUPO 1: CC CABUYA D. – MY LÓPEZ V – MY CRUZ S. – MY TORRES Y.

## Security Operations – SecOps (Security Operations)

Implica la integración de la seguridad de la información y las operaciones de TI para mejorar la colaboración y reducir riesgos, centrándose en la prevención, detección y respuesta a las amenazas cibernéticas.

En este sentido, las SecOps se pueden definir como el conjunto de procesos, tecnologías y equipos especializados diseñados para proteger una organización contra amenazas cibernéticas, minimizar riesgos y responder de manera efectiva a incidentes de seguridad. Se encarga de prevenir, detectar, analizar y responder ante ciberataques o incidentes de ciberseguridad.

### Prevención
![This is an alt text.](/Images/1 SEC OPS - PREVENCIÓN.png "PREVENCIÓN")

Medidas y controles implementados para proteger proactivamente los sistemas de información y los datos contra amenazas, riesgos y vulnerabilidades potenciales, evitando así que ocurran incidentes desde el principio.

#### Protección de Datos:

Una responsabilidad empresarial colectiva que abarca pasos estratégicos y procedimentales para proteger la privacidad, disponibilidad e integridad de los datos sensibles, a menudo utilizada indistintamente con "seguridad de los datos". Ejemplos:

* **Encryption (Cifrado):** El proceso de tomar un mensaje no cifrado (texto plano), aplicarle una función matemática (algoritmo de cifrado con una clave) y producir un mensaje cifrado (texto cifrado).
* **PKI (Public Key Infrastructure):** Una serie de procesos y tecnologías para la asociación de claves criptográficas con la entidad a la que se le han emitido dichas claves.
* **TLS (Transport Layer Security):** Un protocolo criptográfico que proporciona comunicaciones seguras, seguridad en los extremos y privacidad en Internet.
* **Data Loss Prevention (DLP):** Detección y gestión de violaciones de datos, exfiltración o destrucción no deseada de información.
* **Email Security (Seguridad del correo electrónico):** Protección contra ataques como phishing, malware y suplantación de identidad en correos electrónicos.

#### Network Security (Seguridad de la Red):

Protección de los activos de información abordando las amenazas a la información procesada, almacenada y transmitida por sistemas de información interconectados, abarcando tanto los aspectos físicos como lógicos de una red. Ejemplos:

* **Firewall (Cortafuegos):** Un sistema o combinación de sistemas que aplica un límite entre dos o más redes, típicamente formando una barrera entre un entorno seguro y uno abierto como el Internet.
* **IDS – Intrusion Detection System (Sistema de Detección de Intrusos):** Un sistema que inspecciona la actividad de seguridad de la red y del host para identificar patrones sospechosos que puedan indicar un ataque a la red o al sistema.
* **IPS – Intrusion Detection/Prevention System (Sistema de Prevención de Intrusos):** Sistema diseñado no solo para detectar ataques sino también para evitar que los hosts víctimas pretendidos se vean afectados por los ataques.
* **Proxy Filtering (Filtrado Proxy):** Filtrado del tráfico web para bloquear contenido malicioso.
* **VPN-Virtual Private Network (Red Privada Virtual):** Una conexión segura y cifrada que permite que un dispositivo se conecte a una red a través de Internet, lo que permite la transmisión segura de datos, el trabajo remoto y la autenticación, al mismo tiempo que evita escuchas no autorizadas.
* **Security Gateway (Puerta de Enlace Segura):** Un dispositivo que controla, valida y filtra el intercambio de información entre diferentes dominios de seguridad, actuando como un punto central de aplicación de la seguridad.
* **DDoS Protection (Protección ante ataques DDoS):** Medidas para monitorear y/o mitigar ataques de denegación de servicio distribuida.

#### Seguridad de Aplicaciones:

Aspectos de seguridad soportados por la aplicación, principalmente con respecto a los roles o responsabilidades y los rastros de auditoría dentro de las aplicaciones. Ejemplos:

* **Threat Modeling (Modelamiento de Amenazas):** Proceso sistemático de identificación, análisis y mitigación de amenazas potenciales a un sistema o aplicación, centrándose en vulnerabilidades y riesgos para garantizar un diseño y desarrollo seguro.
* **Design Review (Verificación de Diseño):** Un proceso estructurado para evaluar el diseño de los sistemas o procesos de TI, garantizando que cumplan con los requisitos, aborden los riesgos y se alineen con los objetivos del negocio.
* **Secure Coding:** Práctica de desarrollar software que evita deliberadamente la introducción de vulnerabilidades de seguridad, centrándose en la construcción de sistemas sólidos y seguros desde su diseño inicial..
* **Static Analysis (Análisis Estático):** análisis de información que ocurre sobre una base no continua; también conocido como análisis basado en intervalos.
* **Web/App Scanning (Escaneo de aplicaciones o web):** Proceso de utilizar herramientas automatizadas para identificar y evaluar posibles vulnerabilidades en aplicaciones web, ayudando a las organizaciones a mantener la confianza y reputación al mitigar riesgos antes de que sean explotados.
* **WAF (Web Application Firewall):** Una herramienta de seguridad que protege aplicaciones web y API mediante el filtrado, monitoreo y bloqueo del tráfico web malicioso y ataques a la capa de aplicación, como la inyección SQL y el cross-site scripting (XSS).
* **RASP (Runtime Application Self-Protection):** Una tecnología de seguridad, acuñada por Gartner, que se incorpora o vincula a una aplicación o a su entorno de ejecución para controlar la ejecución de la aplicación, detectar y prevenir ataques en tiempo real mediante el monitoreo de los datos internos y el estado de la aplicación.

#### Endpoint Security (Seguridad en los Endpoints):

Protección de dispositivos (endpoints), como computadoras de escritorio, portátiles y dispositivos móviles, que son puntos de acceso a una red empresarial, contra amenazas cibernéticas y actividades maliciosas.

* **Anti-virus:** Aplicación de software desplegada en múltiples puntos en una arquitectura de TI. Está diseñada para detectar y potencialmente eliminar código de virus antes de que se produzcan daños y reparar o poner en cuarentena los archivos que ya han sido infectados.
* **Anti-malware:** tecnología ampliamente utilizada para prevenir, detectar y eliminar muchas categorías de malware, incluyendo virus informáticos, gusanos, troyanos, keyloggers, plug-ins de navegador maliciosos, adware y spyware.
* **HIDS/HIPS (Host Intrusion Detection/Prevention System):** Tipo de solución de ciberseguridad que monitorea los sistemas de TI en busca de signos de actividad sospechosa para detectar comportamientos o patrones inusuales, ya sea de usuarios humanos o aplicaciones, que podrían indicar una brecha de seguridad o un intento de ataque.
* **FIM - File Integrity Monitoring (Monitoreo de Integridad de Archivos):** Un proceso de seguridad que verifica continuamente la autenticidad de sistemas de archivos, componentes del sistema operativo, aplicaciones y bases de datos, comparando archivos críticos con una línea base confiable para detectar manipulaciones, corrupción o modificaciones sospechosas.
* **App Whitelisting:** Una práctica de ciberseguridad que restringe la ejecución de software en un sistema únicamente a aquellas aplicaciones que están explícitamente autorizadas y forman parte de una lista de confianza predefinida.

#### Secure Configurations (Configuraciones Seguras):

Medidas de seguridad implementadas durante la construcción e instalación de hardware, software, servicios y redes para minimizar vulnerabilidades, garantizando que los sistemas funcionen correctamente con las configuraciones de seguridad requeridas y que no sean alteradas por cambios no autorizados.

#### Active Defense (Defensa Activa):

Una respuesta en la que el sistema, ya sea automáticamente o en conjunto con el usuario, bloquea o afecta de otra manera el progreso de un ataque detectado.

#### Patch Management (Gestión de Parches):

Área de la gestión de sistemas que implica la adquisición, prueba e instalación de múltiples parches (cambios de código) en un sistema informático administrado para mantener el software actualizado y, a menudo, para abordar el riesgo de seguridad.

### Detection (Detección)

Proceso de identificar y reportar errores, omisiones, usos o accesos no autorizados, así como detectar y responder a amenazas y vulnerabilidades de ciberseguridad..

#### Log Management (Gestión de Logs):

Registro de los detalles de información o eventos en un sistema organizado de mantenimiento de registros, generalmente secuenciados en el orden en que ocurrieron.

#### SIEM (Security Information and Event Management):

Sistema de software que recopila y agrega datos y eventos de diversos dispositivos de red y recursos en la infraestructura de TI.

#### Continuos Monitoring (Monitoreo Continuo):

Uso de tecnología para automatizar el seguimiento y la validación continua de la efectividad de los controles implementados dentro de una organización, lo que ayuda a agilizar auditorías y mejorar el cumplimiento.

#### Network Security Monitoring (Monitoreo de Seguridad de la Red):

Recopilación y análisis de datos de la red para detectar y responder a amenazas de seguridad, garantizando la integridad y seguridad de la infraestructura de TI de una organización.

#### Netflow Analysis (Análisis de Flujo de Red):

La práctica de utilizar herramientas para monitorear, solucionar problemas e inspeccionar, interpretar y sintetizar en profundidad los datos del flujo de tráfico.

#### Advanced Analytics (Analítica Avanzada):

Uso de algoritmos complejos y técnicas, incluyendo el aprendizaje automático, para analizar datos y obtener conocimientos más allá de la inteligencia empresarial tradicional, permitiendo una toma de decisiones más informada.

#### Threat Hunting (Caza de Amenazas):

Un enfoque proactivo de ciberseguridad en el que los analistas de seguridad buscan e identifican amenazas previamente desconocidas o en curso, a menudo aquellas que han eludido los mecanismos de detección inicial, para fortalecer la postura de seguridad de una organización.

#### Penentration Testing (Pruebas de Penetración):

Un ciberataque simulado que evalúa la seguridad de un sistema, red o aplicación para identificar vulnerabilidades y riesgos potenciales, ayudando a las organizaciones a mejorar su postura de seguridad.

#### Red Team (Equipo Rojo):

Grupo de profesionales capacitados que simulan ciberataques del mundo real, brechas de seguridad y compromisos de seguridad física para evaluar la efectividad de las defensas de una empresa. El equipo rojo identifica vulnerabilidades, debilidades y posibles exploits en los sistemas, redes, aplicaciones y controles de seguridad física de la empresa. A menudo utilizan las mismas tácticas, técnicas y procedimientos que los adversarios del mundo real para proporcionar un entorno de prueba realista.

#### Vulnerability Scanning (Escaneo de Vulnerabilidades):

Proceso automatizado para identificar proactivamente las debilidades de seguridad en una red o sistema individual.

#### Human Sensor (Sensores Humanos):

Uso de la conciencia de los usuarios para detectar amenazas.

#### Data Loss Prevention (Prevención de Pérdida de Datos) - DLP:

Es una disciplina que busca proteger datos confidenciales de robo, pérdida y uso indebido, utilizando estrategias, procesos y tecnologías de ciberseguridad para ello.

#### Security Operation Center (Centro de Operaciones de Seguridad) - SOC:

Es una función centralizada o un equipo responsable de mejorar la postura de la ciberseguridad de una organización y evitar, detectar y responder a las amenazas.

#### Threat Intelligence (Inteligencia de Amenazas):

Información que una organización utiliza para comprender las amenazas que han estado, estarán o están actualmente dirigidas a la organización. Esta información se utiliza para preparar, identificar y prevenir amenazas de seguridad y ciberseguridad que buscan aprovechar recursos valiosos.

#### Threat Information Sharing (Compartición de Información de Amenazas):

Implica el intercambio de información procesable sobre amenazas cibernéticas para ayudar a las organizaciones a mejorar su postura de ciberseguridad y responder de manera efectiva a los incidentes.

#### Industry Partnerships (Asociaciones con la Industria):

Colaboración con otros sectores para mejorar la seguridad.

### Response (Respuesta)

Acciones o estrategias de la organización para gestionar los riesgos identificados y evaluados, abarcando enfoques como la aceptación, evitación, mitigación o transferencia/compartición del riesgo.

#### Incident Handling Plan (Plan de Manejo de Incidentes):

Un documento estratégico que define los procedimientos a seguir cuando ocurre una amenaza cibernética o un incidente de seguridad, detallando los pasos para la detección, respuesta, recuperación y prevención.

#### Breach Preparation (Preparación ante Brechas de Seguridad):

Medidas de respuesta para minimizar daños en caso de intrusión.

#### Tabletop Exercises (Ejercicios de Simulación):

Un ejercicio basado en la discusión, no técnico, en el que los participantes, en un aula o en grupos de trabajo, analizan sus roles y respuestas ante un escenario hipotético de emergencia o crisis, centrándose en la toma de decisiones y la comunicación.

#### Forensic Analysis (Análisis Forense):

El proceso de identificar, preservar, analizar y presentar evidencia digital de manera legalmente aceptable para su uso en investigaciones y procedimientos judiciales.

#### Crisis Management (Gestión de Crisis):

Proceso de identificar y responder a eventos críticos que podrían afectar negativamente a las personas, los bienes o los procesos empresariales de una organización.

#### Breach Communications (Comunicación en Caso de Brechas):

El proceso de comunicar a las partes interesadas, incluidos empleados, clientes y reguladores, sobre una filtración de datos o un incidente de seguridad para garantizar la transparencia, el cumplimiento y minimizar posibles daños.


## PROCESO GENERAL DE RESPUESTA A INCIDENTES

La respuesta a incidentes no es una actividad individual dentro del SOC, esta requiere la integración con otros equipos y funciones del SOC, para obtener soporte y análisis y proveer el estado y reporte, teniendo como base contener el incidente y regresar a operación.

### Componentes Clave:

**1. Aislamiento y Contención (Isolate and Contain Assets):**

Con la finalidad de evitar la propagación de la amenaza en más partes de la red, este paso es crucial para limitar el alcance del incidente y prevenir una mayor propagación, debe establecerse planes claros y ejecutables teniendo en cuenta dos escenarios:

* **Lógico:** Implica acciones como segmentación de redes, deshabilitación de cuentas comprometidas, bloqueo de tráfico malicioso en firewalls, detención de exfiltración de información, ejecución de políticas de sistemas de detección de intrusiones, entre otros (IDS).
* **Física:** Puede requerir el aislamiento de servidores o dispositivos afectados de la red, o incluso el cierre de instalaciones en casos donde la amenaza supere los controles lógicos.

**2. Administración del negocio:**

Es la gestión y administración durante la fase de respuesta y contención, acá es importante la asignación de roles, comunicación con partes interesadas y documentación.

**3.  Erradicación de Problemas:**

Corresponde a la fase de Erradicación, eliminando la causa del incidente, como borrar malware, parchear vulnerabilidades o revocar credenciales comprometidas, adicional puede incluir la corrección de vulnerabilidades explotadas, la restauración de sistemas desde copias de seguridad limpias y la aplicación de parches de seguridad.

Adicional se debe retornar al servicio normal después de que la amenaza ha sido eliminada y se han tomado las medidas necesarias para prevenir una recurrencia. Esto debe hacerse de forma controlada y gradual, con un monitoreo cercano para asegurar que los sistemas sean estables, seguros y que la amenaza no se reproduzca cuando se establezcan medidas de continuidad.

**4. Conexiones externas:**

Se deben tener en cuenta las conexiones externas que se encargan de comunicación a las partes interesadas: Unidades de Negocio (Business Units), Comité Directivo (Steering Committee) y Gerencia (Management):

    4.1. Unidades de Negocio:
    Proporcionan información sobre el impacto del incidente en las operaciones y ayudan a priorizar la restauración de los servicios críticos de la organización.
    4.2. Comité Directivo y Gerencia: 
    Necesitan estar informados del estado del incidente, las acciones tomadas en la contención y el impacto potencial en la organización. De igual forma son responsables de proporcionar los recursos y la autoridad necesarios para la respuesta a incidentes.

### Implicaciones para un CISO:

* Este diagrama proporciona un marco claro para la planificación y ejecución de la respuesta a incidentes.

* Destaca la importancia de la preparación, la comunicación, la colaboración y la mejora continua, teniendo presente la relación con las partes interesadas.

* Un CISO debe asegurarse de que la organización tenga un plan de respuesta a incidentes bien definido, que se realice pruebas periódicas y que el personal esté debidamente capacitado.

### Elementos o actividades necesarias para desarrollar esta estrategia:

* Respuesta a incidentes
* Monitoreo y detección de seguridad (IPS, IDS, SIEM, SOAR)
* Protección y monitoreo de datos (DLP, SOAR)
* Administración de seguridad
* Remediación
* Planificación y hoja de ruta
* Arquitectura e ingeniería del SOC
* Arquitectura e ingeniería de seguridad
* Investigación de amenazas (IOC)
* Soporte de cumplimiento
* Forense digital (Recopilación de evidencia digital – IOC)
* Pruebas de penetración
* Equipos rojos
* Equipos púrpuras
