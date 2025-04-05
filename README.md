## 🏠 Proyecto BD - Casa Sanitaria

### 📌 Descripción:
- Base de datos en MySQL para gestionar productos, ventas, clientes, empleados y proveedores.

### 🛠️ Tecnologías:
- MySQL
- SQL

### 📂 Tablas principales:
- categorias: id, Nombre
- clientes: id, Nombre, Apellido, Email, Cuil, Telefono, Direccion
- empleados: id, Nombre, Apellido, Dni, Mail, Direccion, Puesto
- productos: id, Nombre, Precio, Stock, Codigo, id_categoria, id_proveedor
- proveedores: id, Nombre, Empresa, Telefono, Direccion
- ventas: id, Fecha, Hora, Total, id_clientes
- detalle_ventas: id, id_empleados, Fecha, Hora, Cantidad, id_productos
- ventas_del_dia: id, id_empleados, Fecha, Hora, id_ventas

### ✅ Notas:
- Estructura normalizada, con claves primarias y foráneas.

### 💡 Futuro:
- Agregar triggers, procedimientos y backups.
