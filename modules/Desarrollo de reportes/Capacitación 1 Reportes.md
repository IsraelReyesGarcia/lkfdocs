
1. Manipular formas
	1. Configuración
2. Servido: Es una platadorma OpenSource donde clientes y linkaform desarrollan reportes con herramientas como APIS, scripts, 
	1. Parte 1: Carpeta
	2. ![[Pasted image 20230801094028.png]]
		1. Carpetas app. cada tiulo tiene el nombre de cada cliente.
	3. 
3. InfosynScripts: Carpetas de clientes que usaron scripts
	5. ![[Pasted image 20230801094336.png]]
6. Configurar el front
	1. bootstrap
	2. js Vanilla
	3. jquery https://jquery.com/
	4. [https://www.chartjs.org/](https://www.chartjs.org/) (Creación de charts)
	5. https://tabulator.info/ (Gestor de tablas) saca pdfs, csv, buscadores, cualquier configuración en la data
	6. . carpeta cliente
		1.  syles.css (Estilos de los reportes por cliente)
		2.Estructura por reporte:
			reporte_nombreReporte.html
			reporte_nombreReporte.js
			reporte_nombreReporte_data.js (Configuración de bibliotecas)
			reporte_nombreReporte.css
			****
			Limite de tiempo
				4hrs-max 10hrs****
			![[Pasted image 20230801095058.png]]
1. Configuración de reportes:
	1. En la cuenta de linkaform podemos realizar las siguientes acciones para los reportes:
	2. Acciones:
		1. Compartir
		2. Configurar
		3. Ver el reporte
		4.Herramientas más comunes en la creación de reportes
		1. Fechas, tablas, 
		2. Tablas
		3. Filtrar, dinamismo
		4. Descargar los reportes en excel
		5. Descargar los reportes en pdf
1. Bibliotecas para construir un reporte:
	1. bootstrap (Estilos)
	2. js Vanilla ()
	3. jquery https://jquery.com/ (Dinamismo a los elementos)
	4. [https://www.chartjs.org/](https://www.chartjs.org/) (Creacióin de charts)
		1. Gráficos más solicitados:
			1. Gráficos 
			2. Barras
			3. Lineas
			4. Pai
		2. [https://tobiasahlin.com/blog/chartjs-charts-to-get-you-started/#8-grouped-bar-chart](https://tobiasahlin.com/blog/chartjs-charts-to-get-you-started/#8-grouped-bar-chart
	6. https://tabulator.info/ (Gestor de tablas) saca pdfs, csv, buscadores, cualquier configuración en la data, Ir a examples, formatear la data, (feat data, responsive layout, coaps) 
		1. Las tablas se descargan en varios formatos: 
2. Como hacer cambios en el front
	1. Subir los cambios al repositorio
	2. Hacer un build
3. Creación de DEMO
	1. Configuramos docker para acceder "docker-compose up - "
	2. .Al crear la DEMO se coloca el enlace en el navegador, para comenzar a buscar.
	3. Comenzar con el front
	4. Hacer pruebas 
		1. Realizamos cambios
		2. Accedemos a las ruta 
		3. ![[Pasted image 20230801103405.png]]
	5. Estructura:
		1. HTML
			1. header
				1.  | Syntax      | Description |
| :---------: | :---------: |
| ```{{ }}```      | Imprimir su contenido similar a console.log en JS       |
| ```{% %}```   | Define variables, devuelve valores e imprime contenido        |

			2. style
			3. body
				1. ![[Pasted image 20230801103540.png]]
				2. ![[Pasted image 20230801103626.png]]
				3. Como accedemos a dem
					1. ![[Pasted image 20230801103720.png]]
					2. Se recibe el  scripts
					3. ![[Pasted image 20230801104044.png]]
					4. Llamar catálogos
						1. Mandar a llamar a una api (poco practico, te devuelve resultados en prnmer nivel)
						2. Hacer 
					5. ![[Pasted image 20230801104737.png]]
					6. Elemento de la tabla
					![[Pasted image 20230801105039.png]]
					7. Acceder a las bibliotecas con la cdn
					 ![[Pasted image 20230801105252.png]]
					9. Los utils están en linkaform apps/ servido_utils.js (Configura el id)
					10. ![[Pasted image 20230801105506.png]]
					11. ![[Pasted image 20230801105547.png]]
					12.Cambian los filtros y los estilos 
			1. footer
			2. [https://fontawesome.com/](https://fontawesome.com/)![[Pasted image 20230801102747.png]]
		3. JS
			1. ![[Pasted image 20230801110002.png]]
			2. ![[Pasted image 20230801110443.png]]
				1. Configurar para que el cliente acceda a prod y haga sus cambios
				2 ![[Pasted image 20230801110734.png]]
									- El if permite cargar la demo
									- El Styles permite 
			funcionDemoData() 
				Le decimos que muestre los elementos tabla
					![[Pasted image 20230801111447.png]]
					La DEMO debe ser lo más rápido que se pueda
							1. Select
							2. get_firstElement
								1. Petición para obtener la data
								2. la variable **column** Si necesita de un scripts no se recomienda ser automáticos
								3. getWrawTable(id. columData, tabledData
								4. ![[Pasted image 20230801114956.png]]
								5. ![[Pasted image 20230801115123.png]]
								6. Data:
									1. Title: Título
									2. hasSize = Posición
									3. Width=Ancho de la columna
									4. formater = Formato para las columnas
									5. precision = false, sin decimales y numéricos: define el No. de dec
									6. 
		1. CSS
			1. Estructura del css
			2. ![[Pasted image 20230801102950.png]]
			3. ![[Pasted image 20230801102919.png]]
1. ![[Pasted image 20230801094550.png]]
2. ![[Pasted image 20230801102430.png]]