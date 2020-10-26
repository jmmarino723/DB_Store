# DB_Store
DB Store description and DB
## Requerimientos funcionales ##
1. Incluir lista de productos visible al cliente.
2. Búsqueda por nombre, código de barras, marca, proveedor de productos.
3. Búsqueda por cédula, nombre, apellido de los clientes.
4. El diseño debe ser amigable para el usuario.
5. Incluir registro de transacciones con fecha y hora.
6. Mostrar usuarios con mayores compras.
7. Mostrar proveedores con mejores precios.
8. Mostrar proveedores con mejores tiempos de entrega.
9. Mostrar productos más vendidos TOP 10 del mes.
10. Mostrar productos menos vendidos TOP 10 del mes.
11. Mostrar ususarios con mayor cantidad de puntos para ofertas.
12. Acceso restringido por perfiles a cierta información.
13. Tabla de usuarios de acceso independiente. (CC empleado, cargo, nivel acceso)
14. Mostrar inventario por mínimos y máximos.
15. Alertas por mínimos para compras.
16. Fidelización por cumpleaños. Enviar correo a clientes.
17. Enviar correo después de 1 mes sin compra a clientes.
18. 
19. 
20. 

## Tablas ##

Descripción de las variables y llaves primarias de cada una de las tablas a crear, así como las relaciones que se tienen:

### Productos
* ID_producto **(PRIMARY_KEY)**
* ID_Categoría **(KEY)**
* ID_Proveedor **(KEY)**
* Nombre_producto
* Precio producto
* Desc_producto
* Img_producto
* Ultima_act

### Proveedor
* ID_Proveedor **(PRIMARY_KEY)**
* Nombre_Proveedor
* Tel_Proveedor
* Email_proveedor
* Direcc_Proveedor
* Ciudad_Proveedor

### Categorías
* ID_Categoría **(PRIMARY_KEY)**
* Desc_Categoría

### Empleados
* CC_empleado **(PRIMARY_KEY)**
* Nom_empleado
* Ape_empleado
* Nivel_acceso
* Cargo_empleado

### Clientes
* CC_Cliente: **(PRIMARY_KEY)**
* Nom_cliente
* Ape_cliente
* Cumple
* ID_puntos

### Puntos
* ID_puntos: **(PRIMARY_KEY)**
* Cant_punt


