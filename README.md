# Crosta — sitio web

Sitio estático (HTML, CSS y JavaScript en un solo `index.html`, fotos en `img/`). No necesita compilación.

## Datos pendientes
Busca `CONFIG` al inicio del script en `index.html`:

```js
var CONFIG = {
  whatsapp: '',   // ej. '50212345678' (código de país + número, sin + ni espacios)
  ...
};
```

Al poner el número, el botón del pedido cambia a "Enviar por WhatsApp" y abre el chat con el pedido escrito.

También están marcados como "Por confirmar" en `index.html`: dirección, horario, teléfono, nombres, ingredientes y precios de las pizzas (arreglo `PIZZAS` en el script).

## Tipografías
Cy Grotesk Wide Bold (títulos) y Neue Regrade (texto), en `fonts/`, recortadas a los caracteres del español. Cy Grotesk es una versión de prueba (Trial): para uso comercial hay que comprar la licencia web.

## Música
`audio/coltrane.webm` (Opus) y `audio/coltrane.m4a` (AAC, respaldo para Safari antiguo) suenan en bucle con fundido de entrada. El personaje de la esquina derecha la pausa y la vuelve a poner. Los navegadores no permiten sonido automático al entrar: empieza con el primer toque, clic o tecla del visitante.
