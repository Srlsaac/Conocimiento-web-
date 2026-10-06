# Hotel Vista Verde

Página web de un hotel de montaña, hecha con HTML y CSS como práctica de maquetación. Usa estructura semántica y la metodología BEM para nombrar las clases.

## Secciones de la página

- **Encabezado:** título, frase descriptiva, botón de reserva (call-to-action) y menú de navegación.
- **Nuestro hotel:** foto y video de YouTube, uno a cada lado.
- **Características:** tarjetas con ícono, título y descripción.
- **Habitaciones:** tres planes (Sencilla, Doble y Suite) con foto, precio y lista de características. La Doble es el plan destacado.
- **Reserva:** formulario con nombre, correo, fechas y tipo de habitación.
- **Testimonios:** tarjetas con avatar, nombre, cargo y comentario.
- **Pie de página:** información de contacto, enlaces de navegación, redes sociales y copyright.

## Estructura de archivos

```
├── index.html     # estructura de la página
├── style.css      # todos los estilos
├── img/           # fotos, avatares y favicon
└── README.md
```

## Cómo abrirlo

No necesita instalación. Descarga o clona el proyecto y abre `index.html` en el navegador.

## Metodología

- **HTML semántico:** `header`, `nav`, `main`, `section` y `footer`.
- **BEM (Bloque, Elemento, Modificador):** cada componente lleva su propia clase, por ejemplo `tarjeta`, `tarjeta__titulo` y `tarjeta--destacada`.
- **HTML y CSS separados:** ningún estilo está escrito dentro del HTML.

Las decisiones de diseño BEM están justificadas en el documento "Decisiones de diseño BEM: Hotel Vista Verde".

## Paleta de colores

| Color | Código | Uso |
| --- | --- | --- |
| Crema | `#f5f1e8` | Fondo de la página |
| Verde oscuro | `#2f4f3e` | Títulos, botón y pie de página |
| Verde medio | `#6b8f71` | Menú y bordes |
| Dorado | `#c9a24b` | Detalles y efectos al pasar el mouse |

## Autor

Isaac
