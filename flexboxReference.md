### Comandos para el Contenedor Padre (Flex Container)
- **`display: flex` o `display: inline-flex`**
  - Activa Flexbox en el contenedor.
- **`flex-direction`**
  - Define la dirección de los ítems dentro del contenedor (horizontal o vertical).
- **`flex-wrap`**
  - Controla si los ítems deben envolverse o no cuando no caben en una sola línea.
- **`justify-content`**
  - Alinea los ítems a lo largo del eje principal (horizontalmente si `flex-direction` es `row`, verticalmente si es `column`).
- **`align-items`**
  - Alinea los ítems en el eje transversal (verticalmente si `flex-direction` es `row`, horizontalmente si es `column`).
- **`flex-flow`**
  - Propiedad abreviada para `flex-direction` y `flex-wrap`.

### Comandos para los Ítems Flexibles (Flex Items)
- **`order`**
  - Cambia el orden en que aparecen los ítems flexibles dentro del contenedor.
- **`flex-grow`**
  - Define la capacidad de un ítem para crecer y ocupar espacio disponible.
- **`flex-shrink`**
  - Determina cómo el ítem se encoge para adaptarse al espacio disponible.
- **`flex-basis`**
  - Establece el tamaño inicial de un ítem flexible.
- **`flex`**
  - Propiedad abreviada para `flex-grow`, `flex-shrink` y `flex-basis`.
- **`align-self`**
  - Permite a un ítem individual anular la alineación del eje transversal establecida por el contenedor.
