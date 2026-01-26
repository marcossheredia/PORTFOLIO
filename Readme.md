# 📂 Proyecto: Portfolio Profesional Web

[cite_start]Este repositorio contiene el desarrollo de un **portfolio profesional web**, una herramienta fundamental para perfiles técnicos en el ámbito del desarrollo y diseño web[cite: 3].

[cite_start]El objetivo principal es diseñar y maquetar una interfaz clara, usable y visualmente coherente que muestre perfil, habilidades y trabajos, utilizando **únicamente HTML y CSS**[cite: 4, 5].

---

## 🎯 Objetivos del Proyecto

El proyecto busca aplicar los conocimientos adquiridos en la asignatura para:
* [cite_start]Estructurar documentos HTML usando **etiquetas semánticas**[cite: 7].
* [cite_start]Aplicar estilos CSS de forma organizada, coherente y separada de la estructura[cite: 8, 10].
* [cite_start]Diseñar una interfaz usable, visualmente adecuada y profesional **sin usar JavaScript**[cite: 9, 11].

---

## ⚙️ Requisitos Funcionales

[cite_start]El portfolio puede desarrollarse como una sola página (*landing page*) o múltiples páginas, e incluye los siguientes bloques obligatorios[cite: 13, 18]:

1.  [cite_start]**Inicio** [cite: 14]
2.  [cite_start]**Sobre mí / Perfil** [cite: 15]
3.  [cite_start]**Proyectos / Trabajos** [cite: 16]
4.  [cite_start]**Contacto** (Formulario visual, sin funcionalidad backend) [cite: 17]

---

## 🛠️ Requisitos Técnicos

### HTML (Estructura)
* [cite_start]Uso estricto de **etiquetas semánticas** (`header`, `nav`, `main`, `section`, `footer`)[cite: 20].
* [cite_start]Correcta jerarquía de encabezados, listas y enlaces[cite: 20].
* [cite_start]Inclusión de atributos `alt` en imágenes[cite: 20].

### CSS (Estilo y Maquetación)
* [cite_start]**Archivo externo**: Todo el CSS debe estar en un archivo separado[cite: 22].
* [cite_start]**Layout**: Uso de `flex` o `grid` para la organización de secciones[cite: 27].
* [cite_start]**Posicionamiento**: Uso correcto del modelo de caja, `position` o `display`[cite: 23, 26].
* [cite_start]**Interactividad**: Uso de pseudo-clases (ej. `:hover`) y transiciones/animaciones CSS[cite: 25, 30].
* [cite_start]**Responsive**: Diseño adaptable básico[cite: 29].
* [cite_start]**Buenas prácticas**: Comentarios explicativos en el código[cite: 31].

### 🚫 Restricciones
* [cite_start]**No se permite JavaScript**[cite: 36].
* [cite_start]**No se permiten Frameworks** (Bootstrap, Tailwind, React, etc.)[cite: 36].

---

## 📂 Organización de Archivos

[cite_start]El proyecto sigue una estructura de carpetas clara y ordenada[cite: 34]:

```text
/proyecto-portfolio
├── index.html        # Estructura HTML principal
├── /css
│   └── styles.css    # Hoja de estilos
└── /img              # Imágenes y recursos gráficos