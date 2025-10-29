🎵 Lunaᛜ Audio DAW

Mini DAW unipista para edición profesional de audio completamente offline.

## ✨ Características

- 🎚️ **Pitch Shifting** - Cambia el tono sin afectar el tempo (±12 semitonos)
- ⚡ **Control de Velocidad** - Ajusta la velocidad de reproducción (0.5x - 2x)
- 📊 **Detector BPM & Tonalidad** - Análisis automático del audio
- 🎨 **Visualización de Onda** - Waveform interactiva clickeable
- 🔁 **Loop & Seek** - Reproduce en loop y salta a cualquier punto
- 💾 **Exportación MP3** - Alta calidad 320kbps
- 🔊 **Normalización** - Optimiza el volumen automáticamente
- 📱 **PWA** - Instalable en Android/iOS/Desktop
- 🌙 **100% Offline** - Sin servidor, privacidad total

## 🚀 Instalación Local

### Opción 1: Python (recomendado)
```bash
# Clona o descarga el proyecto
cd luna-audio-daw

# Levanta servidor local
python -m http.server 8000

# Abre en navegador
# http://localhost:8000
Opción 2: Node.js
npx http-server
Opción 3: VS Code
Instala extensión "Live Server"
Click derecho en index.html
"Open with Live Server"
📱 Instalar como PWA
En Android/Chrome:
Abre la app en Chrome
Menú (⋮) → "Agregar a pantalla de inicio"
Ya tienes tu DAW instalado! 🎉
En iOS/Safari:
Abre en Safari
Botón Compartir → "Agregar a pantalla de inicio"
En Desktop:
Chrome: Icono de instalación en la barra de direcciones
Edge: Menú → Apps → Instalar
🎮 Uso
Cargar Audio - Arrastra o haz click para subir archivo
Ajustar Pitch - Mueve el slider de semitonos (−12 a +12)
Procesar - Click en "⚡ Procesar" para aplicar cambios
Escuchar - Usa los controles de reproducción
Exportar - Guarda tu audio procesado en MP3
⌨️ Atajos de Teclado
Espacio - Play/Pause
Click en onda - Saltar a posición
🛠️ Tecnologías
Web Audio API
Canvas API
Service Workers (PWA)
LameJS (MP3 encoding)
Vanilla JavaScript (sin frameworks)
📋 Roadmap
[x] Pitch shifting con preservación de tempo
[x] Control de velocidad de reproducción
[x] Waveform clickeable
[x] Detector de BPM/Key (básico)
[x] Normalización de volumen
[ ] Ecualizador de 5 bandas
[ ] Reverb y efectos adicionales
[ ] Trim/Recorte de audio
[ ] Procesamiento por lotes
[ ] Espectrograma en tiempo real
[ ] Tema claro/oscuro
🔒 Privacidad
Todo el procesamiento ocurre localmente en tu dispositivo.
Tus archivos de audio nunca se suben a ningún servidor.
📄 Licencia
Uso personal. Creado por Luna para proyectos internos.
Versión: 1.0.0
Última actualización: 2025
---

## 🎯 **Estructura final de tu proyecto:**
luna-audio-daw/
├── index.html          ← El DAW completo
├── manifest.json       ← Configuración PWA
├── service-worker.js   ← Funcionalidad offline
└── README.md          ← Instrucciones
---

## 🚀 **Para usarlo:**

1. **Crea una carpeta** llamada `luna-audio-daw`
2. **Crea los 4 archivos** con el contenido que te di
3. **Abre terminal** en esa carpeta
4. **Ejecuta:** `python -m http.server 8000`
5. **Abre:** `http://localhost:8000`

---

## 📱 **Para GitHub Pages:**

1. Sube los 4 archivos a un repo
2. Ve a Settings → Pages
3. Selecciona branch `main` o `master`
4. ¡Tu DAW estará en `https://tu-usuario.github.io