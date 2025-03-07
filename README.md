curl --ubicación --solicitud POST 'https://api.zizy.io/transacción' \

--header 'x-api-key: SU_CLAVE_API' \

--header 'Tipo de contenido: aplicación/json' \

--datos-raw '{

"transaction_type": "TRANSACCIÓN_CON_TARJETA",

"nombre_del_comerciante": "Andrés manuel",

"banco": "banxico",

"código_categoría_comerciante": "2001",

"id_transacción": "8115124917",

"transaction_timestamp": "viernes, 07 de marzo de 2025 16:33:05GMT",

"monto_transacción": 1000.00,

"moneda_de_transacción": "USD",

"id_usuario": "8130437528",

"id_cuenta": "afirme",

"id_de_tarjeta": "4130980152901219"

3

4

5-

6

7

8

9

10

11

12

13

14

15

16

17

18

}