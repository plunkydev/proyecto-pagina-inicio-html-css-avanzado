# Proyecto: Homepage responsiva | The Odin Project

## Descripción

Este repositorio contiene mi solución del proyecto **Homepage** de **The Odin Project**, dentro del curso **Advanced HTML and CSS** de la ruta **Full Stack JavaScript**.

El objetivo del proyecto es construir una página de inicio tipo portafolio, totalmente responsiva, replicando un diseño dado para **desktop, tablet y mobile**, y asegurando que la interfaz se adapte correctamente a tamaños de pantalla entre **320px y 1920px**.

## Objetivo principal

Practicar y consolidar los temas estudiados en **Advanced HTML and CSS**, especialmente:

* diseño responsivo
* media queries
* responsive images
* layout con Flexbox y Grid
* semántica HTML
* accesibilidad
* organización visual de componentes
* uso de iconos, tipografía y jerarquía visual

## Estado del proyecto

### En desarrollo

## Demo

Pendiente.

Cuando el proyecto esté terminado, aquí agregaré:

* **Live preview:** <a href="https://plunkydev.github.io/proyecto-pagina-inicio-html-css-avanzado/">https://plunkydev.github.io/proyecto-pagina-inicio-html-css-avanzado/</a>

* **Repositorio:** `https://github.com/plunkydev/proyecto-pagina-inicio-html-css-avanzado`

---

## Diseño de referencia

El proyecto parte de un brief visual con tres versiones:

* **Desktop**
* **Tablet**
* **Mobile**

La meta no es copiar una web real completa, sino reproducir el layout, la estructura visual y el comportamiento responsivo lo más fielmente posible.

### Secciones principales del diseño

1. **Hero / Presentación personal**

   * imagen destacada
   * nombre
   * bloque “About me”
   * enlaces a redes sociales

2. **My work**

   * tarjetas de proyectos
   * imagen o bloque visual del proyecto
   * nombre del proyecto
   * descripción breve
   * iconos con enlaces

3. **Contact me**

   * texto de contacto
   * dirección
   * teléfono
   * correo
   * redes sociales
   * imagen complementaria

---

## Tecnologías utilizadas

* **HTML5**
* **CSS3**
* **Git**
* **GitHub**

## Enfoque de desarrollo

Este proyecto está siendo construido con un enfoque orientado a:

* escribir **HTML semántico**
* mantener una estructura clara y escalable
* separar contenido, presentación y recursos
* trabajar la responsividad desde una base sólida
* mejorar la accesibilidad desde el inicio

---

## Habilidades del curso aplicadas

Este proyecto sirve como repaso práctico de lo aprendido en el curso.

### 1. Responsive Design

Se busca que el sitio mantenga una composición coherente en móvil, tablet y escritorio.

### 2. Media Queries

Se usarán para adaptar:

* disposición de secciones
* tamaño de imágenes
* espaciados
* número de columnas en la sección de proyectos
* tipografía y alineación

### 3. Natural Responsiveness

Antes de depender de muchos breakpoints, la idea es construir una base flexible usando:

* `max-width`
* `minmax()`
* `auto-fit` o `auto-fill` si aplica
* anchos fluidos
* imágenes flexibles

### 4. Responsive Images

Las imágenes deberán:

* escalar correctamente
* conservar proporciones
* evitar deformaciones
* adaptarse al contenedor

### 5. Semántica HTML

Se priorizará el uso de etiquetas con sentido estructural, según lo que realmente represente cada bloque del diseño. Para este proyecto, lo más seguro es apoyarse en:

* `header` o un contenedor semántico para el bloque principal superior, si funciona como cabecera de la página
* `main`
* `section` para “About me”, “My work” y “Contact me”
* `footer` solo si la parte final cumple función de pie de página del sitio
* encabezados jerárquicos (`h1`, `h2`, `h3`)

### 6. Accesibilidad

Se tendrá en cuenta:

* texto alternativo en imágenes
* contraste suficiente
* enlaces reconocibles
* estructura legible
* navegación clara
* iconos con nombre accesible si funcionan como links

---

## Posible estructura del proyecto

