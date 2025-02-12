# Análisis de transacciones con tarjeta de crédito sobre la utilización del crédito y el comportamiento de gasto

# Trasfondo

Este análisis se realizó con un conjunto de datos de Kaggle de Arjun Bhasin y contiene información sobre el comportamiento de uso de tarjetas de crédito de 9000 usuarios.

Se proporcionan conocimientos y recomendaciones sobre las siguientes áreas clave: Utilización del crédito y comportamiento de gastos.

# Estructura de datos y herramientas

Los datos tienen un total de 18 columnas y 8950 filas. Los tipos de datos incluidos en el conjunto son integers, decimamals y strings.

La limpieza, manipulación y visualización de los datos se realizó en RStudio.

# Resumen

# Alcance 
 * Calcular el porcentaje de utilización
 * Categorizar el porcentaje de utilizaación bajo "Low Risk", "Moderate Risk" o "High Risk"
 * Calcular cantidades de clientes bajo cada cateogoria de riesgo
 * Estudiar el comportamiento de gastos de clientes

# Descubrimientos
###Utilización del crédito
* De los 8,950 clientes 4,455 caen bajo Low Risk, 2,786 bajo High Risk y 1,709 bajo Moderate Risk. Esto significa que un 49.77% de los clientes tienen un porcentage utlizacion de credito menor de 0.3. Consecuentemente, 31.12% tiene porcentage utlizacion de credito mayor de 0.6 y un 19.09% tiene un porcentage utlizacion de credito entre 0.3 y 0.6. 
* La mayoria de las cantidades de compras son realizadas por clientes con utilización baja, o que caen bajo la categoria de "Low Risk". A medida que aumenta la utilización, la cantidad de compras disminuye, lo que significa que un uso alto del crédito no se relaciona con mayores gastos.
* La mayoría de los clientes tienen balances y pagos de baja cantidad y los pagos no se ajustan proporcionalmente a los balances. Muchos de los clientes con balances altos realizan pagos de cantidades bajas.

  ###Comportamiento de gastos
  *

# Recomendaciones :

# Referencias
