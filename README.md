# Comparación de Arquitecturas de Datos en Android (Kotlin)

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white)

Proyecto Android para explorar y comparar diferentes enfoques de manejo de datos en aplicaciones móviles. Sirve como referencia de aprendizaje para entender la evolución desde implementaciones sencillas hacia arquitecturas más robustas y los patrones de diseño en Android.

## 📚 Enfoques comparados

- Acceso a datos directamente desde la `Activity` (sin arquitectura)
- Separación con **Repository Pattern**
- Arquitectura **MVVM** con `ViewModel` y `LiveData`

## 🎯 Por qué importa

Cada enfoque tiene implicaciones en:

- **Testabilidad:** facilidad de escribir pruebas unitarias
- **Mantenibilidad:** claridad y organización del código
- **Escalabilidad:** facilidad de agregar nuevas funcionalidades

## 🛠️ Tecnologías

| Tecnología | Uso |
|---|---|
| Kotlin | Lenguaje principal de la aplicación |
| Android SDK | Plataforma de destino |
| Gradle (Kotlin DSL) | Sistema de construcción (`build.gradle.kts`) |
| Android Jetpack | Componentes `ViewModel` y `LiveData` (enfoque MVVM) |

## ✅ Requisitos previos

Antes de ejecutar el proyecto necesitas tener instalado:

- **Android Studio** (versión reciente, con el plugin de Kotlin incluido)
- **JDK 17** (el que trae embebido Android Studio es suficiente)
- **Android SDK** instalado desde el SDK Manager de Android Studio
- Un **emulador Android** configurado en el AVD Manager, o un **dispositivo físico** con la depuración USB activada

## 🚀 Instalación y ejecución

1. Clona el repositorio:

   ```bash
   git clone https://github.com/NinaDIV/Android-Data-Architecture-Comparison.git
   cd Android-Data-Architecture-Comparison
   ```

2. Abre la carpeta del proyecto en **Android Studio** (`File → Open`) y espera a que termine la sincronización de Gradle.

3. Selecciona un emulador o dispositivo físico en la barra superior y presiona **Run ▶** (o `Shift + F10`).

   También puedes compilar desde la terminal:

   ```bash
   # Windows
   gradlew.bat assembleDebug

   # Linux / macOS
   ./gradlew assembleDebug
   ```

4. Al arrancar, la aplicación se instala y se abre en el emulador o dispositivo seleccionado, mostrando los ejemplos de cada enfoque de manejo de datos.
