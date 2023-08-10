1. Creación de scripts
	1. ![[Pasted image 20230802093908.png]]
	2. ![[Pasted image 20230802093922.png]]
	3. Esructura de un scripts
		1. importar scripts
			1. ![[Pasted image 20230802114944.png]]
			
		2. Settings ()
		3. Prod![[Pasted image 20230802094601.png]]
		4. Preprod![[Pasted image 20230802094620.png]]
		5. ![[Pasted image 20230802094834.png]] 
			6. username: cuenta padre
			7. collection: form_answer, colección de mongo
			8. PROTOCOL:
			9. HOST: dominio general
			10. MONGODB_USER = usuario_id
			11. PASSWORD: Pedir a Roman o a Pato
			12. Configuración API KEY
				1. ![[Pasted image 20230802095550.png]]
				2. Se actualizan revisar, causante de errores de apikey
				3. log -> Mensaje para debuggear un error![[Pasted image 20230802100252.png]]
				5. option 1, el error esta en la ejecución del reporte no de la búsqueda
				6. Recomendación: Dejar variables iu}guales en back y front
				7. ![[Pasted image 20230802100523.png]]
				8. ![[Pasted image 20230802100547.png]]
					1. Validación de fechas date_from, date_to
			13. ![[Pasted image 20230802100824.png]]
				1. Token lo tomo, lo coloco en el confic
			14. ![[Pasted image 20230802101030.png]]
				1. Colecciones
			15. MatchQuery
				1. ![[Pasted image 20230802101443.png]]
					1. form_id : id de la forma
				2.![[Pasted image 20230802101554.png]]
					Filtros que no varian, que siempre se utrilizan
				3. ![[Pasted image 20230802101848.png]]
				4. **Standar** UT0: 00
				5. ![[Pasted image 20230802102006.png]]
					1. Convierte el horario UTT0 a MEXICO-CENTRO
				![[Pasted image 20230802102136.png]]
				Query:![[Pasted image 20230802102621.png]]
				6. s
				7. ![[Pasted image 20230802110414.png]]
					1. Devuelve la collección nobtrafas lote, sergunfo asrgumento corresponde, el dato que va a drvolver.
					2. 
			1. 
	1. ![[Pasted image 20230802114436.png]]
	2. 
		3.accounts_settings.py ->Configuración inicial del cliente
2. Configuración de archivos