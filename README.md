# USA Shoes

Tienda web de tenis con pedidos por WhatsApp. Publicada en **https://usa-shoes.github.io**

## Administración
Entra en **https://usa-shoes.github.io/admin/** con tu usuario y contraseña.

Desde ahí puedes:
- Subir fotos de zapatos nuevos y llenar número, marca, modelo, para quién es, estilo, talla, precio y descripción.
- Marcar un modelo como **vendido** u **oferta**.
- **Importar tallas y precios** pegando una tabla: `número, talla, precio` (una línea por zapato).
- Cambiar el WhatsApp que recibe los pedidos y tu usuario o contraseña.

Los cambios se guardan al pulsar **Publicar cambios** y se ven en la tienda en 1–2 minutos.

## Archivos
- `index.html` — la tienda.
- `productos.json` — los datos del catálogo (lo edita la administración).
- `admin/` — la administración. `admin/acceso.json` guarda la llave de GitHub **cifrada** con tu usuario y contraseña.
- `img/` — fotos de los zapatos. `video/` — videos de la portada y las secciones.
