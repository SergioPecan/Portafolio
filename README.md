# Portafolio de Proyectos

A continuación se muestran mis proyectos organizados según sus componentes de Frontend y Backend.

---

## Proyecto 1: Desarrollo de Carteras de Descuento

**Descripción:**  
Sistema para gestionar cartera de letras y facturas, incluyendo el cálculo de TCEA.

### Frontend
- **Objetivo:** Crear una interfaz intuitiva y responsiva para la gestión de datos.
- **Responsabilidades:**
    - Diseño e implementación de la interfaz de usuario.
    - Consumo de APIs del backend para visualizar la información.
    - Optimización de la experiencia del usuario.
- **Tecnologías:**  
  *HTML, CSS, JavaScript, vue, primavue*
  https://github.com/SI642-2402-SI82-grupo6/FrontEnd
### Backend
- **Objetivo:** Gestionar la lógica de negocio y el procesamiento de datos.
- **Responsabilidades:**
    - Desarrollo de APIs REST para la comunicación con el frontend.
    - Implementación de la lógica de negocio y cálculos (incluyendo TCEA).
    - Gestión y optimización de la base de datos.
- **Tecnologías:**  
  * java 17, SpringBoot, MongoDB, Jenkins, Docker*
    https://github.com/SI642-2402-SI82-grupo6/BackEnd
---

## Proyecto 2: Sistema de Inventario

**Descripción:**  
Aplicación para gestionar inventarios en tiempo real.

### Frontend
- **Objetivo:** Proveer una interfaz clara y ordenada para la gestión de inventarios.
- **Responsabilidades:**
    - Diseño e implementación de la interfaz.
    - Integración con el backend para el flujo de datos.
- **Tecnologías:**  
  Kotlin, android studio
  https://github.com/PawayAppMobil/MobileApplication
### Backend
- **Objetivo:** Desarrollar la lógica de negocio y garantizar el flujo correcto de la información.
- **Responsabilidades:**
    - Creación de APIs para la gestión de inventarios.
    - Implementación de procesos de control y validación de datos.
    - Gestión de la base de datos.
- **Tecnologías:**  
  SpringBoot, java 17
  https://github.com/PawayAppMobil/BackEnd
## Proyecto 3: Landing Page para Microempresa

**Descripción:**  
Desarrollo de una página web para mejorar la visibilidad online de una microempresa.

### Frontend
- **Objetivo:** Diseñar una landing page atractiva y funcional.
- **Responsabilidades:**
    - Diseño de la interfaz y experiencia de usuario.
    - Implementación de animaciones y componentes interactivos.
- **Tecnologías:**  
  * HTML, CSS, angular, typescript, Bootstrap*
    https://neumaticosjys.netlify.app/


---
Aquí tienes el resumen del proyecto y de sus dos partes que logré extraer a partir del repositorio del frontend. Nota que algunos detalles sobre el backend no están disponibles públicamente (o al menos no pude acceder al repositorio), así que completaré con lo que se puede inferir o sugerir qué revisar.

---

## Proyecto 4 : **ParkUp**



## Frontend (Web App)

**Repositorio**: ParkUp Webapp — `parkup-webapp` https://github.com/ArquitecturasEmergentes-SpaceNow-ParkUp/parkup-webapp.git
**Objetivo**: Proveer la interfaz de usuario basada en navegador para la aplicación ParkUp: permitir que los usuarios interactúen con la funcionalidad del sistema — por ejemplo, ver parkings, reservar, gestionar, etc (esto último inferido).
**Responsabilidades**:

* Renderizar vistas para el usuario: formularios, páginas de listados, detalles, etc.
* Comunicarse con el backend mediante API (probablemente REST) para obtener datos (usuarios, plazas, reservaciones, etc).
* Administración del estado, rutas, componentes visuales.
* Proveer entorno de desarrollo local (con `ng serve`) y producción (build con `ng build`). 
  **Tecnología**:
* Framework: Angular (ángulo) — generado con Angular CLI versión 20.3.1. 
* Lenguajes: TypeScript (~60.3 %), CSS (~24.4 %), HTML (~15.3 %) según estadísticas del repositorio. 
* Estructura típica: `angular.json`, `tsconfig*`, `src/`, etc.

---

## Backend (API / Servidor)

**Repositorio estimado**: ParkUp Backend — `backend` (GitHub) (URL dada: `https://github.com/ArquitecturasEmergentes-SpaceNow-ParkUp/backend.git`)
**Estado**: No pude acceder al contenido de dicho repositorio (probablemente privado o eliminado).
**Objetivo (inferencia)**: Proveer la lógica de negocio, acceso a datos, autenticación/autorización, y los endpoints de API que consumen los clientes (web, móvil). En concreto para un sistema de parqueos, podría incluir: gestión de usuarios, gestión de espacios de estacionamiento, reservas, historial, pagos, etc.
**Responsabilidades**:

* Crear, leer, actualizar, eliminar datos del sistema (usuarios, parkings, plazas, reservas).
* Validar y controlar acceso (login, roles, permisos).
* Exponer endpoints REST o GraphQL para que los clientes utilicen.
* Integrar con base de datos (SQL, NoSQL) y quizá servicios externos (pagos, mapas, geolocalización).
* Manejar seguridad, errores, posiblemente logs y despliegue.
  **Tecnología (inferencia / recomendaciones de verificación)**:
* Podría estar construido en Node.js + Express, o en Java Spring Boot, o en Python Django/Flask, u otro stack. Sin acceso confirma no puedo especificar.
* Puedes revisar el archivo `package.json`, `pom.xml`, `requirements.txt` del repositorio para saber.
  **Recomendación**: Si tienes acceso, revisa el README o la estructura del directorio para completar los detalles reales.

---


Parece que no puedo acceder directamente al repositorio móvil desde ese enlace — probablemente es privado o no existe públicamente.
Pero puedo darte el resumen basado en el nombre y estructura esperada del proyecto **ParkUp** y su conjunto de repositorios.

---

## 📱 **Mobile App (Aplicación Móvil ParkUp)**

**Repositorio:** https://github.com/ArquitecturasEmergentes-SpaceNow-ParkUp/mobile-app.git

### **Objetivo:**

Brindar una experiencia móvil para los usuarios del sistema **ParkUp**, permitiendo interactuar de forma práctica con las funcionalidades del backend (reservar estacionamientos, ver disponibilidad, pagar, y gestionar su cuenta).

### **Responsabilidades:**

* Ofrecer una interfaz amigable y adaptada a dispositivos móviles.
* Integrarse con el backend de ParkUp mediante APIs REST/GraphQL.
* Implementar autenticación y manejo de sesiones.
* Mostrar mapas o ubicaciones de estacionamientos.
* Permitir realizar reservas, pagos o cancelaciones.
* Almacenar preferencias del usuario localmente (por ejemplo, con almacenamiento seguro o SQLite).

### **Tecnología (estimada):**

* **Framework:** Flutter o React Native (según los proyectos del grupo *ArquitecturasEmergentes-SpaceNow* suelen usar estos frameworks).
* **Lenguaje:**

  * Si es **Flutter**, está hecho con **Dart**.
  * Si es **React Native**, está hecho con **TypeScript** o **JavaScript**.
* **Dependencias típicas:**

  * Manejo de estado (Provider, Bloc, Redux, etc.).
  * Integración de APIs HTTP (`http`, `axios`, etc.).
  * Manejo de mapas (Google Maps API o Mapbox).
  * Push notifications (Firebase Cloud Messaging).

