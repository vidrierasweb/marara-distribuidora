<p align="center">
  <img src="img/logo-marara-nav.webp" width="120" alt="Logo de Marara Distribuidora">
</p>

<h1 align="center">Marara Distribuidora</h1>

<p align="center">Catálogo online de productos gastronómicos, con pedidos por WhatsApp.</p>

<p align="center">
  <a href="https://vidrierasweb.github.io/marara-distribuidora/"><strong>Ver el catálogo</strong></a>
</p>

## Qué ofrece

- **Catálogo con fotos:** quesos, fiambres, harinas, aceites, conservas, dulces, lácteos y más, con filtros por categoría y buscador.
- **Pedido por WhatsApp:** el cliente arma el carrito y el mensaje sale listo para enviar al +54 9 11 5155-9466.
- **Ofertas destacadas:** incluye ofertas por cantidad, que el carrito aplica solo.
- **Productos por peso:** se marcan como "a confirmar por peso" y no suman al total estimado.
- **Adaptado al celular:** funciona en teléfono, tablet y computadora.

## Cómo está hecho

Es un sitio estático, sin frameworks ni dependencias que instalar:

| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | La página completa, con los datos del catálogo en un bloque JSON |
| `img/` | Fotos de productos y logo, en WebP |
| `og-image.jpg` | Imagen que aparece al compartir el link |
| `apple-touch-icon.png` | Ícono para la pantalla de inicio del celular |

Se publica con GitHub Pages desde la rama `main`. Para probarlo en tu computadora:

```bash
python3 -m http.server 8000
```

Y abrí `http://localhost:8000`.

---

Hecho por [Vidrieras Web](https://github.com/vidrierasweb).
