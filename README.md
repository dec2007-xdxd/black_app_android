# Portafolio personal en Android

Aplicación móvil desarrollada en Kotlin con Jetpack Compose que presenta información personal, una fotografía de perfil y habilidades relacionadas con el desarrollo de software.

El proyecto se realizó como parte de una evaluación académica para aplicar conocimientos de diseño de interfaces en Android.

## Objetivo

Desarrollar una interfaz de portafolio personal mediante componentes de Jetpack Compose, organizando imágenes, textos y habilidades en una pantalla clara y fácil de utilizar.

## Características

- Imagen de portada en la parte superior.
- Fotografía de perfil con recorte circular.
- Nombre del desarrollador.
- Sección de presentación personal.
- Lista horizontal de habilidades.
- Botón flotante con el símbolo “+”.
- Mensaje Toast al presionar el botón flotante.
- Interfaz con fondo oscuro y elementos redondeados.

## Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| Kotlin | Lenguaje de programación de la aplicación. |
| Jetpack Compose | Construcción de la interfaz mediante funciones componibles. |
| Material Design | Componentes visuales de la interfaz. |
| Android Studio | Desarrollo, compilación y ejecución del proyecto. |
| Gradle | Administración de dependencias y configuración de compilación. |
| Git y GitHub | Control de versiones y almacenamiento del código. |

## Estructura del proyecto

Las rutas siguientes se presentan desde la carpeta raíz del proyecto.

| Ruta | Descripción |
|---|---|
| `app/` | Módulo principal de la aplicación Android. |
| `app/src/main/AndroidManifest.xml` | Declaración de la aplicación y sus componentes. |
| `app/src/main/java/com/example/appmaps/` | Paquete principal del código Kotlin. |
| `app/src/main/java/com/example/appmaps/MainActivity.kt` | Actividad de entrada y composición de la pantalla del portafolio. |
| `app/src/main/java/com/example/appmaps/ui/theme/` | Archivos del tema visual, si se conserva la estructura de la plantilla. |
| `app/src/main/res/drawable/` | Imágenes de portada, fotografía de perfil y recursos gráficos. |
| `app/src/main/res/mipmap-*/` | Recursos del icono de la aplicación. |
| `app/src/main/res/values/` | Recursos como textos, colores y temas XML. |
| `app/build.gradle.kts` | Configuración y dependencias del módulo, si utiliza Kotlin DSL. |
| `README.md` | Descripción e instrucciones del proyecto. |

## Componentes principales

| Componente | Función |
|---|---|
| `Column` | Organiza los elementos verticalmente. |
| `Box` | Permite colocar y superponer elementos. |
| `Image` | Muestra la portada, la fotografía y otros recursos gráficos. |
| `Text` | Presenta el nombre, la descripción y las habilidades. |
| `LazyRow` | Muestra las habilidades con desplazamiento horizontal. |
| `FloatingActionButton` | Proporciona la acción del botón “+”. |
| `Toast` | Muestra un mensaje breve al usuario. |
| `Modifier` | Ajusta tamaños, espacios, fondos y recortes. |

## Requisitos

- Android Studio con soporte para Kotlin y Jetpack Compose.
- Android SDK correspondiente a la configuración del proyecto.
- Conexión a internet para descargar las dependencias iniciales.
- Emulador o dispositivo físico con una versión compatible con el `minSdk` del proyecto.

## Instalación y ejecución

1. Descargar el repositorio o clonarlo mediante Git.
2. Abrir Android Studio y seleccionar **Open**.
3. Elegir la carpeta raíz del proyecto.
4. Esperar a que finalice la sincronización de Gradle.
5. Configurar un emulador o conectar un dispositivo Android con depuración USB.
6. Seleccionar el dispositivo y presionar **Run**.

## Uso

Al iniciar la aplicación se muestra el portafolio personal. El usuario puede consultar la presentación y desplazar horizontalmente la lista de habilidades.

Al presionar el botón flotante “+”, aparece un mensaje Toast.

## Aprendizajes

Durante el desarrollo se practicó la creación de interfaces declarativas, la organización de componentes, el uso de recursos gráficos y el manejo de eventos de clic.

También se aplicaron modificadores para controlar la distribución, los espacios y la apariencia de los elementos.

## Autor

**Diego Omar Espinoza Cuevas**  
Ingeniería en Tecnologías de la Información e Innovación Digital  
Universidad Politécnica de Pachuca  
Grupo: TIID 04_01

## Propósito académico

Proyecto desarrollado con fines educativos como parte de una evaluación de desarrollo de aplicaciones móviles.
