## Configura tu caja de herramientas (Data Analysis Toolbox)
Durante el aprendizaje, las hojas de cálculo, el lenguaje de consulta y la visualización de datos son una parte importante del trabajo de un analista de datos. En esta parte del curso, aprenderás más sobre los conceptos básicos involucrados y explorarás algunos ejemplos de cómo funcionan estas herramientas.

### objetivos de aprendizaje
---
  * Describe las hojas de cálculo, el lenguajes de consulta y las herramientas de visualización de datos con ejemplos específicos
  * Demuestra una comprensión de los usos, las características básicas y las funciones de una hoja de cálculo
  * Explica los conceptos básicos involucrados en el uso de SQL e incluye ejemplos específicos de consultas
  * Identifica los conceptos básicos involucrados en la visualización de datos mediante ejemplos específicos

### Herramientas de datos centrales
  * Spreadsheets
  * SQL
  * Data visualization tools

### Más recursos de hojas de cálculo
Para reforzar el aprendizaje permanente, es importante que tengas recursos para consultar cuando quieras saber más sobre el uso de hojas de cálculo. Dos de las plataformas de hojas de cálculo más conocidas y que más se usan son Google Sheets y Microsoft Excel. Ambas ofrecen recursos de capacitación en línea gratuitos a los que puedes acceder cuando sea necesario. Marca estos enlaces si quieres acceder a ellos más tarde.

