# ABM_OOP
Práctica de hacer un ABM PHP OOP , sin framework
<pre>
	/**
	*	Armar un script que cumpla los siguientes requerimientos:
	*
	*	Se dispone de un JSON en la ubicación pub/products.json con informacion de productos.
	*	Se debe obtener este JSON desde PHP en la clase Product, procesarlo e insertar sus productos dentro de la tabla MySQL "products".
	*
	*	Al clickear el botón de <strong>CONSULTAR</strong>, se debe enviar el ID del producto al servidor vía AJAX (validar el ID como obligatorio y numérico).
	*	Se debe incluir un mensaje de "Cargando..." mientras la request está en proceso.
	*
	*	Al clickear el botón de <strong>VER TODOS</strong>, debe traer el listado completo de productos.	*
	*	El servidor debe devolver un listado de productos como JSON.
	*
	*	Con los resultados de las consulta, debe armar una tabla dentro de <strong>#result</strong> con todos los datos de los productos (<i>no imprimir el status</i>),
	*	agregando una columna al final con un botón para eliminar el producto.
	*
	*	<strong>Estos listados deben listar únicamente los productos con status = 1.</strong>
	*
	*	Al hacer click en el botón de eliminar, debe hacer otro llamado por AJAX al server, el cual seteará la columna "status" del producto a <strong>-1</strong>
	*	y devolverá un mensaje de éxito/error.
	*	Se debe eliminar la fila de la tabla de resultados para el producto eliminado.
	*
	*	<strong>IMPORTANTE:</strong> Usar OOP. Crear la clase Product, Database y/o las que crea necesarias.
	*/
		</pre>
