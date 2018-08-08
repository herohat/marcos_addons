# NCF DGII Reports

Este módulo para ODOO 10 (por lo pronto) implementa los reportes de los números de comprobantes fiscales (NCF) para el cumplimento de la norma 06-18 de la Dirección de Impuestos Internos (DGII) en la República Dominicana.

Este repositorio tiene como objetivo que este módulo sea integrado en https://github.com/odoo-dominicana/l10n-dominicana y que sea mantenido por la comunidad de ODOO Dominicana.  Mientras tanto todo aquel que desee colaborar, puede hacer un Pull Request aquí.

## CONFIGURAR IMPUESTOS
Se debe configurar correctamente los impuestos, para ello ir al listado de impuestos y en la opción de Tipo de Impuesto de Compra (Cuando el Ámbito del Impuesto es Compra) seleccionar la opción adecuada para cada caso.

## CONFIGURAR CORRECTAMENTE LOS TIPOS DE PRODUCTOS
En cada producto, se debe configurar correctamente el "Tipo de Producto" para poder filtrar el "Monto Facturado en Servicios" y el "Monto Facturado en Bienes".  Actualmente si un producto es del tipo "Servicio" pues se suma al Monto Facturado en Servicios y si es otra cosa como puede ser Consumible o Almacenable, entonces lo sumamos al Monto Facturado en Bienes.  OJO que si venden productos digitales (como libros, fotos, etc..) en teoría serían servicios al no ser algo mateiral pero esto tampoco lo estamos filtrado en la actualidad y en dado caso de ponerlo caerían como Bienes.


### ESTADO ACTUAL:  En desarrollo, no funcional para declaraciones aún.  Faltan agregar nuevas columnas en los reportes y hacer las pruebas de lugar.

### Créditos:  Basado en el trabajo de Eneldo Serrata para Marcos Organizador de Negocios SRL. (https://marcos.do/) 

### Autor: Manuel Gonzalez para SOFTNET TEAM SRL (https://www.softnet.do)
