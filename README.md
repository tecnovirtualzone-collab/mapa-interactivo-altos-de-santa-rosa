# 🌿 Mapa Interactivo - Finca Altos de Santa Rosa

**Un mapa interactivo con avatar flotante y audio guía para tu centro agroturístico.**

---

## 📌 **📁 Estructura del Proyecto**
```
📂 mapa-interactivo-altos-de-santa-rosa/
├── index.html          # Archivo principal del mapa interactivo
├── avatar.png          # Avatar del guía (mascota)
├── entrada.mp3         # Audios guía
├── zona_descanso.mp3
├── lagos.mp3
├── casona.mp3
├── limon.mp3
├── kiosco.mp3
├── cabanas.mp3
├── README.md           # Instrucciones para usar el mapa
└── LICENSE             # Licencia del proyecto
```

---

## 📌 **🚀 ¿Cómo usar el mapa interactivo?**

### **1️⃣ 📥 Descargar el repositorio**
- **Clona el repositorio en tu computador:**
  ```bash
  git clone https://github.com/alejogomez1991/mapa-interactivo-altos-de-santa-rosa.git
  ```

- **O descarga el repositorio como ZIP:**
  - Ve a: [https://github.com/alejogomez1991/mapa-interactivo-altos-de-santa-rosa](https://github.com/alejogomez1991/mapa-interactivo-altos-de-santa-rosa)
  - Haz clic en el botón verde **"Code"** > **"Download ZIP"**.

---

### **2️⃣ 🎨 Configurar el mapa**
1. **Guarda tu avatar** como `avatar.png` en la carpeta del proyecto.
2. **Guarda los audios** que subiste en la misma carpeta (renómbralos si es necesario para que coincidan con los nombres en el código: `entrada.mp3`, `zona_descanso.mp3`, `lagos.mp3`, `casona.mp3`, `limon.mp3`, `kiosco.mp3`, `cabanas.mp3`).

---

### **3️⃣ 🌐 Desplegar en EasyPanel**
1. **Sube la carpeta completa** a EasyPanel:
   - Ve a tu panel de EasyPanel.
   - Selecciona **"Git"** como método de despliegue.
   - Pega la URL del repositorio:
     ```
     https://github.com/alejogomez1991/mapa-interactivo-altos-de-santa-rosa.git
     ```
   - Haz clic en **"Deploy"**.

2. **Configura el dominio** (opcional):
   - Si tienes un dominio personalizado, configúralo en EasyPanel.

---

### **4️⃣ 📱 Usar el mapa en tu web o app**
- **Si usas WordPress:** Instala un plugin como **"HTML Page"** y sube el archivo `index.html`.
- **Si usas React Native:** Usa el código adaptado para móviles (te lo doy si lo necesitas).

---

## 📌 **🎧 Audios Guía**
Los audios están incluidos en la carpeta del proyecto. Si quieres añadir más puntos de interés, edita el array `puntosDeInteres` en el archivo `index.html`.

---

## 📌 **💡 Personalización**
- **Cambiar el avatar:** Reemplaza `avatar.png` con tu propio diseño.
- **Añadir más puntos de interés:** Edita el array `puntosDeInteres` en `index.html`.
- **Cambiar el estilo:** Modifica el CSS en el archivo `index.html`.

---

## 📌 **📜 Licencia**
Este proyecto está bajo la licencia **MIT**. Puedes usarlo, modificarlo y distribuirlo libremente.

---

## 📌 **🔗 Enlaces Útiles**
- [Leaflet.js](https://leafletjs.com/) - Librería para mapas interactivos.
- [EasyPanel](https://easypanel.io/) - Panel de control para desplegar aplicaciones.
- [GitHub](https://github.com/) - Plataforma para alojar repositorios.
