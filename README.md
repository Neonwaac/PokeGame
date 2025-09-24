# PokeGames 🎮✨

Este repositorio contiene el desarrollo completo de **Pokegame**, una aplicación móvil creada con **Flutter** inspirada en el universo Pokémon.  
El juego se conecta a la [PokéAPI](https://pokeapi.co/) para obtener datos en tiempo real y ofrece distintos modos de trivia y puntuación.  

## 📂 Estructura del repositorio  

/app_flutter
│
├── lib/
│ ├── components/ → Widgets reutilizables (cards, tiles, buttons, etc.)
│ ├── models/ → Clases de datos (ej. Score)
│ ├── pages/ → Pantallas principales (Home, GuessType, Leaderboard)
│ ├── providers/ → Manejo de estado global con ChangeNotifier
│ ├── services/ → Lógica externa (API, almacenamiento, etc.)
│ ├── themes/ → Colores y configuración de tema (light/dark)
│ └── main.dart → Punto de entrada de la app
│
└── assets/ → Fuentes, imágenes y recursos gráficos


## 🚀 Funcionalidades principales  

- 🎯 **Modos de trivia**:
  - Adivina el Pokémon según su tipo.  
  - Comparaciones entre Pokémon usando sus estadísticas.  
- 🏆 **Leaderboard dinámico** para mostrar puntajes.  
- 🎨 **Diseño estilo pixel-art** con colores personalizados y tipografía `PixelifySans`.  
- 🌙 **Soporte de tema claro/oscuro** con `Provider` + `ChangeNotifier`.  
- ⚡ Animaciones suaves para transiciones y widgets interactivos.  

## 🛠 Tecnologías utilizadas  

- **Mobile:** Flutter  
- **Gestión de estado:** Provider + ChangeNotifier  
- **Diseño:** Figma (prototipos iniciales)  
- **API:** [PokéAPI](https://pokeapi.co/)  

## 📌 Objetivo  

Ofrecer una experiencia divertida y educativa inspirada en Pokémon, con un diseño moderno, dinámico y optimizado para dispositivos móviles.  

---
