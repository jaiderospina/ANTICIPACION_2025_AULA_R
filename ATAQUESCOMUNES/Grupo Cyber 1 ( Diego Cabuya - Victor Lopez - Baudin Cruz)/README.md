# Grupo Cyber 1 #

## Participantes 

1. **CC Cabuya Diego**
2. **MY Lopez Victor**
3. **MY Cruz Baudin**
4. **MY Yerson Torres**
   
# Los 8 Principales Ciberataques

En este documento, se analizan los principales tipos de ciberataques que afectan tanto a individuos como a organizaciones. Cada tipo se presenta con una definición, un ejemplo conceptual y un ejemplo real. La información proporcionada tiene como objetivo mejorar la conciencia y comprensión sobre estos riesgos cibernéticos.

## 1. Phishing Attack

### Definición

El phishing es un ataque en el que un adversario intenta engañar a la víctima para que revele información sensible, como contraseñas, números de tarjeta de crédito o credenciales de acceso, haciéndose pasar por una entidad confiable en una comunicación electrónica (Jakobsson & Myers, 2006).

#### Contextualización Definición
![Contextualización de la Definición](Imagenes/Phishing-1024x690.jpg)
Fuente: https://www.infospyware.com/articulos/que-es-el-phishing


### Ejemplo Conceptual

Un atacante envía un correo electrónico falso simulando ser un banco legítimo, solicitando al destinatario que actualice su contraseña en un enlace proporcionado. El enlace lleva a una página web falsa que recolecta las credenciales ingresadas.

### Ejemplo Real

En 2020, un ataque de phishing masivo dirigido a usuarios de Microsoft Office 365 logró capturar miles de credenciales corporativas mediante correos electrónicos que parecían provenir del soporte técnico de Microsoft (CISA, 2020).

## 2. Ransomware

### Definición

El ransomware es un tipo de malware que cifra los datos de la víctima y exige un rescate económico para restaurar el acceso (Kharraz et al., 2015).

#### Contextualización Definición
![Contextualización de la Definición](Imagenes/Ransomeware.png)
Fuente: https://es.statista.com/grafico/9376/como-funciona-un-ransomware/


### Ejemplo Conceptual

Un empleado descarga un archivo adjunto de un correo electrónico que contiene un malware. Este cifra todos los datos del disco duro, mostrando una nota de rescate exigiendo un pago en criptomonedas para liberar los archivos.

### Ejemplo Real

El ataque de ransomware WannaCry en 2017 afectó a más de 200,000 sistemas en 150 países, incluyendo hospitales y empresas, utilizando una vulnerabilidad conocida en Windows (Greenberg, 2017).

## 3. Denial of Service (DoS)

### Definición

Un ataque DoS busca hacer que un servicio en línea no esté disponible sobrecargándolo con tráfico o solicitudes hasta que el sistema colapse (Mirkovic & Reiher, 2004).

#### Contextualización Definición
![Contextualización de la Definición](Imagenes/DoS.png)

Fuente: https://www.spanning.com/blog/denial-of-service-attacks-web-based-application-security-part-7/


### Ejemplo Conceptual

Un servidor web recibe millones de solicitudes simultáneamente desde múltiples fuentes, agotando sus recursos y evitando que los usuarios legítimos accedan al sitio.

### Ejemplo Real

En 2016, un ataque DDoS dirigido contra Dyn, un proveedor de DNS, interrumpió el acceso a sitios populares como Twitter, Netflix y Reddit (Kolias et al., 2017).

## 4. Man-in-the-Middle (MitM)

### Definición

Un ataque MitM ocurre cuando un atacante intercepta y manipula la comunicación entre dos partes sin que estas lo sepan (Conti et al., 2016).

#### Contextualización Definición
![Contextualización de la Definición](Imagenes/man-in-the-middle-diagram.png)
Fuente: https://www.ibm.com/think/topics/man-in-the-middle/

### Ejemplo Conceptual

Un atacante se posiciona entre un usuario y un servidor bancario, interceptando los datos que se envían, como credenciales de inicio de sesión.

### Ejemplo Real

