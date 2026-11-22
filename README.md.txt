La aplicación permite administrar los productos de una tienda. Además, incorpora funcionalidades de búsqueda, filtros por categoría y rango de precios, visualización de imágenes mediante URL y páginas independientes para cada operación.



Descripción de los archivos

database.py: establece la conexión con MongoDB.

app.py: contiene las rutas y la lógica principal de la aplicación.

product.py: define la clase Product y la estructura de los documentos.

base.html: plantilla principal que contiene la estructura común de las páginas.
index.html: muestra el inventario y los filtros de búsqueda.
404.html: muestra un mensaje cuando no se encuentra una página o producto.

create.html: formulario para registrar productos.
detail.html: muestra los detalles de un producto.
edit.html: formulario para modificar productos.
delete.html: ventana que solicita confirmación antes de eliminar un producto.



Instrucciones

Para ejecutar el programa hay que cambiar los credenciales en database.py:
	MONGO_URI = "mongodb+srv://yaracadima_db_user:5nObjFeS2z52XmUM@cluster0.yoyba5k.mongodb.net"
correr el archivo app.py e ir a la pagina http://localhost:4000/products en el navegador.

