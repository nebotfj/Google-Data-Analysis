# La increíble hoja de cálculo

Some common math functions
- Sum
- Average
- Count
- Min
- Max

### Spreadsheet tasks
- Organize your data
  - Pivot table
    - Sort and filter
- calculate your data
-   Formulas
-   Functions

### Hojas de cálculo y el ciclo de vida de los datos.

Para entender mejor los beneficios de usar hojas de cálculo en el análisis de datos, exploremos cómo se relacionan con cada fase del ciclo de vida de los datos: planificar, capturar, administrar, analizar, archivar y destruir.

- Planifica respecto de los usuarios que trabajarán dentro de una hoja de cálculo mediante el desarrollo de estándares organizacionales. Esto puede significar formatear sus celdas, los encabezados que elijas resaltar, el esquema de color y la forma en que ordenas tus puntos de datos. Cuando te tomas tu tiempo para establecer estos estándares, mejoras la comunicación, garantizas la coherencia y ayudas a las personas a ser más eficientes con su tiempo.
- Captura los datos según su fuente mediante la conexión de hojas de cálculo a otras fuentes de datos, como una aplicación de encuestas en línea o una base de datos. Estos datos se actualizarán automáticamente en la hoja de cálculo. De esa manera, la información es siempre lo más actual y precisa posible.
- Administra diferentes tipos de datos con una hoja de cálculo. Esto puede implicar almacenar, organizar, filtrar y actualizar la información. Las hojas de cálculo también te permiten decidir quién puede acceder a los datos, cómo se comparte la información y cómo mantener tus datos seguros y protegidos. 
- Analiza los datos en una hoja de cálculo para ayudar a tomar mejores decisiones. Algunas de las herramientas de análisis de hojas de cálculo más comunes incluyen fórmulas para agregar datos o crear informes, y tablas dinámicas para imágenes claras y fáciles de entender. 
- Archiva las hojas de cálculo que no uses con frecuencia, pero que es posible que debas consultar más adelante con herramientas integradas. Esto te servirá, especialmente, si deseas almacenar datos históricos antes de que se actualicen. 
- Destruye tu hoja de cálculo cuando estés seguro de que nunca la volverás a necesitar; si tienes mejores copias de seguridad, o por motivos legales o de seguridad. Ten en cuenta que muchas empresas deben seguir ciertas reglas o tomar medidas para asegurarse de que los datos se destruyan correctamente.


Recursos
Los accesos directos a las hojas de cálculo pueden ayudarte a ser más eficiente con ellas. Si deseas obtener más información, puedes investigar sobre la colección de [accesos directos de Google Sheets](https://support.google.com/docs/answer/181110) o, si usas Excel, puedes visitar la página de [accesos directos de Microsoft Excel](https://support.microsoft.com/en-us/office/keyboard-shortcuts-in-excel-1798d9d5-842a-42b8-9c99-9b7213f0040f). Ambos recursos contienen una lista de accesos directos de hojas de cálculo que puedes guardar y consultar a medida que trabajes más seguido con hojas de cálculo.



Errores: Descripción y Ejemplo

#DIV/0!

Una fórmula está tratando de dividir un valor de una celda por 0 (o una celda vacía sin valor)

=B2/B3, cuando la celda B3 contiene el valor 0

#ERROR!

(Solo para Google Sheets) Algo no se puede interpretar de la manera en que se ingresó. Esto también se conoce como error de análisis.

=COUNT(B1:D1 C1:C10) no es válido porque los rangos de celdas no están separados por una coma.

#N/A

Una fórmula no puede encontrar los datos

No se puede encontrar la celda a la que se hace referencia

#NAME?

No se reconoce el nombre de una fórmula o función utilizada.

El nombre de una función está mal escrito.

#NUM!

La hoja de cálculo no puede hacer un cálculo de fórmula porque una celda tiene un valor numérico no válido.

=DATEDIF(A4, B4, "M") no puede calcular el número de meses entre dos fechas porque la fecha de la celda A4 es posterior a la fecha de la celda B4

#REF!

Una fórmula hace referencia a una celda que no es válida.

Una celda usada en una fórmula estaba en una columna que se eliminó.

#VALUE!

Un error general que indica un problema con una fórmula o con celdas a las que se hace referencia.

Podría haber problemas con los espacios, el texto o las celdas a las que se les hace referencia en una fórmula; es posible que tengas que trabajar más

 para hallar el origen del problema. 

[Documento resumen de errores](https://github.com/sirjn/Google-Data-Analysis/files/12891999/872yQ-X9Q069skPl_TNOGA_ea3700e555c945d88b9cf6d31d2653f1_More-about-spreadsheet-errors-and-fixes_SPA.1.docx)

Si estás trabajando con Microsoft Excel, la página interactiva [Cómo corregir un error de #VALUE!](https://support.microsoft.com/en-us/office/how-to-correct-a-value-error-15e1b616-fbf2-4147-9c0b-0a11a20e409e) puede ayudarte a reducir la causa del error. En una lista desplegable, puedes elegir una función específica para mostrar un enlace a consejos a fin de corregir el error cuando se usa esa función.


## Recursos de errores de hoja de cálculo
Para obtener más información y leer sobre más ejemplos de errores y soluciones, explora estos recursos:

[Fórmulas y funciones de Microsoft](https://support.microsoft.com/en-us/office/formulas-and-functions-294d9486-b332-48ed-b489-abe7d0f9eda9?ui=en-US&rs=en-US&ad=US#id0eaabaaa=errors): En este recurso, se describe cómo evitar fórmulas rotas y cómo corregir errores en Microsoft Excel. Esta es una referencia útil de conservar en caso de que te encuentres con un error específico y necesites hallar soluciones rápidamente mientras trabajas en Excel. 

[Cuando tu fórmula no funciona:](https://www.benlcollins.com/spreadsheets/formula-parse-error/): [errores de análisis de fórmula en Google Sheets](https://www.benlcollins.com/spreadsheets/formula-parse-error/): Este recurso es una guía para encontrar y corregir algunos errores comunes en Google Sheets. Si estás trabajando con Google Sheets, puedes usar esto como referencia rápida para resolver problemas que puedes encontrar cuando trabajes por tu cuenta.

## Accesos directos del teclado:
[1yuA0UjeSc2rgNFI3vnN3A_c3073fa61c7247a8bc26245d400ae0f1_Quick-reference--Functions-in-spreadsheets1_SPA.docx](https://github.com/sirjn/Google-Data-Analysis/files/12892502/1yuA0UjeSc2rgNFI3vnN3A_c3073fa61c7247a8bc26245d400ae0f1_Quick-reference--Functions-in-spreadsheets1_SPA.docx)


[BYn_Vx19SA6J_1cdfTgOnQ_b8e76d09efc544a29a29c7dbfa865cf1_Quick-reference--Functions-in-spreadsheets2_SPA.docx](https://github.com/sirjn/Google-Data-Analysis/files/12892500/BYn_Vx19SA6J_1cdfTgOnQ_b8e76d09efc544a29a29c7dbfa865cf1_Quick-reference--Functions-in-spreadsheets2_SPA.docx)


![image](https://github.com/sirjn/Google-Data-Analysis/assets/72023291/ff4a1f36-e6e5-4ecd-ae78-56c10f4616ab)

RESUMEN DEL BLOQUE: 
[Glosario: Términos y definiciones](https://github.com/sirjn/Google-Data-Analysis/files/12893007/6jxTkHYXQeW8U5B2F7HlPQ_c1c68d785b604f37834c1b2ecc5a57f1_DAC2M3L7R1ATTACHMENT_SPA.docx)
