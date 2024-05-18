# Proyecto Holy Grail

Este proyecto es un ejemplo básico de un layout "Holy Grail" utilizando HTML y CSS. El layout "Holy Grail" es una disposición común en el diseño web, donde hay un encabezado, un pie de página y tres columnas principales en el cuerpo del contenido.

## Contenido

1. [Descripción](#descripción)
2. [Estructura del Proyecto](#estructura-del-proyecto)
3. [Instalación](#instalación)
4. [Uso](#uso)
5. [Licencia](#licencia)

## Descripción

El propósito de este proyecto es proporcionar un ejemplo de cómo estructurar una página web utilizando HTML y CSS para crear un diseño responsivo y limpio. La página incluye:
- Un encabezado con una barra de navegación principal.
- Una columna de navegación secundaria.
- Una sección principal de contenido.
- Una columna adicional para contenido secundario.
- Un pie de página.

## Estructura del Proyecto

El proyecto tiene la siguiente estructura de archivos:

```
/holy-grail
├── index.html
├── styles.css
└── README.md
```

- `index.html`: Contiene la estructura HTML de la página.
- `styles.css`: Contiene los estilos CSS aplicados a la página.
- `README.md`: Este archivo, con la descripción del proyecto y guías de uso.

## Instalación

Para utilizar este proyecto, simplemente clona el repositorio y abre el archivo `index.html` en tu navegador.

```sh
git clone https://github.com/tu-usuario/holy-grail.git
cd holy-grail
open index.html
```

## Uso

Una vez abierto `index.html` en el navegador, podrás ver el layout "Holy Grail" en acción. El archivo CSS proporciona un diseño responsivo que ajusta la disposición de los elementos según el tamaño de la pantalla:

- En pantallas grandes, muestra todas las columnas.
- En pantallas medianas, oculta la última columna de contenido secundario.
- En pantallas pequeñas, apila las columnas en una sola columna vertical.

### Personalización

Puedes personalizar los estilos editando el archivo `styles.css`. Cambia los colores, márgenes, y otros estilos según tus necesidades. Aquí hay algunas secciones clave que podrías querer ajustar:

- **Colores del tema**: Ajusta los colores en el encabezado, pie de página, enlaces y el fondo de la página.
- **Layout y flexbox**: Modifica el comportamiento del layout utilizando las propiedades de flexbox en la clase `.main-wrapper`.
- **Medias queries**: Ajusta las reglas de CSS en las secciones `@media` para cambiar la forma en que el layout responde a diferentes tamaños de pantalla.

## Licencias

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSES para obtener más detalles.