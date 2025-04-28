## **Taller en Clase**

1. Realizar según las indicaciones de clase el ejercicio desarrollado en:

- https://github.com/SabyasachiRana/WebMap

2. 

**Manual de Nmap: Técnicas y Ejemplos Prácticos**  
*Objetivo de ejemplo: scanme.nmap.org*  

---

### **1. Introducción a Nmap**  

**Nmap** (Network Mapper) es una herramienta de código abierto para exploración de redes y auditorías de seguridad. Permite descubrir dispositivos en una red, identificar puertos abiertos, servicios en ejecución, sistemas operativos y vulnerabilidades. Es utilizado por administradores de redes, pentesters y entusiastas de la ciberseguridad.  

**Nota importante**:  
El sitio `scanme.nmap.org` es un servidor de prueba proporcionado por los desarrolladores de Nmap para experimentar. Evita escanear otros sitios sin autorización explícita, ya que podría ser ilegal.

---

### **2. Técnicas Principales de Nmap**  

#### **2.1 Tipos de Escaneo**  
- **TCP SYN Scan (`-sS`)**:  
  Envía paquetes SYN para determinar puertos abiertos sin completar la conexión. Rápido y sigiloso.  
  *Requiere privilegios de root*.  

- **TCP Connect Scan (`-sT`)**:  
  Completa la conexión TCP (handshake de 3 vías). Útil si no hay permisos de root.  

- **UDP Scan (`-sU`)**:  
  Escanea puertos UDP. Es más lento debido a la falta de respuestas en protocolos UDP.  

- **Escaneo de Ping (`-sn`)**:  
  Descubre hosts activos sin escanear puertos.  

#### **2.2 Detección de Servicios y SO**  
- **Detección de Versiones (`-sV`)**:  
  Identifica la versión de los servicios en puertos abiertos.  

- **Detección de SO (`-O`)**:  
  Determina el sistema operativo del host objetivo.  

#### **2.3 Uso de Scripts (NSE)**  
- **Nmap Scripting Engine (NSE)**:  
  Ejecuta scripts para tareas avanzadas (vulnerabilidades, recolección de información, etc.).  
  Ejemplo: `--script http-title` para obtener el título de una página web.  

#### **2.4 Opciones de Temporización**  
- **Modos de Velocidad (`-T0` a `-T5`)**:  
  Controla la agresividad del escaneo. `-T4` es rápido; `-T1` es sigiloso.  

---

### **3. Ejemplos Prácticos**  
*Objetivo: scanme.nmap.org*  

#### **3.1 Escaneo Básico**  
```bash  
nmap scanme.nmap.org  
```  
- **Resultado**: Muestra puertos abiertos y servicios básicos.  

#### **3.2 Escaneo con Detección de Versiones**  
```bash  
nmap -sV scanme.nmap.org  
```  
- **Detalles**: Identifica versiones de servicios (Ej: Apache 2.4.7).  

#### **3.3 Detección de Sistema Operativo**  
```bash  
sudo nmap -O scanme.nmap.org  
```  
- **Nota**: Requiere permisos de root (`sudo`).  

#### **3.4 Escaneo UDP**  
```bash  
sudo nmap -sU scanme.nmap.org  
```  
- **Uso típico**: Para servicios como DNS o DHCP.  

#### **3.5 Uso de Scripts NSE**  
```bash  
nmap --script http-title scanme.nmap.org  
```  
- **Salida**: Muestra el título de la página web alojada.  

#### **3.6 Escaneo Agresivo**  
```bash  
nmap -A scanme.nmap.org  
```  
- **Combina**: Detección de SO, versiones, scripts comunes y traceroute.  

#### **3.7 Guardar Resultados**  
```bash  
nmap -oN resultado.txt scanme.nmap.org  
```  
- **Formatos**: `-oN` (texto), `-oX` (XML), `-oG` (grepable).  

---

### **4. Mejores Prácticas y Consideraciones Éticas**  
- **Permisos**: Siempre obtén autorización antes de escanear redes ajenas.  
- **Límites**: No abuses de `scanme.nmap.org`. Está destinado a pruebas puntuales.  
- **Legalidad**: Escanear sin consentimiento puede violar leyes como la CFAA (EE.UU.) o GDPR (UE).  

---

### **5. Conclusión**  
Nmap es una herramienta poderosa para diagnóstico de redes y seguridad. Dominar sus técnicas permite identificar riesgos y fortalecer infraestructuras. Úsala con responsabilidad y ética.  

```markdown
# Recursos Adicionales  
- Documentación Oficial: https://nmap.org/docs.html  
- Guía de NSE: https://nmap.org/book/nse.html  
```


3. **Cuestionario sobre Nmap: Técnicas y Uso**  
*(Respuestas al final)*  

---

### **Preguntas**  
1. ¿Qué es Nmap y cuál es su propósito principal?  
2. Describe cómo funciona el **escaneo TCP SYN** (`-sS`) y menciona por qué requiere privilegios de root.  
3. Explica la diferencia entre un **escaneo TCP Connect** (`-sT`) y un **escaneo TCP SYN** (`-sS`).  
4. ¿Por qué el **escaneo UDP** (`-sU`) es considerado más lento que otros tipos de escaneo?  
5. ¿Qué comando usarías para detectar la versión de los servicios en puertos abiertos de un objetivo?  
6. ¿Cómo se realiza la detección del sistema operativo de un host con Nmap? Proporciona un ejemplo de comando.  
7. Menciona dos scripts comunes de **NSE (Nmap Scripting Engine)** y su utilidad.  
8. ¿Qué significa el modo de temporización `-T4` en Nmap y en qué situaciones se recomienda usarlo?  
9. ¿Cómo guardarías los resultados de un escaneo en formato de texto con el nombre `resultado.txt`?  
10. ¿Por qué es importante obtener autorización antes de usar Nmap en una red ajena?  

---
**Nota:**  
- Practica siempre en entornos autorizados (como `scanme.nmap.org`).  
- Revisa la documentación oficial (**https://nmap.org**) para profundizar en técnicas avanzadas.