# Botilleria-POO-pseudocodigo
clase producto
{
	##atributos##
	idProducto=# identificador del producto
	nombre=''#nombre del producto
	precio=# precio del producto
	proveedor=''#nombre del proveedor, contactos
	cantidad=# cantidad de productos

	##fin atributos##

	##metodos##
	
	cambiar_cantidad(nuevaCantidad)#permite ingresar,modificar, eliminar la cantidad productos
	cambiar_proveedor(nuevoProveedor)#permite actualizar datos o proveedor
	##fin metodos##	
}

clase proveedor
{
	##atributos##
	nombre=´´# ingresa nombre del proveedor
	producto=´´# nombre del producto
	cantidad=# cantidad del producto
	direccion=´´# direccion del proveedor
	telefono=# contacto del proveedor

	##fin atributos##

	##metodos##
	cambiar_telefono(telefono)#nuevo telefono
	cambiar_cantidad(cantidad)#cambiar cantidad
	##fin metodos##
}

clase inventario
{
	##atributos##
	numerosolicitud=#permite registrar el numero de solicitud
	##fin atributos##

	##metodos##
	cambiar_numerosolicitud(nuevonumerosolicitud)# permite ingresar otra solicitud

	##fin metodos##
}
