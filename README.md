# USA Shoes

Tienda web de tenis con pedidos por WhatsApp. Publicada en **https://usa-shoes.github.io**

## Administración
Entra en **https://usa-shoes.github.io/admin/** con tu usuario y contraseña.

Desde ahí puedes:
- Subir fotos de zapatos nuevos y llenar número, marca, modelo, para quién es, estilo, talla, precio y descripción.
- **Centrar la foto** dentro del marco de la tienda: arrastra la foto en el recuadro del editor o usa las dos barras.
- Marcar un modelo como **vendido** u **oferta**.
- **Importar tallas y precios** pegando una tabla: `número, talla, precio` (una línea por zapato).
- **💱 Monedas**: agregar monedas con su tasa (cuántas unidades vale 1 USD) y elegir la que se muestra por defecto. Los precios se escriben siempre en USD; el cliente cambia la moneda arriba, en la cabecera.
- **⭐ Portada**: elegir qué modelos se ven en la portada (lo ideal son 4). Los demás siguen en la tienda completa; si no se marca ninguno, la portada elige sola los primeros disponibles.
- **📣 Cinta**: activar la cinta promocional de la cabecera, con su texto, sus colores y cada cuánto vuelve a pasar.
- En **Ajustes**: el WhatsApp que recibe los pedidos, la **presentación de la tienda** (foto de banner, título, descripción general y modelo destacado) y los usuarios.

Los cambios se guardan al pulsar **Publicar cambios** y se ven en la tienda en 1–2 minutos.

## Archivos
- `index.html` — la portada.
- `tienda.html` — el catálogo completo por categorías (a donde lleva «Ver catálogo»).
- `productos.json` — los datos del catálogo y los ajustes (lo edita la administración).
- `admin/` — la administración. `admin/acceso.json` guarda la llave de GitHub **cifrada** con tu usuario y contraseña.
- `img/` — fotos de los zapatos. `video/` — videos de la portada y las secciones.
