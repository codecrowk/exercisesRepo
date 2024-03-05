# Facturación de productos de los clientes.
Desarrolla un programa que permita a un usuario ingresar información sobre varios productos comprados por un cliente. El programa debe calcular el total de la factura, aplicar descuentos y mostrar el recibo detallado de la compra.

## Tabla de descuentos
Casos % Descuento

Si el cliente compra 3 o más productos se aplicara un descuento
5% sobre el valor total de la factura

Si el cliente compra 5 o más productos se aplicara un descuento
10% sobre el valor total de la factura

Si el cliente compra 7 o más productos obtendrá.
Bono por 100.000 para ser redimido en su siguiente compra.

Si el cliente compra un(1) solo producto superior a 500.000
No se vera obligado a pagar iva

## Nota
- Tenga en cuenta que se le debe aplicar iva a todas las compras realizadas. 
Ejemplo:
    si realizo una compra por un valor total de 100.000 el valor que deberá pagar será 119.000.
- Solo se puede aplicar un(1) beneficio de la tabla de descuentos.
- El IVA se aplicara al valor total de la factura sin tener en cuenta los descuentos obtenidos.

## Funcionalidad
1. El sistema solicitara al cliente sus datos para la factura, (número de documento, nombres y apellidos)
2. El sistema desplegara el menú de acciones del usuario.
(1) Volver a registrar el documento, nombres y apellidos del cliente
(2) Registrar un nuevo producto a la factura (nombre producto, valor producto)
(3) Listar productos actuales de la factura.
(4) Mostrar factura
(5) Apagar el programa