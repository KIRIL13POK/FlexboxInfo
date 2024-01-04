### `align-items`

* ¿Qué hace?

    align-items se utiliza para alinear ítems a lo largo del eje transversal en un contenedor Flexbox. Mientras justify-content maneja la alineación a lo largo del eje principal (horizontal o vertical), align-items se centra en el eje perpendicular a este.

* ¿Cómo se utiliza?

    Los valores comunes para align-items incluyen
    
    + flex-start (alinea los ítems al inicio del eje transversal) 
    + flex-end (al final del eje transversal)
    + center (centra los ítems en el eje transversal) + 
    + baseline (alinea los ítems en base a la línea base del texto contenido en ellos) y stretch (estira los ítems para llenar el contenedor, que es el valor predeterminado).

 + ¿Cuándo es útil?

     Esta propiedad es crucial para controlar cómo se alinean los ítems en situaciones donde su altura es variada o cuando quieres alinearlos de manera específica verticalmente (en un contenedor de fila) o horizontalmente (en un contenedor de columna). Por ejemplo, si tienes una lista de ítems con diferentes alturas y quieres que todos comiencen desde la misma línea superior, usarías align-items: flex-start.