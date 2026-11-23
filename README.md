# The Daily Reel

## Descripción

**The Daily Reel** es un sitio web del proyecto de LMSGI que relaciona el cine con temas de actualidad. Su objetivo es recomendar películas según el tipo de acontecimiento o tema: ciencia y exploración espacial, deporte y tecnología.

El sitio está construido principalmente con **HTML5 y CSS3**. La navegación conecta la página de inicio, el catálogo, las fichas de películas, el formulario de recomendaciones, el contacto y el historial.

## Contenido del sitio

- `index.html`: página de inicio y presentación del proyecto.
- `peliculas.html`: catálogo de películas y enlaces a sus fichas.
- `Interstelar.html`: ficha de *Interstellar*.
- `Moneyball.html`: ficha de *Moneyball*.
- `TheSocialNetwork.html`: ficha de *The Social Network*.
- `pelicula.html`: página de recomendación/detalle de *Interstellar*.
- `formulario.html`: formulario para proponer una película.
- `contacto.html`: información de contacto.
- `historial.html`: tabla con el historial de películas recomendadas.
- `galleria.html`: página de contenido sobre *Interstellar* con imagen adaptable y datos estructurados JSON-LD.

## Estructura de archivos

```text
The Daily Reel/
├── index.html
├── peliculas.html
├── pelicula.html
├── Interstelar.html
├── Moneyball.html
├── TheSocialNetwork.html
├── formulario.html
├── contacto.html
├── historial.html
├── galleria.html
├── reflexion_critica.md
├── tabla decisiones.md
├── galeria_decisones.md
├── historial_borradorV1.html
├── README.md
├── ToDo
├── css/
│   └── estilos.css
├── img/
│   ├── interstelar.jpg
│   ├── interstelar-480w.jpg
│   ├── interstelar-778w.jpg
│   ├── interstelar-1920w.jpg
│   ├── moneyball.jpg
│   └── the-social-network.jpg
├── Evidencias/
│   ├── validador.png
│   ├── accesibilidad_sin_imagenes.png
│   ├── img_desk.png
│   ├── img_mobil.png
│   └── img_tab.png
└── docs/
    └── registre_ia.md
```

## Tecnologías y recursos

- **HTML5** para la estructura y el contenido.
- **CSS3** para los estilos y la adaptación a distintos tamaños de pantalla.
- Elementos semánticos como `header`, `nav`, `main`, `section`, `article` y `footer`.
- Formularios HTML para enviar propuestas de películas.
- Tablas HTML para presentar el historial.
- Imágenes con texto alternativo (`alt`) y, en la página de galería, el elemento `picture` para seleccionar imágenes según el ancho de pantalla.
- JSON-LD en `galleria.html` para describir el artículo y la película.

## Cómo abrir el proyecto

1. Descarga o clona el repositorio.
2. Conserva la estructura de carpetas, especialmente `css/` e `img/`, para que las rutas relativas funcionen.
3. Abre `index.html` en un navegador web. También puedes utilizar la extensión Live Server de Visual Studio Code si está disponible.

No se necesita un proceso de compilación ni instalar dependencias para visualizar las páginas estáticas.

## Accesibilidad y diseño adaptable

El proyecto incluye atributos `alt` en las imágenes de varias páginas, estructura semántica, una tabla con encabezados y estilos de foco, además de reglas CSS para adaptar las imágenes a pantallas pequeñas.

Las comprobaciones de accesibilidad y validación deben realizarse sobre la versión final en el navegador y con las herramientas correspondientes. La presencia de capturas en `Evidencias/` no sustituye la repetición de las pruebas si se modifica el código.

## Documentación adicional

- `reflexion_critica.md`: reflexión sobre la tabla del historial.
- `tabla decisiones.md`: decisiones de estructura y semántica de la tabla.
- `galeria_decisones.md`: decisiones sobre imágenes adaptables, accesibilidad y metadatos.
- `docs/registre_ia.md`: registro del uso de herramientas de IA.

## Limitaciones conocidas

El proyecto es estático: el formulario utiliza `action="#"` y no incluye un servicio de servidor para almacenar o procesar las recomendaciones. La información del catálogo tampoco se actualiza automáticamente con noticias; la relación con la actualidad forma parte del contenido editorial.
