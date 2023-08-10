
Estructura de la api
settings: 
urls: 

usar el método "create_filters"
create_filters = "tiene la ruta de destino/el método/"

Cuando se crea un scripts  para los clientes, se debe hacer lo siguiente: 
1. Acceder al directorio infosync_scrip.js
2. Acceder al nombre del cliente
3. Se verán los siguientes archivos
4. accounts_settings.py = Se definen las credenciales del usuario, además, del subdominio de prueba.
## Creación de filtros
-----------------------------------------------------------

Si se desea crear un filtro como en este caso, se define un archivo llamado **create_filters.com**

Ejecutar scripts desde el servidor
python arg1 arg2 arg3 arg4

Estructura de create_filters.py
>Montar las dependencias a necesitar
>	importamos a linkaform (Cuando Linkaform se invoca lo primero que se lee es el archivo init.py)
>	importamos el archivo **account_settings.py**
>Definir las funciones
>definir la clase main, necesaria para correr el scripts desde consola


Estructura de account_settings.py
	Define las credenciales del cliente
	> puerto a usar
	> HOST
	

if name = "__main__":
	current_record = simplejson.loads(sys.argv[1])
	jwt_complete = simplejson.loads(sys.argv[2])
	config['USER_JWT_KEY'] = jwt_complete["jwt"].split(' ')[1]
	settings_config.update(config)
	net = network.Network(settings)
	cr = net.get_collection()
	validate_counts(current_record)

Definición de la función create_filter
	Recibe cuatro parámetros.
	1. id del catalogo
	2. nombre del filtro
	3. filtro a buscar
	4. filter_selected = cuando ya tienes un filtro y realizas un filtro 
	5. jwt = si quieres enviar un jwt distinto a la llave default
Crear api_key
	Ingresar a la cuenta del usuario
	Creamos la api_key
	
python path (Variable de ambiente)