En 2013, cibercriminales usaron ataques MitM para interceptar comunicaciones entre cajeros automáticos y servidores bancarios, robando millones de dólares (Kaspersky Lab, 2014).

## 5. SQL Injection

### Definición

El SQL Injection es un ataque que permite a un atacante ejecutar comandos maliciosos en una base de datos a través de entradas no seguras en aplicaciones web (Halfond et al., 2006).

#### Contextualización Definición
![Contextualización de la Definición](Imagenes/SQLinjection.png)

Fuente: https://www.avast.com/es-es/c-sql-injection

### Ejemplo Conceptual

Un campo de inicio de sesión en una página web no valida adecuadamente las entradas, permitiendo que un atacante ingrese un comando SQL que extrae información confidencial de la base de datos.

### Ejemplo Real

En 2019, un ataque de SQL Injection comprometió más de 20 millones de registros de clientes de la empresa Desjardins, exponiendo nombres, direcciones y datos financieros (Office of the Privacy Commissioner of Canada, 2020).

## 6. Cross-Site Scripting (XSS)

### Definición

El XSS es un ataque que permite a un atacante inyectar scripts maliciosos en páginas web vistas por otros usuarios, comprometiendo sus datos o dispositivos (Kirda et al., 2006).

#### Contextualización Definición
![Contextualización de la Definición](Imagenes/ataque-xxs-blog-hostalia-hosting.jpg)

Fuente: https://www.avast.com/es-es/c-sql-injection/

### Ejemplo Conceptual

Un atacante inserta un script en un foro en línea que captura cookies de sesión de los usuarios que visualizan el mensaje.

### Ejemplo Real

En 2021, se identificaron múltiples vulnerabilidades de XSS en Microsoft Teams que permitían a los atacantes tomar control de cuentas de usuarios (Microsoft Security Response Center, 2021).

## 7. Zero-Day Exploits

### Definición

Los Zero-Day Exploits son ataques que aprovechan vulnerabilidades desconocidas en software antes de que los desarrolladores puedan solucionarlas (Bilge & Dumitras, 2012).

#### Contextualización Definición
![Contextualización de la Definición](Imagenes/zerodayexplot.jpg)
Fuente: Elaboracion propia

### Ejemplo Conceptual

Un atacante descubre una falla en una aplicación de mensajería y la usa para instalar spyware sin conocimiento del usuario.

### Ejemplo Real

En 2021, Microsoft informó que actores maliciosos explotaron vulnerabilidades de día cero en Exchange Server, permitiendo el acceso no autorizado a numerosos servidores a nivel mundial (Microsoft, 2021).

## 8. DNS Spoofing

### Definición

El DNS Spoofing consiste en comprometer el sistema de nombres de dominio para redirigir a los usuarios a sitios falsos sin su conocimiento (Abdullah et al., 2010).

#### Contextualización Definición
![Contextualización de la Definición](Imagenes/DNOSpoofing.png)

Fuente: https://flashstart.com/es/dns-spoofing-que-es-por-que-es-peligroso/

### Ejemplo Conceptual

Un atacante altera registros DNS para que una URL legítima dirija a un sitio web malicioso diseñado para robar información de los usuarios.

### Ejemplo Real

En 2019, el Departamento de Seguridad Nacional de EE. UU. advirtió sobre ataques de secuestro de DNS que comprometían la infraestructura de múltiples organizaciones, redirigiendo el tráfico a sitios maliciosos para robar información sensible (DHS, 2019).

