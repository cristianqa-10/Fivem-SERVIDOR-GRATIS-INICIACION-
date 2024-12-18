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
2. 🛑 **HeidiSQL** - Para gestionar la base de datos de tu servidor.  
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
- Coloca la carpeta **descomprimida** en la carpeta **`server`** dentro de tu proyecto (por ejemplo, `C:/Usuarios/TuUsuario/FiveM-SERVIDOR`).

### Paso 2️⃣ **Abrir el FXServer:**
- Abre la carpeta `server` de los artifacts.
- Dentro de esa carpeta, haz doble clic en el archivo **`FXServer.exe`** para iniciar la configuración inicial del servidor.

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
- Crea una base de datos con **HeidiSQL** e importa el archivo `.sql` proporcionado.  

### 5️⃣ **Editar las configuraciones:**  
- Abre el archivo `server.cfg` y ajusta las configuraciones principales (nombre del servidor, clave, etc.).  

### 6️⃣ **Iniciar el servidor:**  
Para evitar errores en la consola de **FXServer.exe** al ejecutar el servidor en **localhost**, es **OBLIGATORIO tener **XAMPP** activado**. Cada vez que quieras iniciar o modificar tu servidor, asegúrate de tener **XAMPP** activo y los siguientes servicios iniciados:

1. **MySQL:** Inicia MySQL para gestionar la base de datos de tu servidor.  
2. **Apache:** Inicia Apache para garantizar que los recursos web y conexiones se manejen correctamente.

- Una vez que **XAMPP** esté funcionando, puedes proceder a ejecutar el servidor con el archivo **`start.bat`** o directamente a través de **FXServer.exe**.

### 7️⃣ **Únete a tu servidor:**  
Abre FiveM y conéctate a `localhost` para comenzar a explorar.  

---

## 📖 **Documentación y ayuda**  
En este repositorio encontrarás:  
- 📂 **server.cfg:** Archivo de configuración principal.  
- 📚 **Guía paso a paso:** Documentación para instalar y configurar scripts adicionales.  
- 🔧 **Scripts básicos:** Funciones como policía, mecánico, interacción con vehículos, y más.  

---

## 🔧 **Personalización recomendada**  
- **Trabajos personalizados:** Agrega tus propios trabajos o modifica los existentes.  
- **Scripts avanzados:** Integra recursos adicionales para mejorar la experiencia de los jugadores.  
- **Sistema de oposiciones:** Limita trabajos importantes (como policía) para acceder únicamente mediante oposiciones desde Discord.  

---

## 🤝 **Contribuciones**  
¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto:  
1. Haz un **fork** del repositorio.  
2. Crea una nueva rama para tus cambios.  
3. Envía un **pull request** con tus mejoras.  

---

## 📧 **Contacto y soporte**  
Si necesitas ayuda o tienes alguna sugerencia, no dudes en contactarme.  

---

💻 **Autor:** *TuNombre*  
🔗 **Repositorio:** [GitHub](https://github.com/tuusuario/Fivem-SERVIDOR-GRATIS-INICIACION)

---
