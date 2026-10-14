# Demo · Cine Clase Azul × TaquillApp para Empresas

Demo de una sola página que presenta el beneficio de cine para colaboradores de Clase Azul: folios y códigos de Cinépolis y Cinemex con **más de 50% de descuento**, operado por TaquillApp para Empresas. Mensaje principal: **“El mejor precio para ir al cine, siempre.”**

**Uso offline:** abre `index.html` con doble clic en cualquier navegador. Es un archivo autocontenido (logo, estilos y scripts incluidos); no necesita internet ni servidor.

Incluye: hero, beneficios, cómo funciona, catálogo filtrable (Cinépolis, Cinemex, combos), carrito y compra simulada (acceso de colaborador → pago directo en la plataforma → folios de ejemplo), instrucciones de canje en el cine, calculadora de ahorro, sección TaquillApp para Empresas y preguntas frecuentes.

El pago se presenta siempre como compra directa del colaborador en la plataforma (tarjeta, transferencia o efectivo); no se menciona descuento vía nómina.

**Editar precios:** en `index.html`, busca `const PRODUCTS=[`. `price` es el precio colaborador (catálogo TaquillApp) y `ref` el precio de referencia en taquilla (ilustrativo); el % de descuento se calcula solo (todos > 50%).

`assets/` contiene la flor de Clase Azul con fondo transparente (azul y blanco). Ya va incrustada en el HTML; los colores de marca usados parten del azul del logo (`#0C183E`) con cobalto y blanco porcelana.
