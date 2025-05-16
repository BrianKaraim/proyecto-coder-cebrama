# Proyecto Coder

Este archivo fue creado con el objetivo de explicar cómo apliqué los conocimientos adquiridos en clase.

En el archivo index.html, utilicé Flexbox principalmente para estructurar la página. En el main, implementé componentes de Bootstrap, como el carrusel y un botón desplegable para las categorías, que se muestran en dispositivos pequeños. En el footer, utilicé CSS Grid para la disposición de los elementos.

Tanto en login.html como en register.html, empleé Bootstrap para asegurar que el contenido se ajuste al 100% del alto de la página, ya que, por alguna razón, no lo hacía de forma automática.

Además, apliqué efectos en los botones de carrito de compras y en el botón desplegable para mejorar la interacción y la experiencia de usuario.

Todos los html son responsive.

Siguiendo con lo aprendido, apliqué Sass de la siguiente manera:

Creé un archivo principal llamado style.scss, que se encarga de los estilos generales del sitio y está asociado principalmente a la página de inicio (index).
Además, generé archivos .scss individuales para cada una de las demás páginas HTML del sitio:
stylelogin.scss para la página de login
styleproductdetail.scss para la página de detalle de producto
styleregister.scss para la página de registro
Luego, compilé todos los archivos .scss a archivos .css, que se encuentran en la carpeta public/css/, listos para ser utilizados por el navegador.

Cada uno de estos archivos SCSS utiliza una estructura organizada en subcarpetas:

base/: contiene el reset.
layout/: incluye el header, main, footer y media queries del index. También contiene los estilos del login, registro y detalle de producto. Decidí ubicar estos archivos aquí ya que contienen bloques de código extensos relacionados con la estructura.
components/: incluye estilos para componentes como la card, el carrusel, la navbar del header y una media query del login (por ser un archivo más corto).
utilities/: contiene variables y mixins.
