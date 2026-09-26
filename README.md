# USA Shoes

Tienda web de tenis con pedidos por WhatsApp. Publicada en **https://usa-shoes.github.io**

## Cómo actualizar el catálogo
Todo está en `index.html`, en el bloque **EDITA AQUÍ** (al principio del `<script>`):

- `WHATSAPP` — número que recibe los pedidos (sin + ni espacios).
- `PRODUCTS` — un renglón por modelo:
  - `img`: nombre de la foto en la carpeta `img/` (sin `.jpg`).
  - `sizes`: tallas disponibles, por ejemplo `["36","38½"]`.
  - `price`: precio en USD, o `null` para mostrar «Consultar».
  - `hot:true` pone la etiqueta «Precio especial».

Para agregar un modelo: sube la foto a `img/` (mejor recortada y de unos 1000 px) y añade su renglón. Para quitar uno vendido, borra su renglón.
