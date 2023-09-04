# Datasets - CM0888

## Real Estate

Nombre: [Rental Properties Collaboration Data](https://www.kaggle.com/datasets/arashnic/property-data)

Fuente: [arashnic](www.kaggle.com/arashnic) @ Kaggle

Descripción: base de datos generada por diversos sistemas de recomendación en el sector de bienes raíces (10000 registros). Las entradas de esta (*logs*) emulan las rentas en línea.

En la carpeta:
- Transactions.csv contiene los registros de rentas de propiedades
- Property.csv contiene detalles sobre las propiedades
- EventTypes.csv contiene detalles sobre algún evento en relación a una propiedad. Por ejemplo, si la propiedad fue vista (en línea), visita, agendamiento, etc.


## Empresa de Recaudos

Nombre: EmpresaRecaudos.csv

Fuente: cedida por compañía de forma anónima

Descripción: base de datos que guarda la trazabilidad de diversas transacciones (10000 registros) realizadas por clientes en una compañía de apuestas, recaudo de servicios públicos, recarga de servicios prepago (telefonía celular, televisión satelital prepago, etc.)

En el Archivo:
- ID.Nombre: id del cliente
- Producto: Producto solicitado
- Monto: Cantidad en pesos de la transacción comercial
- Fecha: Fecha en la que se realiza la transacción comercial (Día/Mes/Año)
- Hora: Hora de la transacción (HH:MM:SS en formato 24 horas)


## Motos

Nombre: Motos.csv

Fuente: cedida por compañía de forma anónima

Descripción: base de datos con 100000 registros que guarda trazabilidad en la compra de motocicletas.

En el archivo:
- ClienteID: Identificación del cliente
- Fecha: Fecha (día de la semana, día mes y año) de la compra
- NombreProducto: Motocicleta comprada


## Online Retail

Nombre: OnlineRetail.csv

Fuente: [University of California at Irving (UCI) Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail)

Descripción: 100000 registros de transacciones realizadas virtualmente entre el 01/12/2010 y el 09/12/2011 para compañía británica de *retail*

En el archivo:
- InvoiceNo: número identificador de la transacción. Si empieza por la letra 'c', indica cancelación. 
- StockCode: código del ítem (producto). Código asignado a cada producto.
- Description: Nombre del ítem (producto).
- Quantity: Cantidades compradas de cada producto en cada transacción..	
- InvoiceDate: Fecha y hora de la factura.
- UnitPrice: Precio unitario por producto en libras esterlinas.
- CustomerID: Identificador del cliente.
- Country: País en el que reside el cliente.
