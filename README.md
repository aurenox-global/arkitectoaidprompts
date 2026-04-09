
# 🚀 PromptArchitect | Prompts Nivel Arquitecto para Android

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-Modern-e34f26?logo=html5&logoColor=white)]()
[![Vanilla JS](https://img.shields.io/badge/JS-Vanilla-f7df1e?logo=javascript&logoColor=black)]()
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-34d399)]()

> 📱 **20 Prompts profesionales de nivel Arquitecto Senior** para generar aplicaciones Android completas, listas para compilar directamente en tu espacio de trabajo. **Sin necesidad de Android Studio.**

## 🌟 Características

- ✅ **20 Prompts de Nivel Senior** diseñados con arquitectura limpia (MVVM/MVI, Clean Architecture)
- 🔍 **Búsqueda en tiempo real** y filtrado por 20 categorías diferentes
- 📋 **Copiado con un clic** y vista detallada en modal con prompt completo
- 🎨 **UI/UX Moderna**: Glassmorphism, animaciones CSS, tema oscuro, totalmente responsive
- ⚡ **Zero Dependencies**: Un único archivo `index.html` autocontenido y listo para usar
- 📦 **Compilación Directa**: Cada prompt incluye configuración de Gradle Wrapper para generar APK desde terminal

## 🛠️ Tecnologías Utilizadas

| Tecnología | Descripción |
|---|---|
| `HTML5` | Estructura semántica moderna y accesible |
| `CSS3` | Variables CSS, Grid, Flexbox, `backdrop-filter`, animaciones keyframes, media queries |
| `JavaScript (ES6+)` | DOM dinámico, Intersection Observer, Clipboard API, filtros y búsqueda en tiempo real |
| `Font Awesome 6` | Iconografía vectorial profesional |
| `Google Fonts (Inter)` | Tipografía optimizada para interfaces modernas |

## 🚀 Cómo Usar

1. **Clona o descarga** este repositorio
   ```bash
   git clone https://github.com/tu-usuario/prompt-architect-android.git
   cd prompt-architect-android
   ```
2. **Abre el archivo** `index.html` en tu navegador favorito (Chrome, Firefox, Edge, Safari)
3. **Navega** por las categorías o usa la barra de búsqueda para encontrar lo que necesitas
4. **Haz clic** en `Copiar Prompt` y pégalo en tu asistente de IA preferido (Claude 3.5, GPT-4o, Gemini, etc.)
5. **Sigue las instrucciones** generadas por la IA. Cada prompt está diseñado para que el asistente devuelva una estructura de proyecto completa con `gradlew`, listo para ejecutar:
   ```bash
   ./gradlew assembleDebug   # Genera app-debug.apk
   ./gradlew assembleRelease # Genera APK firmado (con keystore)
   ```

## 📐 Arquitectura de los Prompts

Cada prompt está estructurado siguiendo estándares empresariales reales:
```text
📦 Proyecto Android Generado
├── 📁 app/src/main/java/...
│   ├── 📁 data/        (Room, Repositories, Retrofit/Coroutines)
│   ├── 📁 domain/      (Use Cases, Entidades, Contratos)
│   └── 📁 presentation/ (ViewModels, Compose UI, Navigation, StateFlow)
├── 📁 gradle/wrapper/  (Wrapper configurado)
├── 📄 build.gradle.kts (Dependencias exactas y versiones compatibles)
└── 📄 settings.gradle.kts
```
> 💡 **Importante**: "Sin Android Studio" significa que no necesitas abrir el IDE. Solo requieres tener `JDK 17+` y las `Android Command Line Tools` en tu PATH. La IA generará los scripts para compilar directamente desde terminal.

## 🎯 Categorías Incluidas

| Categoría | Stack Principal | Uso Ideal |
|---|---|---|
| 🛒 E-Commerce | Compose, Room, Retrofit | Tiendas, marketplaces, catálogos |
| 💬 Social | Compose, Firebase, CameraX | Redes, comunidades, feeds |
| ❤️ Salud | Health Connect, MPAndroidChart | Fitness, trackers, bienestar |
| 📚 Educación | ExoPlayer, Room | Cursos, e-learning, quizzes |
| 💰 Finanzas | Biometric, Room, Material 3 | Banca digital, presupuestos |
| 🍔 Comida | Google Maps, Firebase | Delivery, restaurantes, reservas |
| ✈️ Viajes | Retrofit, Coroutines | Booking, itinerarios, guías |
| 🎵 Música | Media3, Room | Reproductores, streaming local |
| 📰 Noticias | WorkManager, Retrofit | Agregadores, blogs, feeds RSS |
| ✅ Productividad | MVI, WorkManager | Gestores de tareas, notas, Pomodoro |
| 🎮 Gaming | Canvas API, Coroutines | Mini-juegos, hubs, puzzles |
| ☁️ Clima | Location, Retrofit | Pronósticos, mapas, alertas |
| 📷 Fotografía | CameraX, Bitmap | Editores, filtros, galerías |
| 💬 Chat | WebSocket, Room | Mensajería, foros, soporte |
| 🧘 Meditación | MediaPlayer, Room | Mindfulness, respiración, sonidos |
| 🎬 Streaming | ExoPlayer, Hilt | VOD, series, picture-in-picture |
| 🗺️ Navegación | Google Maps SDK | GPS, rutas, puntos de interés |
| 📅 Calendario | Room, WorkManager | Agendas, recordatorios, sync |
| 🏪 Marketplace | CameraX, Firebase | P2P, ventas, clasificados |
| 🌱 Hábitos | DataStore, Room | Trackers, streaks, gamificación |

## 📸 Vista Previa

![Vista previa de PromptArchitect](https://via.placeholder.com/800x450/1a1a2e/6c5ce7?text=PromptArchitect+UI+Preview)
> 🖼️ Interfaz moderna con filtros dinámicos, modal de prompts y animaciones fluidas. *(Reemplaza con una captura real de tu repositorio)*

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Sigue estos pasos:
1. Haz un fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/nueva-categoria`)
3. Realiza commit (`git commit -m 'feat: agrega prompt de categoría X'`)
4. Push a la rama (`git push origin feature/nueva-categoria`)
5. Abre un Pull Request describiendo los cambios

## 📄 Licencia

Distribuido bajo la licencia [MIT](https://choosealicense.com/licenses/mit/). Consulta `LICENSE` para más información.

## 💡 Notas Importantes

- 🔒 **Privacidad**: Todo se ejecuta localmente en tu navegador. No se envían datos a servidores externos.
- 🤖 **Compatibilidad IA**: Optimizado para Claude 3.5 Sonnet, GPT-4o, Gemini 1.5 Pro y modelos locales (Llama 3, Mistral, Qwen).
- 🛠️ **Requisitos de Compilación**: 
  ```bash
  # Instalación mínima recomendada
  sudo apt install openjdk-17-jdk
  sdkmanager "platform-tools" "platforms;android-34" "build-tools;34.0.0"
  ```
- 📱 **Compatibilidad**: Los prompts están configurados para `minSdk 24` y `targetSdk 34`.

## 📬 Contacto

- 💼 GitHub: [@tu-usuario](https://github.com/tu-usuario)
- 📧 Email: tu-email@ejemplo.com
- 🌐 Web: [tuweb.dev](https://tuweb.dev)

---
⭐ Si te fue útil, ¡dale una estrella al repositorio! `PromptArchitect` está hecho para desarrolladores que quieren ir más rápido, sin sacrificar calidad arquitectónica.
