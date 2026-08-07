============================================================
PROYECTO: STAKEHOLDERS Y REQUERIMIENTOS DE SOFTWARE
============================================================

1. DESCRIPCIÓN DEL PROYECTO
------------------------------------------------------------
Este proyecto consiste en un sitio web educativo e interactivo 
que explica de forma clara los conceptos de:
  - Stakeholders (Internos y Externos).
  - Requerimientos Funcionales (RF).
  - Requerimientos No Funcionales (RNF) presentados mediante
    una tabla comparativa detallada.

La página incluye interacciones dinámicas con el usuario mediante 
jQuery, estilos modernos con CSS3, animaciones clave y un indicador 
de tamaño de pantalla que adapta la vista para Celular, Tablet y PC.


2. ESTRUCTURA DE ARCHIVOS
------------------------------------------------------------
/ (Carpeta raíz del proyecto)
  ├── index.html   --> Documento HTML con el contenido estructurado
  ├── styles.css   --> Hoja de estilos, animaciones y diseño responsivo
  └── readme.txt   --> Documento de información del repositorio


3. TECNOLOGÍAS UTILIZADAS
------------------------------------------------------------
  - HTML5: Estructuración de contenido, tablas y navegación.
  - CSS3: 
      * Layouts flexibles (Flexbox)
      * Animaciones (@keyframes bajar y moverderecha)
      * Consultas de medios (@media queries) para diseño adaptativo
  - JavaScript / jQuery (v3.7.1):
      * Ocultar/mostrar imágenes mediante eventos clic (#hide, #show)
      * Eventos hover y clic dinámicos en encabezados (<h2>)


4. CARACTERÍSTICAS Y FUNCIONALIDADES
------------------------------------------------------------
  - Menú de navegación con desplazamiento suave (smooth scroll).
  - Botones de acción para mostrar u ocultar la imagen principal.
  - Títulos <h2> interactivos que cambian de color al pasar el cursor 
    o al hacer clic sobre ellos.
  - Tarjetas de información con sombras y efecto de elevación.
  - Indicador flotante en pantalla que identifica automáticamente si 
    el usuario está navegando desde un celular, tablet o computador.
  - Animación especial de rebote en imágenes para pantallas pequeñas.


5. INSTRUCCIONES DE EJECUCIÓN
------------------------------------------------------------
  1. Descargar o clonar el repositorio.
  2. Abrir el archivo 'index.html' en cualquier navegador web.
  3. Asegurarse de contar con conexión a Internet para la carga 
     de la librería jQuery mediante CDN.

============================================================
