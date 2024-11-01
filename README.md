# Primer DER Ontológico Centro de Distribución
Proyecto SQL Bolt Shipping
![Primer_DER_Bolt_Shipping](https://github.com/user-attachments/assets/a6a60e09-0a6c-4b00-adbd-91e591126bfd)
# Bolt Shipping Database
Este proyecto trata sobre una empresa de logística de tipo Cross Docking la cual se encarga de recibir productos de diferentes vendedores en el Centro de Distribución donde los operarios procesan y despachan los envíos hacia los clientes de todo el país.
## Tablas y Relaciones

### Tabla: `vendedores`
Almacena información de los vendedores que envían sus productos al Centro de Distribución.
- **Campos:**
  - ID_VENDEDOR PK
  - NOMBRE_VENDEDOR
  - TIPO_VENDEDOR
  - DOMICILIO_VENDEDOR
  - EMAIL_VENDEDOR
 
- **Relación:**
    Se relaciona con la tabla `Productos` como llave foránea.
  
### Tabla: `productos`
### Tabla: `centro_de_distribucion`
### Tabla: `operarios`
### Tabla: `categoría_operarios`
### Tabla: `shipment`
### Tabla: `clientes`


