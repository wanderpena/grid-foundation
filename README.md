Aquí están las características principales:

## Variables de Configuración

- **`$grid-system`**: Cambia entre `'flexbox'` y `'grid'`
- **`$grid-columns`**: Número de columnas (por defecto 12)
- **`$grid-gutter`**: Espaciado entre columnas
- **`$enable-offset`**: Activa/desactiva clases de offset
- **`$enable-gap`**: Activa/desactiva clases de gap personalizadas

## Características Incluidas

### Sistema Flexbox
- Filas con `display: flex`
- Columnas responsivas: `.col-small-6`, `.col-medium-4`, etc.
- Offsets: `.offset-medium-2`
- Alineación: `.row-align-center`, `.row-justify-between`
- Orden: `.order-small-1`

### Sistema CSS Grid
- Filas con `display: grid`
- Grid de 12 columnas automático
- Columnas span: `.col-medium-6` (ocupa 6 columnas)
- Offsets con `grid-column-start`
- Sistema de gap nativo

### Utilidades
- Clases de gap personalizadas (0-6)
- Gap horizontal y vertical (`.gap-x-3`, `.gap-y-2`)
- Contenedores responsive
- Clases de visibilidad por breakpoint
- 5 breakpoints: small, medium, large, xlarge, xxlarge

Para cambiar entre sistemas, solo modifica la variable `$grid-system` al inicio del archivo.
