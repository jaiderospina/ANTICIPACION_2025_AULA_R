## Modelamiento de Amenazas  **STRIDE**, **PASTA**.

Los métodos de modelado de amenazas STRIDE y PASTA son enfoques utilizados para identificar y mitigar amenazas de seguridad en sistemas y aplicaciones. A continuación, se presenta una descripción de cada método y una tabla comparativa que resalta sus diferencias clave.

### Método STRIDE

STRIDE es un marco de modelado de amenazas que clasifica las amenazas en seis categorías:

1. **Suplantación (Spoofing)**: Impersonar a un usuario o sistema legítimo.
2. **Manipulación (Tampering)**: Modificación no autorizada de datos.
3. **Repudio (Repudiation)**: Negar haber realizado una acción sin evidencia que lo contradiga.
4. **Divulgación de Información (Information Disclosure)**: Exposición de datos sensibles a partes no autorizadas.
5. **Denegación de Servicio (Denial of Service)**: Hacer que un sistema no esté disponible para usuarios legítimos.
6. **Elevación de Privilegios (Elevation of Privilege)**: Obtener privilegios más altos de los previstos.

Este enfoque es útil para identificar amenazas de manera sistemática y permite a los equipos de desarrollo anticipar y preparar defensas contra posibles ataques [[1]](https://www.softwaresecured.com/post/comparison-of-stride-dread-pasta)[[3]](https://www.datasunrise.com/es/centro-de-conocimiento/modelo-de-amenazas-stride/).

### Método PASTA

PASTA (Process for Attack Simulation and Threat Analysis) es un enfoque más complejo y centrado en el riesgo que consta de siete pasos:

1. **Definir el alcance**: Establecer los límites del análisis.
2. **Identificar y enumerar amenazas**: Reconocer las amenazas potenciales.
3. **Identificar vulnerabilidades**: Detectar debilidades en el sistema.
4. **Analizar ataques**: Simular posibles ataques para evaluar su impacto.
5. **Analizar debilidades**: Evaluar las debilidades identificadas.
6. **Correlacionar información**: Relacionar los hallazgos con los objetivos de negocio.
7. **Producir un informe**: Documentar los resultados y recomendaciones.

PASTA se enfoca en alinear la seguridad con los objetivos comerciales y priorizar riesgos basados en su impacto y probabilidad [[1]](https://www.softwaresecured.com/post/comparison-of-stride-dread-pasta)[[2]](https://aptori.dev/blog/stride-vs-pasta-a-comparison-of-threat-modeling-methodologies).

### Tabla Comparativa

| Característica                | STRIDE                                         | PASTA                                         |
|-------------------------------|------------------------------------------------|-----------------------------------------------|
| **Enfoque**                   | Centrado en la clasificación de amenazas       | Centrado en el riesgo y la simulación de ataques |
| **Complejidad**               | Relativamente simple y fácil de implementar    | Más complejo, requiere un proceso detallado   |
| **Número de pasos**           | 6 categorías de amenazas                       | 7 pasos en el proceso                         |
| **Análisis de riesgos**       | Limitado a la identificación de amenazas       | Incluye análisis exhaustivo de riesgos        |
| **Orientación**               | Más técnica y menos centrada en el negocio     | Alineado con los objetivos comerciales         |
| **Uso recomendado**           | Sistemas simples o en fases de diseño          | Sistemas complejos o análisis de riesgos exhaustivos |

### Conclusión

Ambos métodos son valiosos para el modelado de amenazas, pero su elección depende de las necesidades específicas de la organización, la complejidad del sistema y los objetivos de seguridad. STRIDE es adecuado para equipos nuevos o sistemas menos complejos, mientras que PASTA es ideal para organizaciones que requieren un análisis de riesgos más profundo y alineado con los objetivos comerciales [[2]](https://aptori.dev/blog/stride-vs-pasta-a-comparison-of-threat-modeling-methodologies)[[3]](https://www.datasunrise.com/es/centro-de-conocimiento/modelo-de-amenazas-stride/).

---
Learn more:
1. [Software Secured | Comparison of STRIDE, DREAD & PASTA | USA](https://www.softwaresecured.com/post/comparison-of-stride-dread-pasta)
2. [STRIDE vs PASTA - A Comparison of Threat Modeling Methodologies](https://aptori.dev/blog/stride-vs-pasta-a-comparison-of-threat-modeling-methodologies)
3. [Modelo de Amenazas STRIDE](https://www.datasunrise.com/es/centro-de-conocimiento/modelo-de-amenazas-stride/)
4. https://criminologiacorporativa.com/f/la-metodolog%C3%ADa-pasta-priorizando-amenazas-y-vulnerabilidades

## Estudio de Caso: Modelamiento de Amenazas Cibernéticas con STRIDE y Zabbix

### Introducción
Este estudio de caso tiene como objetivo aplicar el modelo STRIDE para identificar y clasificar las amenazas cibernéticas a un sistema de monitoreo de infraestructura basado en Zabbix. A través de este ejercicio, los estudiantes podrán comprender la importancia de la modelización de amenazas y aplicar conocimientos prácticos en ciberseguridad.

### Objetivos de Aprendizaje
* Comprender el modelo STRIDE y sus componentes.
* Identificar las vulnerabilidades potenciales en un sistema de monitoreo como Zabbix.
* Modelar amenazas cibernéticas específicas utilizando STRIDE.
* Proponer medidas de mitigación para las amenazas identificadas.
* Evaluar la efectividad de las medidas de mitigación.

### Desarrollo del Ejercicio

**1. Definición del Sistema:**
   * **Zabbix:** Servidor central, agentes, base de datos y frontend web.
   * **Infraestructura:** Servidores, redes, dispositivos de red.
   * **Usuarios:** Administradores, usuarios con acceso limitado.

**2. Aplicación del Modelo STRIDE:**
   * **Spoofing:** Suplantación de identidad (usuarios, servicios).
   * **Tampering:** Manipulación de datos (modificación de configuraciones, inyección de código).
   * **Repudiation:** Negación de servicio (denegación de responsabilidades).
   * **Information disclosure:** Divulgación de información confidencial (fuga de datos).
   * **Denial of service:** Denegación de servicio (ataques DDoS, DoS).
   * **Elevation of privilege:** Escalada de privilegios (obtener acceso a cuentas con mayores privilegios).

**3. Identificación de Amenazas Específicas:**
   * **Enumerar** las posibles amenazas para cada componente de Zabbix y la infraestructura asociada.
   * **Priorizar** las amenazas según su probabilidad de ocurrencia e impacto potencial.

**4. Proposición de Medidas de Mitigación:**
   * **Controles técnicos:** Firewall, IDS/IPS, autenticación de dos factores, cifrado, etc.
   * **Controles administrativos:** Políticas de seguridad, gestión de acceso, capacitación del personal.
   * **Controles físicos:** Seguridad física de los servidores, control de acceso físico.

**5. Evaluación de las Medidas de Mitigación:**
   * **Efectividad:** ¿Las medidas mitigan las amenazas identificadas?
   * **Impacto:** ¿Cuál es el impacto de las medidas en la disponibilidad, integridad y confidencialidad de los datos?
   * **Costo:** ¿Cuál es el costo de implementación y mantenimiento de las medidas?

### Métricas de Evaluación

1. **Completitud:** ¿Se han identificado todas las amenazas relevantes?
2. **Precisión:** ¿Las amenazas identificadas son precisas y relevantes para el sistema?
3. **Viabilidad:** ¿Las medidas de mitigación propuestas son viables y realistas?
4. **Costo-beneficio:** ¿Las medidas de mitigación proporcionan un retorno de la inversión adecuado?
5. **Claridad y organización:** ¿La presentación del trabajo es clara y organizada?

### Ejemplo de Amenaza y Mitigación

* **Amenaza:** Un atacante puede explotar una vulnerabilidad en el servidor Zabbix para obtener acceso no autorizado a la base de datos y robar información confidencial.
* **Mitigación:**
  * Mantener actualizado el servidor Zabbix y las aplicaciones relacionadas.
  * Implementar un sistema de detección de intrusiones (IDS) para monitorear el tráfico de red y detectar actividades sospechosas.
  * Configurar firewalls para restringir el acceso al servidor Zabbix.
  * Encriptar la base de datos de Zabbix.

#### TALLER EN GRUPO.

Tomar un componente (sistema de información, componente de red, etc) considerado como de alto impacto en su caso de estudio en desarrollo y de manera similar a los anteriorente expuesto aplicar **STRIDE**  para el modelamiento de amenazas  entregar un informe que incluya:

* Identificación de las amenazas.
* Matriz de riesgos (amenaza, probabilidad, impacto, mitigación).
* Diagramas de arquitectura de seguridad.
* Políticas de seguridad propuestas.

**ObjEtivo**.

Este ejercicio permitirá desarrollar habilidades en:
* Análisis de riesgos
* Diseño de soluciones de seguridad
* Aplicación de marcos de trabajo de seguridad

**Desarrollo del Taller:**

1. **Formación de equipos:**
2. **Definición del escenario:** Cada equipo seleccionará un caso práctico de una organización que ha implementado un modelo de trabajo híbrido (por ejemplo, una empresa de tecnología, una institución educativa, etc.).
3. **Análisis de riesgos:** Utilizando el modelo STRIDE los equipos identificarán las principales vulnerabilidades y amenazas a las que se enfrenta la organización en este nuevo entorno de trabajo.
4. **Diseño de controles de seguridad:** Los equipos propondrán controles de seguridad técnicos, administrativos y físicos para mitigar los riesgos identificados  (anaexo A 27001).
5. **Elaboración del informe:** Los equipos elaborarán un informe escrito que incluya:
   * Introducción
   * Descripción del escenario
   * Análisis de riesgos
   * Diseño de controles de seguridad
   * Conclusiones y recomendaciones
   * Referencias bibliográficas

**Condiciones de Entrega:**

* **Formato:** Documento en formato Word o PDF, siguiendo las normas APA 7.
* **Extensión:** Mínimo 1000 palabras, máximo 2000 palabras.
* **Fecha de entrega:** [Fecha límite]
* **Presentación:** Los equipos deberán realizar una presentación oral de 15-20 minutos para exponer sus hallazgos y recomendaciones.

**Rúbrica de Evaluación (Escala del 1 al 5)**

| Criterio | 1 (Insuficiente) | 2 (Suficiente) | 3 (Bueno) | 4 (Muy Bueno) | 5 (Excelente) |
|---|---|---|---|---|---|
| Comprensión del tema | No demuestra comprensión | Comprensión básica | Comprensión adecuada | Demuestra un profundo conocimiento | Demuestra un conocimiento experto |
| Identificación de riesgos | Identifica pocos riesgos | Identifica algunos riesgos relevantes | Identifica la mayoría de los riesgos | Identifica todos los riesgos relevantes y prioriza | Realiza un análisis de riesgos exhaustivo |
| Diseño de controles | Controles propuestos son poco realistas | Controles propuestos son básicos | Controles propuestos son adecuados | Controles propuestos son sólidos y bien justificados | Controles propuestos son innovadores y altamente efectivos |
| Calidad del informe | Informe mal estructurado, con errores gramaticales y ortográficos | Informe estructurado, pero con algunos errores | Informe bien estructurado y conciso | Informe muy bien estructurado, con un lenguaje claro y conciso | Informe excepcional, con un análisis profundo y original |
| Presentación oral | Presentación pobre, falta de claridad | Presentación aceptable, pero con algunas deficiencias | Presentación clara y organizada | Presentación muy buena, con uso efectivo de ayudas visuales | Presentación sobresaliente, con una comunicación clara y persuasiva |
| Cumplimiento de las normas APA | Numerosas faltas de formato | Algunas faltas de formato | Formato generalmente correcto | Formato correcto, pero con algunas pequeñas inconsistencias | Formato impecable, siguiendo estrictamente las normas APA |

**Consideraciones Adicionales:**

* **Herramientas:** Los estudiantes pueden utilizar herramientas como MindMeister para la creación de mapas mentales, Visio para diagramas de flujo y herramientas de análisis de riesgos para facilitar su trabajo.