```text
proyecto-pagina-inicio-html-css-avanzado/
├── index.html
├── README.md
├── css/
│   └── styles.css
├── assets/
│   ├── images/
│   └── icons/
└── .gitignore
```

> La estructura puede cambiar a medida que avance el desarrollo.

---

## Plan de trabajo

### Fase 1: Preparación

* [X] crear la estructura base del proyecto
* [X] enlazar HTML y CSS
* [X] organizar carpetas de assets
* [X] reunir imágenes, iconos y fuentes

### Fase 2: Maquetación base

* [X] construir la estructura semántica en HTML
* [X] crear las secciones principales
* [X] ubicar bloques grandes del layout

### Fase 3: Estilos generales

* [X] definir tipografías
* [X] aplicar colores principales
* [X] trabajar espaciado, sombras y jerarquía visual

### Fase 4: Responsividad

* [X] adaptar diseño mobile
* [X] ajustar versión tablet
* [X] pulir desktop
* [X] revisar el comportamiento entre 320px y 1920px

### Fase 5: Accesibilidad y revisión

* [X] revisar semántica
* [X] mejorar textos alternativos
* [X] validar contraste y legibilidad
* [X] comprobar estados hover/focus

### Fase 6: Publicación

* [X] subir versión final a GitHub
* [X] publicar con GitHub Pages
* [X] agregar enlace demo al README

---

## Estrategia de maquetación recomendada

Para desarrollar este proyecto con orden, la estrategia será:

1. construir primero la **estructura HTML completa**
2. maquetar las **secciones grandes** antes de entrar en detalles
3. estilizar de arriba hacia abajo
4. dejar lista una versión funcional inicial
5. después refinar responsividad, tipografía, espaciados e iconografía

---

## Decisiones técnicas previstas

### Layout general

* usar **Flexbox** para alineaciones simples en una dimensión
* usar **Grid** en la galería de proyectos
* limitar el ancho de contenido con contenedores reutilizables

### Sección hero

* superposición visual entre imagen, nombre y tarjeta informativa
* cuidado especial con posiciones, espaciados y escalado entre breakpoints

### Tarjetas de proyecto

* componente reutilizable
* consistencia en alturas, paddings y distribución interna
* adaptación progresiva del número de columnas según viewport

### Contacto

* estructura flexible para pasar de una columna a dos columnas según tamaño de pantalla

---

## Retos del proyecto

Estos son algunos puntos importantes a resolver:

* reproducir correctamente la superposición del bloque superior
* mantener equilibrio visual entre imagen y texto en distintos tamaños
* lograr una cuadrícula responsiva limpia en “My work”
* evitar desbordes o saltos visuales en pantallas intermedias
* conservar legibilidad y buen espaciado en mobile

---

## Checklist de calidad

Antes de dar el proyecto por terminado, debería cumplirse lo siguiente:

* [X] el HTML valida sin errores importantes
* [X] la página se ve bien en mobile, tablet y desktop
* [X] no hay scroll horizontal no deseado
* [X] las imágenes no se deforman
* [X] los enlaces funcionan correctamente
* [X] los iconos tienen propósito claro
* [X] la jerarquía de títulos es correcta
* [X] el contenido es legible en todos los tamaños
* [X] el código CSS está ordenado y es mantenible

---

## Ideas de mejora opcionales

Una vez completada la versión base, se podrían añadir mejoras como:

* animaciones sutiles en hover
* transiciones en tarjetas
* versión con proyectos reales
* enlaces a perfiles reales
* modo oscuro
* mejoras extra de accesibilidad

---

## Lecciones que busco reforzar con este proyecto

Con este proyecto quiero reforzar especialmente:

* cómo convertir un diseño estático en una interfaz real
* cómo decidir entre Grid y Flexbox
* cómo estructurar media queries con criterio
* cómo pensar una interfaz responsiva sin romper el layout
* cómo escribir HTML semántico y CSS más limpio

---

## Créditos

* Proyecto original: **The Odin Project**
* Ruta: **Full Stack JavaScript**
* Curso: **Advanced HTML and CSS**
* Ejercicio: **Project: Homepage**

---

## Autor

### David Rosales

* GitHub: `https://github.com/plunkydev`

---

