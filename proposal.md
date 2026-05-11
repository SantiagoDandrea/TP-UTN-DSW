# Propuesta TP DSW

## Grupo
### Integrantes
* 52923 - D'Andrea, Santiago
* 51872 - De Benedetti, Martin
* 49692 - Ravarotto, Giovanni Santino
* 30478 - Giannuzzi, Guillermo

### Repositorios
* [frontend app]()
* [backend app]()
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
*Sistema web E-Commerce destinado a la venta de artículos de colchonería, tecnología y electrodomésticos*

### Modelo
[Propuesta](https://drive.google.com/file/d/1G9vCAjXbEdTR9zqLLkdPHgMROQR0kiN8/view?usp=sharing)
## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Categoría de Producto<br>2. CRUD Marca<br>3. CRUD Medio de Pago<br>4. CRUD Localidad|
|CRUD dependiente|1. CRUD Producto {depende de} CRUD Categoría de Producto<br>2. CRUD Usuario {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de productos filtrado por categoría de producto y/o marca, muestra marca, descripcion y precio del producto => detalle CRUD Producto<br> 2. Listado de pedidos filtrado por rango de fecha y/o estado, muestra nro de pedido, fecha del pedido, estado y nombre del cliente => detalle muestra datos completos del pedido y del usuario|
|CUU/Epic|1. Realizar un pedido completo<br>2. Realizar el cambio de estado del pedido|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Categoría de Producto<br>2. CRUD Marca<br>3. CRUD Medio de Pago<br>4. CRUD Localidad<br>5. CRUD Producto<br>6. CRUD Pedido<br>7. CRUD Precio<br>8. CRUD Usuario<br>9. CRUD Proveedor<br>10. Envio<br>11. Stock<br>12. Almacen|
|CUU/Epic|3. Dar el alta de productos y actualizar stock<br>4. Cancelar un pedido|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Filtrado de pedidos con ordenamientos y agrupados por usuario<br>2. Filtrado de productos por precio|
|CUU/Epic|1. Modificación de precios<br>2. Agregar descuento por Marca o Categoria de Producto|
|Otros|1. Envío de seguimiento de pedido/envio por email al cliente|

