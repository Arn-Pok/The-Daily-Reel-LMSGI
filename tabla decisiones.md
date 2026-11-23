Tabla decisopmes


1. Datos que representa la tabla

La tabla recoge el historial de películas recomendadas en The Daily Reel.

Se mantienen las tres películas del archivo original:

Interstellar — Christopher Nolan.

Moneyball — Bennett Miller.

The Social Network — David Fincher.

Los datos se organizan en cinco columnas:

Título de la película.

Director.

Género.

Año de estreno.

Fecha recomendada.

2. Encabezados

Encabezados de columna: título, director, género, año de estreno y fecha recomendada.

Encabezados de fila: el título de cada película.

Totales: no se añade una fila de total porque los datos son descriptivos y no cantidades que deban sumarse.

3. Decisión semántica

He utilizado scope="col" en los encabezados de columna y scope="row" en el título de cada película.

El título identifica la fila y permite relacionar el resto de los datos con esa película.

Las celdas de información utilizan td.

También he añadido caption para describir el contenido de la tabla y time para representar las fechas.

4. Teclado y foco visible

He utilizado tabindex="0" en los encabezados y las celdas para permitir recorrerlos con Tab.

He definido :focus-visible con un contorno visible para facilitar la identificación del elemento enfocado.

Es importante distinguir que tabindex permite recibir el foco y scope establece las relaciones semánticas entre encabezados y celdas.

5. Uso de IA

He utilizado IA como apoyo para revisar la estructura semántica de la tabla.

La recomendación fue utilizar scope="row" y scope="col", sugerencias que acepté porque permiten relacionar correctamente los encabezados con los datos.

La validación W3C y las pruebas de accesibilidad deben ejecutarse para comprobar el resultado final.
