# Comandos de Flexbox en Tailwind CSS

- **`flex` / `inline-flex`**
  - Activa Flexbox en el contenedor.
  - Tailwind: `flex` o `inline-flex`

- **`flex-direction`**
  - Define la dirección de los ítems dentro del contenedor.
  - Tailwind: `flex-row`, `flex-row-reverse`, `flex-col`, `flex-col-reverse`

- **`flex-wrap`**
  - Controla si los ítems deben envolverse o no.
  - Tailwind: `flex-wrap`, `flex-wrap-reverse`, `flex-nowrap`

- **`justify-content`**
  - Alinea los ítems a lo largo del eje principal.
  - Tailwind: `justify-start`, `justify-end`, `justify-center`, `justify-between`, `justify-around`, `justify-evenly`

- **`align-items`**
  - Alinea los ítems en el eje transversal.
  - Tailwind: `items-start`, `items-end`, `items-center`, `items-baseline`, `items-stretch`

- **`flex-flow`**
  - Combinación de `flex-direction` y `flex-wrap`.
  - Tailwind: No hay una clase directa, se maneja combinando clases de `flex-direction` y `flex-wrap`.

## Comandos para los Ítems Flexibles (Flex Items)

- **`order`**
  - Cambia el orden en que aparecen los ítems flexibles.
  - Tailwind: `order-[n]` (donde `[n]` es un número, como `order-1`, `order-2`, etc.)

- **`flex-grow`**
  - Define la capacidad de un ítem para crecer y ocupar espacio disponible.
  - Tailwind: `flex-grow`, `flex-grow-0`

- **`flex-shrink`**
  - Determina cómo el ítem se encoge para adaptarse al espacio disponible.
  - Tailwind: `flex-shrink`, `flex-shrink-0`

- **`flex-basis`**
  - Establece el tamaño inicial de un ítem flexible.
  - Tailwind: Se controla con clases de ancho (`w-`) y margen/padding, no hay una clase específica.

- **`flex`**
  - Propiedad abreviada para `flex-grow`, `flex-shrink` y `flex-basis`.
  - Tailwind: `flex-1`, `flex-auto`, `flex-initial`, `flex-none`

- **`align-self`**
  - Permite a un ítem individual anular la alineación del eje transversal establecida por el contenedor.
  - Tailwind: `self-auto`, `self-start`, `self-end`, `self-center`, `self-stretch`, `self-baseline`


## Clases de Flex Container en Tailwind CSS

- **`flex` / `inline-flex`**
  - Activa Flexbox en un contenedor. `flex` crea un contenedor de bloque, mientras que `inline-flex` crea un contenedor en línea.

- **`flex-row` / `flex-row-reverse` / `flex-col` / `flex-col-reverse`**
  - Define la dirección de los ítems dentro del contenedor. `flex-row` para una fila horizontal, `flex-row-reverse` para una fila en dirección inversa, `flex-col` para una columna vertical, y `flex-col-reverse` para una columna en dirección inversa.

- **`flex-wrap` / `flex-wrap-reverse` / `flex-nowrap`**
  - Controla si los ítems deben envolverse o no. `flex-wrap` permite el envolvimiento en múltiples líneas, `flex-wrap-reverse` envuelve ítems en orden inverso, y `flex-nowrap` mantiene todos los ítems en una sola línea.

- **`justify-start` / `justify-end` / `justify-center` / `justify-between` / `justify-around` / `justify-evenly`**
  - Alinea los ítems a lo largo del eje principal. Varían desde alinear ítems al inicio (`justify-start`), al final (`justify-end`), centrados (`justify-center`), con espacio entre (`justify-between`), alrededor de los ítems (`justify-around`), y espacio uniforme entre y alrededor de los ítems (`justify-evenly`).

- **`items-start` / `items-end` / `items-center` / `items-baseline` / `items-stretch`**
  - Alinea los ítems en el eje transversal. Desde el inicio (`items-start`), al final (`items-end`), al centro (`items-center`), en la línea base del texto (`items-baseline`), o estirados para llenar el contenedor (`items-stretch`).

## Clases de Flex Items en Tailwind CSS

- **`order-[n]`**
  - Cambia el orden de los ítems flexibles. Por ejemplo, `order-1`, `order-2`, etc., para controlar el orden de visualización.

- **`flex-grow` / `flex-grow-0`**
  - Controla la capacidad de un ítem para crecer y llenar el espacio disponible. `flex-grow` permite que el ítem crezca, mientras que `flex-grow-0` lo previene.

- **`flex-shrink` / `flex-shrink-0`**
  - Determina cómo el ítem se encoge para adaptarse al espacio disponible. `flex-shrink` permite el encogimiento, y `flex-shrink-0` lo impide.

- **`self-auto` / `self-start` / `self-end` / `self-center` / `self-stretch` / `self-baseline`**
  - Permite a un ítem individual anular la alineación del eje transversal establecida por el contenedor. Estas clases alinean el ítem individualmente de diferentes maneras.