## Referencias
- Abdullah, M., Hussain, S., & Saeed, K. (2010). DNS Spoofing: Attacks and Countermeasures. *International Journal of Computer Applications*. DOI: 10.5120/903-1307
- Bilge, L., & Dumitras, T. (2012). Before We Knew It: An Empirical Study of Zero-Day Attacks in the Real World. *ACM Conference on Computer and Communications Security*. DOI: 10.1145/2382196.2382232
- CISA. (2020). Alert (AA20-302A): Ransomware Activity Targeting the Healthcare and Public Health Sector. Recuperado de [https://us-cert.cisa.gov/ncas/alerts/aa20-302a](https://us-cert.cisa.gov/ncas/alerts/aa20-302a)
- Conti, M., Dragoni, N., & Lesyk, V. (2016). A Survey of Man in the Middle Attacks. *IEEE Communications Surveys & Tutorials*. DOI: 10.1109/COMST.2016.2548421
- DHS. (2019). DHS Warns Federal Agencies of DNS Hijacking Attacks. *SecurityWeek*. Recuperado de [https://www.securityweek.com/dhs-warns-federal-agencies-dns-hijacking-attacks/](https://www.securityweek.com/dhs-warns-federal-agencies-dns-hijacking-attacks/)
- Greenberg, A. (2017). How an Accidental ‘Kill Switch’ Slowed Friday’s Massive Ransomware Attack. *Wired*. Recuperado de [https://www.wired.com/2017/05/accidental-kill-switch-slowed-fridays-massive-ransomware-attack/](https://www.wired.com/2017/05/accidental-kill-switch-slowed-fridays-massive-ransomware-attack/)
- Halfond, W. G., Viegas, J., & Orso, A. (2006). A Classification of SQL Injection Attacks and Countermeasures. *IEEE International Symposium on Secure Software Engineering*. DOI: 10.1109/ISSRE.2006.27
- IBM. (n.d.). Man-in-the-middle (MITM) attacks. Recuperado de https://www.ibm.com/think/topics/man-in-the-middle
- IBM. (n.d.). Injection attacks. Recuperado de https://www.ibm.com/docs/pt/snips/4.6.0?topic=categories-injection-attacks
- IBM. (n.d.). Cross-Site Scripting (XSS) vulnerabilities. Recuperado de https://www.ibm.com/security/learn/cross-site-scripting/
- Jakobsson, M., & Myers, S. (2006). Phishing and Countermeasures: Understanding the Increasing Problem of Electronic Identity Theft. *Wiley-Interscience*. ISBN: 978-0471789622
- Kaspersky Lab. (2014). *Man-in-the-Middle Attacks: An Overview*. Recuperado de [https://www.kaspersky.com/resource-center/threats/man-in-the-middle-attacks](https://www.kaspersky.com/resource-center/threats/man-in-the-middle-attacks)
- Kharraz, A., Arshad, S., Mulliner, C., Robertson, W., & Kirda, E. (2015). Cutting the Gordian Knot: A Look Under the Hood of Ransomware Attacks. *Proceedings of the 12th Conference on Detection of Intrusions and Malware & Vulnerability Assessment*. DOI: 10.1007/978-3-319-20550-2_10
- Kirda, E., Kruegel, C., & Jovanovic, N. (2006). Securing Web Application Code by Static Analysis and Runtime Protection. *World Wide Web Conference*. DOI: 10.1145/1135777.1135785
- Kolias, C., Kambourakis, G., Stavrou, A., & Voas, J. (2017). DDoS in the IoT: Mirai and Other Botnets. *IEEE Computer*. DOI: 10.1109/MC.2017.201
- Microsoft. (2021). HAFNIUM targeting Exchange Servers with 0-day exploits. *Microsoft Security Blog*. Recuperado de [https://www.microsoft.com/en-us/security/blog/2021/03/02/hafnium-targeting-exchange-servers/](https://www.microsoft.com/en-us/security/blog/2021/03/02/hafnium-targeting-exchange-servers/)
- Microsoft Security Response Center. (2021). *CVE-2021-1732: Windows Win32k Elevation of Privilege Vulnerability*. Recuperado de [https://msrc.microsoft.com/update-guide/vulnerability/CVE-2021-1732](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2021-1732)
- Mirkovic, J., & Reiher, P. (2004). A Taxonomy of DDoS Attack and DDoS Defense Mechanisms. *ACM SIGCOMM Computer Communication Review*. DOI: 10.1145/997150.997156
- Office of the Privacy Commissioner of Canada. (2020). Investigation into Desjardins’ compliance with PIPEDA following a breach of personal information between 2017 and 2019. Recuperado de [https://www.priv.gc.ca/en/opc-actions-and-decisions/investigations/investigations-into-businesses/2020/pipeda-2020-005/](https://www.priv.gc.ca/en/opc-actions-and-decisions/investigations/investigations-into-businesses/2020/pipeda-2020-005/)


