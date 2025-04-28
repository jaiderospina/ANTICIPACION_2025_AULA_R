
## Habilitar, Validar, Instalar y Realizar Conexión Remota por SSH en Kali Linux

Este manual te guiará a través de los pasos necesarios para **instalar (si es necesario)**, habilitar, verificar el funcionamiento y conectarte a un servidor SSH en tu máquina Kali Linux de forma remota.

**1. Instalar el Servidor SSH (Si no está instalado):**

Aunque Kali Linux suele incluir el servidor SSH por defecto, en algunas instalaciones minimalistas o personalizadas podría no estar presente. Sigue estos pasos para instalarlo:

   **a. Abrir la Terminal:** Abre una ventana de terminal en tu Kali Linux.

   **b. Actualizar la Lista de Paquetes:** Antes de instalar cualquier software nuevo, es recomendable actualizar la lista de paquetes disponibles en los repositorios:
   ```bash
   sudo apt update
   ```
   Se te pedirá tu contraseña de administrador. Introdúcela y presiona Enter.

   **c. Instalar el Servidor SSH (OpenSSH):** El servidor SSH más común en sistemas Linux es OpenSSH. Utiliza el siguiente comando para instalarlo:
   ```bash
   sudo apt install openssh-server
   ```
   El sistema te preguntará si deseas continuar. Escribe `s` o `yes` y presiona Enter para confirmar la instalación.

**2. Habilitar el Servidor SSH:**

Una vez instalado (o si ya estaba presente), necesitas iniciar y habilitar el servicio SSH:

   **a. Iniciar el Servicio SSH:** Utiliza el siguiente comando para iniciar el servicio SSH:
   ```bash
   sudo systemctl start ssh
   ```

   **b. Habilitar el Servicio SSH al Inicio:** Para que el servicio SSH se inicie automáticamente cada vez que arranques tu sistema, ejecuta el siguiente comando:
   ```bash
   sudo systemctl enable ssh
   ```

**3. Validar que el Servidor SSH esté Funcionando:**

Después de la instalación y el inicio del servicio, verifica que esté corriendo correctamente:

   **a. Verificar el Estado del Servicio:** Utiliza el siguiente comando para comprobar el estado del servicio SSH:
   ```bash
   sudo systemctl status ssh
   ```
   Deberías ver una salida que indique que el servicio está "active (running)".

   **b. Verificar el Puerto de Escucha:** Asegúrate de que el servidor SSH esté escuchando en el puerto predeterminado (22):
   ```bash
   sudo netstat -tuln | grep :22
   ```
   o
   ```bash
   sudo ss -tuln | grep :22
   ```
   Busca una línea similar a `tcp        0      0 0.0.0.0:22              0.0.0.0:* LISTEN` o `tcp        0      0 [::]:22                 [::]:* LISTEN`.

   **c. Verificar la Dirección IP:** Necesitarás la dirección IP de tu máquina Kali Linux para la conexión remota:
   ```bash
   ip a
   ```
   Localiza la interfaz de red activa (por ejemplo, `eth0` o `wlan0`) y anota la dirección IP que aparece junto a `inet`.

**4. Realizar la Conexión Remota por SSH:**

Con el servidor SSH instalado, habilitado y funcionando, puedes conectarte desde otra máquina:

   **a. Abrir una Terminal en la Máquina Remota:** Abre una terminal o símbolo del sistema en el dispositivo desde el que te conectarás.

   **b. Utilizar el Comando SSH:** Ejecuta el siguiente comando, reemplazando los valores según tu configuración:
   ```bash
   ssh usuario@direccion_ip_kali
   ```
   * Sustituye `usuario` con el nombre de usuario de la cuenta en tu Kali Linux a la que deseas acceder.
   * Reemplaza `direccion_ip_kali` con la dirección IP que obtuviste anteriormente.

   **c. Autenticación:**
      * En la primera conexión, recibirás una advertencia sobre la clave del host. Escribe `yes` para aceptarla y la clave se guardará en tu archivo `known_hosts`.
      * Ingresa la contraseña del usuario especificado cuando se te solicite.

   **d. Sesión Remota Establecida:** Si la autenticación es exitosa, verás el prompt de comandos de tu máquina Kali Linux, indicando que la conexión remota se ha establecido correctamente.

**Consideraciones de Seguridad Importantes (Recordatorio):**

* **Cambiar Contraseñas Predeterminadas:** Utiliza `passwd usuario` para cambiar las contraseñas inseguras.
* **Deshabilitar Acceso Root por SSH:** Edita `/etc/ssh/sshd_config` y configura `PermitRootLogin no`. Reinicia el servicio SSH.
* **Utilizar Claves SSH:** Implementa la autenticación por clave pública para una mayor seguridad.
* **Cambiar el Puerto SSH Predeterminado:** Modifica el puerto en `/etc/ssh/sshd_config` y reinicia el servicio. Asegúrate de abrir el nuevo puerto en tu firewall.
* **Configurar un Firewall:** Utiliza `ufw` u otro firewall para controlar el acceso al puerto SSH.

