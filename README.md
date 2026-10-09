# Mattea Music

Es una página totalmente visual de un local de venta de discos. Por ahora funciona como catálogo con formulario de contacto: el cliente ve los discos, y si le interesa alguno escribe por el formulario y se coordina la compra por mail.

## Qué tiene la página

- **Inicio:** bienvenida con un fondo en degradado.
- **Productos:** cards de discos con la tapa, el nombre, la banda y el año de lanzamiento.
- **Reseñas:** opiniones de clientes, con una destacada.
- **Contacto:** formulario para consultar por los discos.
- **Menú de navegación:** lista de links que llevan a cada sección de la misma página.

## Qué usé

- **HTML:** estructura semántica con `header`, `nav`, `main`, `section` y `footer`.
- **CSS:** archivo externo `styles.css` con estilos para header, footer y navegación, y propiedades de background (colores y degradado).
- **Flexbox:** para ordenar las cards de productos de forma responsiva.
- **Grid:** para las reseñas y para el layout de contacto.
- **Media Queries:** para que se adapte a tablet y celular.
- **Google Fonts:** *Bebas Neue* para los títulos y *Roboto* para el texto.
- **Formspree:** para que el formulario de contacto envíe los mensajes por mail sin necesitar backend.

## Ideas a futuro

Cuando veamos JavaScript, mi idea es:

- Implementar distintos precios según el estado del disco: usado, nuevo o reacondicionado.
- Distintos formatos: vinilo, CD o cassette, con su precio según cada uno.
- Quizá mostrar una imagen con varios formatos del mismo disco.
- Armar una parte administrativa donde se puedan cargar los discos y que se generen solos con su formato según la imagen.
- Sumar un carrito para que se parezca más a un ecommerce.