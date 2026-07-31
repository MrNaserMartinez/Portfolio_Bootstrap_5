# 🌐 Portfolio de Naser Martinez — Bootstrap 5

## 📌 Objetivo del proyecto

Página de presentación personal desarrollada con **Bootstrap 5**, aplicando **HTML5 semántico**, diseño **responsive** y personalización mediante **CSS propio**.

El objetivo fue aprender a integrar un framework CSS moderno sin perder una identidad visual propia, construyendo el sitio desde cero, sin utilizar plantillas prediseñadas.

---

## 🚀 Cómo ejecutar la página

1. Cloná o descargá este repositorio.
2. Abrí el archivo `index.html` directamente en tu navegador.

   **O**, si utilizás Visual Studio Code, ejecutá el proyecto con la extensión **Live Server** para obtener recarga automática.

3. No es necesario instalar dependencias. Bootstrap 5 y la fuente **Inter** se cargan mediante CDN.

---

## 🧩 Componentes de Bootstrap utilizados

- **Navbar** (`navbar`, `navbar-expand-lg`)
  - Menú principal responsive con botón hamburguesa (`navbar-toggler`) para pantallas menores a **992px**.

- **Grid System** (`container`, `row`, `col-12`, `col-md-*`)
  - Organización del contenido y distribución responsive de la sección de inicio.

- **Cards** (`card`, `card-img-top`, `card-body`, `card-title`, `card-text`)
  - Presentación de los tres proyectos realizados.

- **Buttons** (`btn`, `btn-primary`)
  - Botones para acceder a los repositorios y documentación de los proyectos.

- **List Group** (`list-group`, `list-group-item`)
  - Utilizado en la sección **Sobre mí**.

- **Badges** (`badge`, `rounded-pill`)
  - Utilizados para mostrar las habilidades e intereses.

---

## 🎨 Personalización con CSS

- Uso de **variables CSS** (`:root`) para colores, espaciados y radios de borde reutilizados en todo el sitio.
- Paleta de colores personalizada basada en tonos **morado** y **celeste** sobre un fondo neutro.
- Personalización de Bootstrap sobrescribiendo las variables:

  ```css
  --bs-primary
  --bs-primary-rgb
  ```

  para que botones y badges utilicen automáticamente la identidad visual del sitio sin recurrir a `!important`.

- Implementación de la tipografía **Inter** mediante Google Fonts.
- Espaciado consistente entre secciones utilizando variables CSS.
- Tarjetas con bordes redondeados, sombras y efecto de elevación mediante `transition` y `transform`.
- Desarrollo completo sin utilizar `!important`.

---

## 📱 Capturas de pantalla (Responsive)

### Vista móvil (320px)

![Vista en 320px](https://github.com/user-attachments/assets/3db2f9fc-750b-4e3b-abc0-c34e5951a94d)

### Vista tablet (768px)

![Vista en 768px](https://github.com/user-attachments/assets/6bc6b2c5-eaeb-412a-856b-72c2b757bb26)

### Vista escritorio (1280px)

![Vista en 1280px](https://github.com/user-attachments/assets/eb322737-2d8d-4764-9ed2-c878dfee4e7d)

---

## 🎯 Decisiones de diseño

- Se mantuvo la identidad visual del proyecto original utilizando una combinación de colores morados y celestes, reduciendo la saturación del fondo para conseguir un aspecto más limpio y moderno.
- El **navbar** y el **footer** concentran el color principal de la interfaz, mientras que el contenido utiliza un fondo claro para mejorar la legibilidad.
- Los componentes de Bootstrap fueron personalizados mediante clases propias (`.proyecto`, `.proyecto__titulo`, `.proyecto__descripcion`, etc.) sin modificar el comportamiento base del framework.
- Se incorporó la sección **Contenido audiovisual** como contenido adicional para aportar un toque más personal al portafolio sin afectar los requisitos de la práctica.

---

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3
- Bootstrap 5.3
- Google Fonts (Inter)

---

## 👨‍💻 Autor

**Naser Daniel Martinez Morales**

Estudiante de Ingeniería en Sistemas de Información.
