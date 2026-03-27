# 🎵 GrooveVault

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)
![Room](https://img.shields.io/badge/Room-Database-blue?style=for-the-badge)
![Retrofit](https://img.shields.io/badge/Retrofit-Network-red?style=for-the-badge)

## 📖 Descripción General
**GrooveVault** es una aplicación nativa para Android diseñada para melómanos y coleccionistas. Funciona como una bóveda digital integral que permite explorar discografías inmensas, descubrir metadatos musicales profundos y gestionar una colección física personal (vinilos, CDs, casetes) con una arquitectura robusta que funciona totalmente sin conexión a internet.

## ✨ Características Principales
* **Enciclopedia Musical:** Busca y explora discografías completas, lados B y rarezas de bandas como The Smiths o Radiohead consumiendo la API de Discogs.
* **Gestor de Colección Offline:** Añade álbumes a tu inventario físico personal y accede a toda tu colección sin necesidad de conexión a la red.
* **Metadatos y Créditos Detallados:** Consulta información profunda sobre músicos de sesión, estudios de grabación y años de lanzamiento originales.
* **Interfaz Inmersiva (UI/UX):** Colores de interfaz dinámicos que se adaptan a la portada de cada álbum utilizando Palette API de Android, construidos enteramente con vistas clásicas en XML.

## 🛠️ Stack Tecnológico y Arquitectura
Este proyecto demuestra la aplicación de buenas prácticas modernas en el desarrollo Android, utilizando el enfoque tradicional de interfaces basadas en XML.

* **Lenguaje:** Kotlin
* **Arquitectura:** MVVM (Model-View-ViewModel)
* **Interfaz de Usuario (UI):** XML Layouts, Material Design Components, ViewBinding
* **Red:** Retrofit2 y OkHttp para el consumo de la API
* **Persistencia de Datos:** Base de datos Room para una arquitectura *Offline-First*
* **Programación Asíncrona:** Kotlin Coroutines y Flow
* **Carga de Imágenes:** Glide / Coil
* **Inyección de Dependencias:** Dagger Hilt (Opcional/En proceso)

## 🚀 Cómo Empezar

### Requisitos Previos
* Android Studio (Última versión estable)
* JDK 17 o superior
* Una clave de API gratuita de [Discogs Developers](https://www.discogs.com/developers)

### Instalación
1. Clona este repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/GrooveVault.git](https://github.com/tu-usuario/GrooveVault.git)
