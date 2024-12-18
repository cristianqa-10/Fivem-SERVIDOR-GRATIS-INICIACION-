# 🌟 **FiveM-SERVIDOR GRATIS (INICIACIÓN)**  
📦 Configuración inicial de un servidor **FiveM** totalmente funcional utilizando **QBCore** (versión gratuita). Este proyecto está diseñado para ayudar a los principiantes a configurar y personalizar su servidor de manera sencilla y rápida.

---

## 🎯 **Características principales**  
- 🟢 **Framework QBCore:** Fácil de usar, estable y gratuito.  
- 🟢 **Configuración inicial completa:** Scripts esenciales listos para usar.  
- 🟢 **Personalización:** Base preparada para que agregues tus propios scripts y ajustes según tus necesidades.  
- 🟢 **Guía para principiantes:** Documentación clara y concisa para entender cómo configurar y administrar tu servidor.  

---

## 🛠️ **Requisitos**  
Antes de comenzar, asegúrate de tener lo siguiente:  

1. 🛑 **XAMPP** - Para manejar la base de datos.  
2. 🛑 **HeidiSQL** - Para gestionar la base de datos de tu servidor. *(Por ahora no es necesario crear una base de datos, solo instálalo)*  
3. 🛑 **Visual Studio Code (VSCode)** - Para editar y personalizar los scripts.  
4. 🛑 **FiveM Artifacts** - Archivos base necesarios para ejecutar el servidor.  
   - Descárgalos desde la [página oficial de FiveM](https://runtime.fivem.net/artifacts/fivem/).  
5. 🛑 **Keymaster de FiveM** - Necesaria para registrar y activar tu servidor.  
   - Registra tu servidor en el [FiveM Keymaster](https://keymaster.fivem.net/).  

---

## 🚀 **Cómo iniciar tu servidor**  

### Paso 1️⃣ **Instalar los Server-Artifacts:**
- Descarga los **FiveM Artifacts** desde la [página oficial de FiveM](https://runtime.fivem.net/artifacts/fivem/).
- Una vez descargado el archivo comprimido, descomprímelo.
- **La carpeta `server` ya estará dentro de los archivos descomprimidos**, solo tendrás que moverla a tu carpeta de proyecto principal **FiveM** (por ejemplo, `C:/Usuarios/TuUsuario/FiveM-SERVIDOR`).

### Paso 2️⃣ **Abrir el FXServer:**
- Dentro de la carpeta `server` que moviste, encontrarás el archivo **`FXServer.exe`**. Haz doble clic para iniciar la configuración inicial del servidor.

### Paso 3️⃣ **Configuración inicial:**
Al abrir **FXServer.exe**, se te pedirá que ingreses algunos detalles, como:
- **Contraseña:** Escribe una contraseña para tu servidor.
- **ID de Discord (opcional):** Si deseas, puedes asociar tu servidor con tu cuenta de Discord.
- **Framework:** Selecciona el framework **QBCore** (ya que este proyecto utiliza QBCore).  
- **Recursos a utilizar:** Se te preguntará qué recursos quieres usar. Los recursos recomendados son adecuados, por lo que puedes optar por usarlos (si no tienes preferencia, usa los predeterminados).
- **FiveM Keymaster:** A continuación, te pedirá la **Keymaster** de FiveM.  
   - Ve al [FiveM Keymaster](https://keymaster.fivem.net/) y regístrate o inicia sesión.
   - Registra tu servidor y obtén tu clave (`licenseKey`).
   - Introduce la **clave de licencia** en el campo correspondiente.

### Paso 4️⃣ **Completar la configuración:**
- Una vez completados estos pasos, el servidor terminará la configuración y podrás comenzar a personalizar tu servidor a tu gusto.

---

### 4️⃣ **Configura la base de datos:**  
- Instala y ejecuta **XAMPP**.  
- **HeidiSQL:** Aunque no es necesario crear una base de datos para iniciar el servidor, instala **HeidiSQL** para gestionar la base de datos si es necesario en el futuro.  

### 5️⃣ **Editar las configuraciones:**  
- Abre el archivo `server.cfg` y ajusta las configuraciones principales (nombre del servidor, clave, etc.).  

### 6️⃣ **Iniciar el servidor:**  
Para evitar errores en la consola de **FXServer.exe** al ejecutar el servidor en **localhost**, es **OBLIGATORIO tener **XAMPP** activado**. Cada vez que quieras iniciar o modificar tu servidor, asegúrate de tener **XAMPP** activo y los siguientes servicios iniciados:

1. **MySQL:** Inicia MySQL para gestionar la base de datos de tu servidor.  
2. **Apache:** Inicia Apache para garantizar que los recursos web y conexiones se manejen correctamente.

- Una vez que **XAMPP** esté funcionando, puedes proceder a ejecutar el servidor con el archivo **`start.bat`** o directamente a través de **FXServer.exe**.

### 7️⃣ **Creación de la carpeta txData:**
- Después de completar la instalación y configuración, se creará una carpeta llamada **`txData`** en tu carpeta de servidor.  
- Dentro de esta carpeta, encontrarás varios archivos y configuraciones esenciales para tu servidor. ¡Tu servidor ya está creado y listo para ser utilizado!

### 8️⃣ **Agregar tus propios scripts:**
- El **FXServer.exe** crea automáticamente varios scripts básicos para el funcionamiento inicial del servidor.
- Puedes **agregar tus propios scripts** en la carpeta `resources` de tu servidor.  
- Recuerda que para que tus scripts funcionen correctamente, debes agregar la siguiente línea en el archivo `server.cfg`:
  ```plaintext
  ensure nombre_del_script
