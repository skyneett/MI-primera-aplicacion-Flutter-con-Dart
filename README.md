# Cookie Clicker - Flutter App 🍪

Mi primera aplicación Flutter por Luis Hernan Torres Machado.

## 👨‍🏫 Profe, ahora sí está bien!

![Cookie](https://media.giphy.com/media/EKUvB9uFnm2dO/giphy.gif)

Una aplicación simple de "Cookie Clicker" donde puedes hacer clic en una galleta para incrementar el contador.

## Requisitos Previos

Antes de ejecutar este proyecto, asegúrate de tener instalado:

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (versión 3.9.2 o superior)
- [Dart SDK](https://dart.dev/get-dart) (viene incluido con Flutter)
- Un editor de código (VS Code, Android Studio, etc.)
- Un dispositivo o emulador para ejecutar la aplicación

## Instalación y Configuración

Sigue estos pasos para ejecutar el proyecto:

### 1. Clonar el repositorio

```bash
git clone https://github.com/skyneett/MI-primera-aplicacion-Flutter-con-Dart.git
cd MI-primera-aplicacion-Flutter-con-Dart
```

### 2. Instalar las dependencias

Ejecuta el siguiente comando en la raíz del proyecto:

```bash
flutter pub get
```

### 3. Verificar la configuración de Flutter

Asegúrate de que Flutter esté correctamente configurado:

```bash
flutter doctor
```

Resuelve cualquier problema que aparezca (si los hay).

### 4. Ejecutar la aplicación

Para ejecutar la aplicación en un dispositivo conectado o emulador:

```bash
flutter run
```

O si prefieres ejecutarla en modo web:

```bash
flutter run -d chrome
```

## Características

- ✨ Interfaz simple e intuitiva
- 🍪 Galleta clickeable dibujada con widgets nativos de Flutter
- 🔢 Contador de clics
- ➕ Botón flotante para incrementar el contador
- 🎨 Diseño Material con tema personalizado

## Estructura del Proyecto

```
lib/
  └── main.dart          # Archivo principal de la aplicación
```

## Solución de Problemas Comunes

### Error: "The Flutter SDK is not available"
- Asegúrate de haber instalado Flutter correctamente
- Verifica que Flutter esté en tu PATH: `flutter --version`

### Error: "No connected devices"
- Conecta un dispositivo físico con depuración USB habilitada
- O inicia un emulador de Android/iOS
- O ejecuta en modo web: `flutter run -d chrome`

### Error al ejecutar `flutter pub get`
- Verifica tu conexión a internet
- Intenta limpiar la caché: `flutter pub cache repair`

### La aplicación no compila
- Limpia el proyecto: `flutter clean`
- Obtén las dependencias nuevamente: `flutter pub get`
- Intenta ejecutar: `flutter run`

## Recursos de Aprendizaje

Si este es tu primer proyecto Flutter, aquí hay algunos recursos útiles:

- [Lab: Escribe tu primera app Flutter](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Ejemplos útiles de Flutter](https://docs.flutter.dev/cookbook)
- [Documentación oficial de Flutter](https://docs.flutter.dev/)

## Autor

👤 **Luis Hernan Torres Machado**

## Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.