[Ayuda y capacitación de Google Sheets](https://support.google.com/a/users/answer/9282959?visit_id=637361702049227170-1815413770&rd=1)

Aprende otras maneras de mover, almacenar y analizar tus datos con la página de Capacitación y ayuda de Google Sheets, que está en el Centro de aprendizaje de Google Workspace. Este centro ofrece una lista ampliada de consejos para los niveles desde principiante hasta avanzado, junto con hojas de referencia, plantillas, guías y tutoriales. 

[Hoja de referencia de Google Sheets](https://support.google.com/a/users/answer/9300022)

¿Deseas obtener más información sobre Google Sheets? En este artículo de ayuda en línea, se proporciona una breve lista de las funciones más importantes que usarás, incluidas filas, columnas, celdas y funciones. 

[Capacitación en Microsoft Excel para Windows](https://support.microsoft.com/en-us/office/excel-for-windows-training-9bc05390-e94c-46af-a5b3-d7c22f6990bb)

Si deseas saber un poco más sobre las hojas de cálculo de Excel, visita este centro de capacitación en línea gratuito. Encontrarás todo lo que necesitas saber en un solo lugar; desde una guía de inicio rápida e introducción hasta tutoriales y plantillas.

### SQL en acción 
* Store
* Organize
* Analize

## Databases wich use SQL
* Oracle
* MySQL
* PostgreSQL
* Microsoft SQL Server



Basic structure of a SQL Query (Start a big data table and go small to specefic conditions)
  ---
  2. SELECT: Choose the column (s) you want
  1. FROM: From the appropiate table 
  3. WHERE A certain condition is met
  
## Guía de SQL: Primeros pasos
**El lenguaje de consulta estructurado (SQL)**. SQL es una de las herramientas de análisis de datos más útiles, especialmente cuando se trabaja con grandes conjuntos de datos en tablas. Puede ayudarte a investigar grandes bases de datos y rastrear texto (conocido como cadenas) y números, y filtrar el tipo exacto de datos que necesitas, mucho más rápido que una hoja de cálculo.

### ¿Qué es una consulta? (Query: A request for data or information from a database).
Una consulta es una solicitud de datos o información que proviene de una base de datos.

Cada lenguaje de programación, incluido SQL, sigue una sintaxis única. La sintaxis es la estructura predeterminada de un lenguaje, que incluye todas las palabras, los símbolos y la puntuación requeridos, así como su correcta colocación.

La sintaxis de cada consulta SQL es la misma: 
- Usa **SELECT** para elegir las columnas que deseas devolver.
- Usa **FROM** para elegir las tablas donde se encuentran las columnas que deseas.
- Usa **WHERE** para filtrar determinada información.

Una consulta SQL es como rellenar una plantilla. Descubrirás que, si escribes una consulta SQL desde cero, es mucho mejor iniciar una consulta escribiendo las palabras clave SELECT, FROM y WHERE en el siguiente formato:

````
SELECT
 #Columns you want to look at
FROM 
 #Table the data lives in
WHERE 
 #Certain condition is met
````
Escribe el nombre de la tabla después del FROM, las columnas de la tabla que deseas después de SELECT y, por último, las condiciones que quieres agregar a tu consulta después del WHERE. Asegúrate de agregar un nuevo renglón y sangría cuando las agregues.

Seguir este método facilita el proceso de escribir consultas SQL. También puede ayudarte a cometer menos errores de sintaxis.

### Ejemplo de una consulta
Así es como aparecería una simple consulta en BigQuery, un almacén de datos de Google Cloud Platform.

````
SELECT 
 first_name 
FROM
 customer_data.customer_name 
WHERE 
 first_name = 'Tony'
 ````
La consulta anterior usa tres comandos para localizar clientes que se llaman Tony:
1. ELEGIR (SELECT) la columna denominada nombre (first_name)
2. DESDE (FROM) una tabla denominada nombre_del_cliente (customer_data) (en un conjunto de datos denominado nombre_del_cliente [customer_data]) (el nombre del conjunto de datos siempre va seguido de un punto y, a continuación, del nombre de la tabla).
3. Pero solo se devuelven los datos DONDE (WHERE) el primer_nombre (first_name) es Tony

Los resultados de la consulta pueden ser similares a los siguientes:

| first_name | |
--- | ---
| Tony |
| Tony |
| Tony |

En conclusión, esta consulta tenía la sintaxis correcta, pero no fue muy útil después de la devolución de los datos.

### Varias columnas en una consulta
En la vida real, tendrás que trabajar con más datos, además de los clientes llamados Tony. 

El  comando SELECT elige varias columnas que se pueden sangrar y agrupar.
Si solicitas varios campos de datos de una tabla, debes incluir estas columnas en el comando SELECT. Cada columna está separada por una coma, como se muestra a continuación:
````
SELECT
 ColumnA,
 ColumnB,
 ColumnC
FROM
 Table where the data lives
WHERE
 Certain condition is met
 ````
Este es un ejemplo de cómo aparecería en BigQuery:
````
SELECT 
 customer_id, 
 first_name, 
 last_name 
FROM 
 customer_data.customer_name 
WHERE 
 first_name = 'Tony'
 ````
La consulta anterior usa tres comandos para localizar clientes que se llaman Tony:
 1. **ELEGIR (SELECT)** las columnas denominadas **id_del_cliente (customer_id), nombre (first_name) y apellido (last_name)**
 2. **DESDE (FROM)** una tabla denominada **nombre_del_cliente (customer_data)** (en un conjunto de datos denominado **nombre_del_cliente [customer_data])** (el nombre del conjunto de datos siempre va seguido de un punto y, a continuación, del nombre de la tabla)3. Pero solo se devuelven los datos DONDE (WHERE) el nombre (first_name) es Tony”
 3. Pero solo se devuelven los datos **DONDE (WHERE)** el nombre (first_name) es **Tony**

La única diferencia entre esta consulta y la anterior es que se eligen más columnas de datos. La consulta anterior eligió solamente el nombre (first_name), mientras que esta consulta elige el ID_del_cliente (customer_id) y el apellido (last_name), además del nombre (first_name). 

Si tienes varias condiciones en tu cláusula WHERE, pueden escribirse de la siguiente manera:
````
SELECT 
 ColumnA, 
 ColumnB, 
 ColumnC 
FROM 
 Table where the data lives 
WHERE 
 Condition 1 
 AND condition 2 
 AND condition 3
Ten en cuenta que:
- *a diferencia del comando SELECT*, que usa una coma para separar campos/variables/parámetros, 
- *el comando WHERE* usa la instrucción AND para conectar condiciones. 
- Cuando te conviertas en un escritor de consultas más experimentado, usarás otros conectores u operadores, como OR y NOT. 

Ejemplo de BigQuery con varios campos usados en una cláusula WHERE:
````
SELECT 
 customer_id, 
 first_name, 
 last_name 
FROM 
 customer_data.customer_name 
WHERE 
 customer_id>0 
 AND first_name = 'Tony' 
 AND last_name = 'Magnolia'
La consulta anterior usa tres comandos para localizar clientes con un ID de cliente válido (mayor que 0) cuyo nombre es Tony, y su apellido es Magnolia.

 1. ELEGIR (SELECT) las columnas denominadas 
  id_del_cliente (customer_id), 
  nombre (first_name) 
  y apellido (last_name)
 2. DESDE (FROM) una tabla denominada nombre_del_cliente (customer_data) (en un conjunto de datos denominado nombre_del_cliente [customer_data]) (el nombre del conjunto de datos siempre va seguido de un punto y, a continuación, del nombre de la tabla).
 3. Pero solo devuelve los datos DONDE (WHERE) el ID_del_cliente (customer_id) es mayor que 0, el nombre (first_name) es Tony y el apellido (last_name) es Magnolia.

Ten en cuenta que una de las condiciones es una condición lógica que comprueba si el ID_del_cliente (customer_id) es mayor que cero.

Si un cliente se llama Tony Magnolia, los resultados de la consulta podrían ser:

| 1967 | Tony |
--- | ---

Si hay más de un cliente con el mismo nombre, los resultados de la consulta podrían ser:

| 1967 | Tony | Magnolia |
--- | --- | --- 
| 7689 | Tony | Magnolia |


Conclusión clave
Lo más importante es **recordar cómo usar SELECT, FROM y WHERE en una consulta.** 

## Las posibilidades de SQL son infinitas
### Uso de mayúsculas, sangría y punto y coma
- Puedes escribir tus consultas SQL solo en minúsculas, y no tienes que preocuparte por los espacios adicionales entre palabras
- el uso de mayúsculas y sangría puede ayudarte a leer la información más fácilmente
![xv18VOamRrm9fFTmpoa5wQ_cd7288dd597743a2a6e38ee0686621f1_Screenshot-2021-04-30-10 50 55-AM](https://user-images.githubusercontent.com/72023291/182603607-9d384618-b0f3-425d-a4e3-03c31bcfc576.png)
**Ten cuenta que la instrucción SQL que se muestra arriba tiene un punto y coma al final. El punto y coma es un terminador de instrucción que forma parte de la norma SQL-92 del Instituto Nacional Estadounidense de Estándares (ANSI), la cual es una sintaxis común recomendada para su adopción por todas las bases de datos SQL. Sin embargo, no todas las bases de datos SQL han adoptado o cumplido con el uso del punto y coma, por lo que es posible que te encuentres con algunas instrucciones SQL que no terminan con un punto y coma. Si una instrucción funciona sin punto y coma, es correcta.**

### Condiciones WHERE 
La cláusula **WHERE** restringe la consulta para que la base de datos devuelva solo los datos con una coincidencia de valor exacta, o los datos que coincidan con una determinada condición que deseas satisfacer. 

WHERE field1 = 'Chavez' # si estás buscando a un cliente específico con el apellido Chavez
WHERE field1 LIKE 'Ch%' #si estás buscando a todos los clientes que tienen un apellido que empieza con las letras “Ch”
 - la cláusula LIKE  permite decir a la base de datos que busque un patrón determinado.
 - El signo de porcentaje (%) se usa como comodín para que coincida con uno o más caracteres.
   - algunas bases de datos se usa un asterisco (*) como comodín en lugar de un signo de porcentaje (%).
   
### Elegir (SELECT) todas las columnas
si reemplazaras SELECT field1 por SELECT * , elegirías todas las columnas de la tabla en lugar de la columna field1 sola. Según cuántas columnas tenga una tabla, es posible que elijas una enorme cantidad de datos. Si eliges demasiados datos, es posible que la consulta se ejecute muy lentamente.

### Comentarios
Puedes agregar comentarios junto a tu SQL para ayudarte a recordar qué representa el nombre. Los comentarios son textos colocados entre ciertos caracteres
- /* y */, 
- o después de dos guiones (--), como se muestra a continuación. 
![k4wKMVuhQ6iMCjFbodOopA_eabf1858723e4c43a78ba734f9e40ff1_Screenshot-2021-04-30-10 53 40-AM](https://user-images.githubusercontent.com/72023291/182604839-1f427566-1e88-4cfa-a198-3bb86b4efaf5.png)
Los comentarios también se pueden agregar dentro o fuera de una instrucción. Puedes usar esta flexibilidad para proporcionar una descripción general de lo que harás, notas paso a paso sobre cómo lo lograrás y por qué estableces diferentes parámetros o condiciones. 
<img width="651" alt="TFj1L_EOTEWY9S_xDnxFCg_7e7ee9689e884f4ab4bbbcaac34c1616_Screen-Shot-2020-11-11-at-4 30 48-PM" src="https://user-images.githubusercontent.com/72023291/182604920-cd5eb080-e3d6-4c49-987a-e0bae77c4dbb.png">

### Ejemplo de una consulta con comentarios en BigQuery
<img width="629" alt="YFUj-vGxT4aVI_rxsY-GGg_0a4b434ac7c14176a192d0f65be62142_Screen-Shot-2020-11-11-at-4 32 20-PM" src="https://user-images.githubusercontent.com/72023291/182605082-eeae84c4-2890-4149-afa1-1eef78974922.png">
Puedes usar # en lugar de -- en la consulta anterior, pero # no se reconoce en todas las versiones de SQL; por ejemplo, MySQL no reconoce #.  También puedes colocar comentarios entre /* y */ si la base de datos que estás usando lo permite.

### Alias
Asignar un nuevo nombre o alias a los nombres de columna o tabla para que sea más fácil trabajar con ellos (y evitar la necesidad de agregar comentarios). **Esto se hace con una cláusula SQL AS.**
En el siguiente ejemplo, se asigna el alias last_name a field1 y el alias customers a table.Estos alias son válidos solo para la duración de la consulta. Un alias no cambia el nombre real de una columna o tabla de la base de datos.
![xWaDqVcZSrCmg6lXGSqwAQ_63f4dbb967a848919d5d1f10602926f1_Screenshot-2021-04-30-10 57 42-AM](https://user-images.githubusercontent.com/72023291/182605405-df8e9dd4-98c4-49bb-9ab2-5c372636197b.png)

### Cláusula AND
Deseas excluir a los datos con el código de trabajo INT que también ganan menos de USD 30,000. La cláusula AND te permite analizar ambas condiciones.
Creas una consulta SQL similar a la siguiente, en la cual <> significa “no es igual a”:
![DHE3QIDxTfKxN0CA8R3yZg_9fd64a89db55453e8f54afe7cc672ed5_Updated-image-for-C1M4L3R1](https://user-images.githubusercontent.com/72023291/182606243-4c627fff-21f3-4991-9544-36841feaacaa.png)
Así, los datos con el código de trabajo INT no se devuelven

### Recursos para más información: 
- [Tutorial de SQL de W3Schools](https://www.w3schools.com/sql/default.asp): Tutorial detallado de SQL. Incluye ejemplos interactivos que puedes editar, analizar y recrear. Úsalo como referencia o completa todo el tutorial para practicar el uso de SQL.

- [Hoja de referencia de SQL](https://towardsdatascience.com/sql-cheat-sheet-776f8e3189fa): Si eres un estudiante más avanzado, lee este artículo para obtener información sobre la sintaxis SQL estándar que se usa en PostgreSQL.
