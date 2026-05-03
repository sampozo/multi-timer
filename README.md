# MultiTimer - Mobile Application

## Overview
App de temporización múltiple para cocina. Permite gestionar hasta 4 timers simultáneos con alertas de voz en español.

## Technology Stack
- **Framework**: Capacitor 7.x
- **Build Tool**: Vite
- **Target Platforms**: Android (AAB para Play Store, APK para testing)

## Features
- ⏱️ 1 a 4 timers simultáneos
- 🍽️ Nombres personalizados por plato
- 🔊 Alertas de voz en español (femenino)
- 🎨 Diseño dark premium con colores por timer
- 🚀 Inicio/parada individual y global

## Play Store Optimization
- Genera un `AAB` (Android App Bundle) en cada push via GitHub Actions
- Icono adaptativo inyectado automáticamente
- Sin permisos innecesarios

## Build Artifacts
- `MultiTimer-play-store-release`: AAB para subir a Google Play
- `MultiTimer-debug-apk`: APK para instalación directa y testing
