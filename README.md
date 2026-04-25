# MyTeacher — Plataforma de Tutorías Particulares 🚀

**MyTeacher** es una aplicación web interactiva diseñada para conectar a estudiantes con profesores particulares de diversas áreas (Matemáticas, Inglés, Programación, etc.). La plataforma permite explorar perfiles, filtrar resultados por precio o materia, y simular el proceso completo de reserva de una clase.

## 🔗 Enlaces del Proyecto
* **Repositorio GitHub:** [[https://github.com/miguelitox20/myteacher-platform](https://github.com/miguelitox20/myteacher-platform)](https://github.com/miguelitox20/myteacher-platform.git)
* **Demo en vivo (Vercel/Railway):[myteacher-platform.vercel.app](https://myteacher-platform.vercel.app/)

---

## ✨ Características Principales

### 1. Sistema Single Page Application (SPA)
La aplicación funciona en una sola página, gestionando la navegación a través de la manipulación del DOM con JavaScript para mostrar u ocultar secciones (`home`, `search`, `profile`, `booking`, `dashboard`) sin recargar el navegador.

### 2. Búsqueda y Filtrado Dinámico
* **Exploración:** Los usuarios pueden buscar profesores por nombre o materia desde la página de inicio o la sección de exploración.
* **Filtros Avanzados:** Incluye un sidebar de filtros funcionales para ajustar la búsqueda según el precio por hora, modalidad (en línea/presencial) y calificación.

### 3. Perfiles Detallados de Profesores
Cada profesor cuenta con un perfil completo que incluye:
* Biografía y años de experiencia.
* Especialidades específicas y reseñas de otros estudiantes.
* Calendario de disponibilidad visual para Mayo 2025.

### 4. Flujo de Reserva Integrado
* **Cálculo en Tiempo Real:** Al seleccionar la duración de la clase, el sistema calcula automáticamente el subtotal, la comisión de la plataforma y el total a pagar.
* **Confirmación:** Genera un resumen final de la reserva tras simular el pago.

### 5. Panel de Control (Dashboard)
El estudiante dispone de una vista personalizada donde puede ver sus estadísticas de estudio, clases próximas y sus profesores favoritos.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica para todas las vistas de la aplicación.
* **CSS3:** Diseño responsivo utilizando **Flexbox** y **CSS Grid**. Uso de variables modernas para la gestión de colores y sombras.
* **JavaScript (Vanilla):** Lógica de negocio, gestión del estado de la aplicación, filtrado de datos y renderizado dinámico de componentes.
* **Fuentes:** Google Fonts (Syne y DM Sans).

---

## 📂 Estructura de Archivos

```text
├── index.html   # Estructura de las páginas, lógica de JS y datos de profesores.
├── styles.css   # Estilos globales, diseño responsivo y animaciones.
└── README.md    # Documentación del proyecto.
