# USA Shoes

Tienda web con pedidos por WhatsApp. Publicada en **https://usa-shoes.github.io**

## Administración
La administración **ya no vive en este sitio**: está fuera de GitHub y no es pública. La dirección la tiene el dueño de la tienda.
La llave de GitHub ya no se guarda en el repositorio: queda cifrada en el dispositivo de cada administrador, con su usuario y contraseña.

Desde ahí puedes:
- **Productos**: foto, número, marca, nombre, para quién es, categoría, talla, precio, descripción y color.
  - **Precio anterior** (sale tachado), **unidad** (el par, kg, litro…), **existencias** (vacío = único; 0 = agotado) y **código** interno.
  - **Ficha del producto**: datos extra libres (material, garantía, peso, ingredientes, medidas…) que salen en la ficha del cliente.
- **Centrar la foto** dentro del marco de la tienda: arrastra la foto en el recuadro del editor o usa las dos barras.
- Marcar un producto como **vendido** u **oferta**.
- **Importar tallas y precios** pegando una tabla: `número, talla, precio` (una línea por producto).
- **📂 Categorías**: crear, renombrar, describir y ordenar las categorías; los productos se agrupan en ellas.
- **💱 Monedas**: la moneda base de la tienda (en la que se escriben los precios) y las demás con su tasa. El cliente cambia la moneda arriba, en la cabecera.
- **⭐ Portada**: elegir qué productos se ven en la portada (lo ideal son 4).
- **📣 Cinta**: la cinta promocional de la cabecera, con su texto, sus colores y cada cuánto vuelve a pasar.
- **🕑 Horario**: cerrado, 24 h o por rangos de días y horas, con aviso en la tienda.
- En **Ajustes**: el WhatsApp que recibe los pedidos, la presentación de la tienda (foto de banner, título, descripción y producto destacado), las **palabras de la tienda** y los usuarios.

### Palabras de la tienda (para cualquier negocio)
En Ajustes → «Palabras de la tienda» se cambia cómo se llama todo, y la tienda entera se adapta:
`producto/productos`, `Talla`, `Para`, `Color`, `Marca`.
Ejemplos: una cafetería pone «plato/platos», «Tamaño», «Tipo», «Presentación», «Cocina»; una ferretería «artículo/artículos», «Medida», «Uso», «Acabado», «Fabricante».

Los cambios se guardan al pulsar **Publicar cambios** y se ven en la tienda en 1–2 minutos.

## Archivos
- `index.html` — la portada.
- `tienda.html` — el catálogo completo por categorías (a donde lleva «Ver catálogo»).
- `productos.json` — los datos del catálogo y los ajustes (lo edita la administración).
- `catalogo-usa-shoes.pdf` — el catálogo que se descarga desde la portada.
- `img/` — fotos de los productos. `video/` — videos de la portada y las secciones.
