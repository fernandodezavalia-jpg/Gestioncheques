# Gestion Cheques

Una aplicación web simple y robusta para gestionar tus cheques. Sube datos desde archivos CSV, añade cheques manualmente y visualiza un resumen de tus movimientos financieros.

## Características

- Subir datos de cheques desde archivos CSV.
- Añadir, editar y eliminar cheques manualmente.
- Filtrar cheques por banco y rango de fechas.
- Marcar cheques como pagados o pendientes.
- Visualizar un resumen mensual en una tabla y un gráfico.
- Guardar todos tus datos de forma segura y persistente en una base de datos en la nube.

## Estructura del Proyecto

- `index.html`: La estructura principal de la aplicación.
- `style.css`: Los estilos y el diseño de la interfaz de usuario.
- `script.js`: Toda la lógica de la aplicación, incluyendo la conexión a la base de datos y la gestión de datos.

## Cómo Empezar

1. Crea un nuevo repositorio en GitHub.
2. Copia y pega el contenido de `index.html`, `style.css` y `script.js` en los archivos correspondientes en tu repositorio.
3. Abre el archivo `index.html` en tu navegador. ¡No necesitas un servidor web ni ninguna configuración adicional!

## Uso de la Aplicación

### Subir tus datos

- Haz clic en **Subir Archivo (.csv)** para cargar tu "Tabla Madre" y tu "Resumen". La aplicación guardará estos datos en tu base de datos personal.

### Gestionar tus cheques

- Usa el botón **Añadir Cheque** para registrar un nuevo cheque manualmente.
- En la tabla, haz clic en **Editar** o **Eliminar** en la fila de cada cheque para modificar o borrar registros.
- El botón **Pagado / Pendiente** te permite cambiar el estado de un cheque con un solo clic.

### Analizar tu información

- Usa los filtros por banco y fecha para encontrar información específica.
- La sección de resumen y el gráfico te darán una visión rápida de tus movimientos financieros a lo largo del tiempo.