Linkaform hace uso de subdominios para el desarrollo de las plantillas de pdfs.
Estas son:

>**Producción** 
>**Preprod** En esta se realizar cambios sin incurrir en riesgos que afecten a la manera en la que el cliente accede a los pdfs.

### Cuentas

-----------------------------------------------------------------
Desarrollar pdfs necesita del acceso a ciertas cuentas en LinkaForm:
+ **Cuenta de preproducción**
+ **Administrador django:** Se necesita de una cuenta y contraseña para acceder a la cuenta, esta es otorgada por el grupo técnico de LinkaForm. En esta plataforma se gestionan las plantillas pdfs asociadas a cada cliente. Por favor consulte [[Bases de django]] para conocer los conceptos más indispensables de la herramienta más utilizado en LinkaForm.

### Estructura de creación de plantillas en django preprod

-------------------------------------------------------------------------------
1. Iniciar sesión en django preprod [https://preprod.linkaform.com/admin/login/?next=/admin/](https://preprod.linkaform.com/admin/login/?next=/admin/)
2. Acceder a la sección de **crear plantillas**
3. Se muestra un formulario con la siguiente estructura:
	1. **Título:**  Escribir el titulo de la plantilla con las métricas **nombre_pnatilla para nombre_cliente**
	2. **Paginación:** Es un campo checkbox, esta seleccionado por defecto indicando que...
	3. **Header:** En este campo se debe colocar el contenido de [[Header]]
	4. **Body:** En este campo se debe colocar el contenido de [[Body]]
	5. **Footer**: En este apartado se coloca el contenido de [[Footer]]
	6. **Style:** En esta sección se coloca el contenido de [[Style]]
5. Colocar el owner o el dueño de la cuenta: Cada usuario está asociado a la cuenta de un awner, esto debido a que LinkaForm se le asigna una cuenta a cada cliente, se debe seleccionar la cuenta del cliente al que se esta realizando el pdf o si en su defecto se están realizando pruebas, es recomendable asociarla a la cuenta padre del José Patricio Villa Real con el id 126.
6. Una ves realizado los pasos anteriores, seleccione el botón **Guardar y continuar** situado en la parte inferior izquierda de la página.


