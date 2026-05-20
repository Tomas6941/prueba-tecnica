# Nórdika — Landing Page

Demo de landing page para **Nórdika**, una tienda de muebles de diseño escandinavo.  
Este proyecto es una maqueta estática que representa cómo se vería el sitio una vez funcional.

---

## Estado actual

Este repositorio contiene únicamente la interfaz visual (frontend estático):

- `index.html` — estructura de la página
- `styles.css` — estilos

No hay backend, base de datos ni lógica real implementada. Todo el contenido es de demostración.

---

## Cómo funciona la web (versión funcional)

### Navbar
- El botón **"Ver catálogo"** redirige a la sección de productos o a una página de catálogo completo.
- Los links de navegación hacen scroll suave hacia cada sección de la página.
- En mobile, el ícono de hamburger despliega el menú.

### Hero
- El botón **"Ver catálogo"** lleva al listado de productos.
- La imagen de fondo mostraría una foto real de producto o ambiente.

### Productos destacados
- Cada tarjeta muestra un producto real con foto, nombre, descripción corta y precio.
- El botón **"Agregar al carrito"** añade el producto al carrito de compras del usuario.
- Al hacer clic en la tarjeta (o en el nombre del producto) se abre la página de detalle del producto, con más fotos, descripción completa y opciones (color, material, etc.).

### Contacto (Footer)
- Los links del footer redirigen a secciones internas o páginas separadas.
- Habría un formulario de contacto real conectado a un backend que envía el mensaje por email.

---

## Stack sugerido para la versión funcional

| Capa | Tecnología sugerida |
|---|---|
| Frontend | HTML, CSS, JS — o migrar a React |
| Backend | Flask (Python) o Node.js + Express |
| Base de datos | PostgreSQL o MySQL |
| Autenticación | Flask-Login / JWT |
| Pagos | MercadoPago API |
| Hosting | Vercel (frontend) + Railway o Render (backend) |

---

## Estructura de archivos

```
nordika/
├── index.html
├── styles.css
└── README.md
```

Una vez funcional, la estructura crecería para incluir páginas de detalle de producto, panel de administración para gestionar el catálogo, y la lógica de carrito y checkout.

---

## Autor

Desarrollado por **Tomás** como demo de landing page para cliente.  
GitHub: [Tomas6941](https://github.com/Tomas6941)