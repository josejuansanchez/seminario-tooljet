# Seminario de Tooljet

Repositorio para el seminario de Tooljet.

# ¿Qué es Tooljet

TODO

# Mockups de la aplicación

## Listado de productos

La página principal de la aplicación muestra un listado de productos disponibles
en la base de datos.

![](images/mockup_00.png)

## Añadir productos al carrito

1. En la lista de productos podemos modificar la cantidad de cada tipo que queremos
añadir al carrito.

2. Para añadirlos hay que pulsar sobre el botón `Añadir a la cesta`.

3. En la esquina superior derecha se muestra el número de elementos que se han
añadido al carrito.

![](images/mockup_01.png)

## Ver el estado del carrito en formato JSON

El botón `Ver JSON` nos permite visualizar el estado del carrito en formato JSON.

Esta funcionalidad se ha añadido únicamente para facilitar la depuración de la
aplicación.

![](images/mockup_02.png)

![](images/mockup_03.png)

## Vaciar el carrito

El botón `Vaciar carrito` nos permite eliminar todos los elementos del carrito.

![](images/mockup_04.png)

![](images/mockup_05.png)

## Comprar

Cuando se pulsa sobre el botón `Comprar` la aplicación nos redirige a otra
página donde se muestra el contenido del carrito y podemos tramitar el pedido.

![](images/mockup_06.png)

En esta página nos aparece una tabla con el resumen de la compra y el importe total del pedido.

Al pulsar sobre el botón `Tramitar pedido` el pedido se insertará en la base de datos y se vaciará el carrito.

![](images/mockup_07.png)

Si el pedido se inserta con éxito nos aparecerá un mensaje de confirmación y redirigirá a la página principal.

![](images/mockup_08.png)

## Menú de navegación

La aplicación consta de tres páginas:

1. **Productos**: Listado de productos.
2. **Comprar**: Página donde muestra el contenido del carrito y se tramita el pedido.
3. **Pedidos:** Listado de pedidos realizados.

![](images/mockup_09.png)

## Listado de pedidos

En esta página se muestra una tabla con todos los pedidos realizados por el cliente.

![](images/mockup_10.png)