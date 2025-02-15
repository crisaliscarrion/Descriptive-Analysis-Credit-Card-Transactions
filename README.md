# Análisis de transacciones con tarjeta de crédito sobre la utilización de crédito y el comportamiento de gastos

# Trasfondo

Este análisis se realizó con un conjunto de datos de Kaggle de Arjun Bhasin y contiene información sobre el comportamiento de uso de tarjetas de crédito de 8,950 usuarios.

Se proporcionan conocimientos y recomendaciones sobre las siguientes áreas claves: Utilización del crédito y comportamiento de gastos.

# Estructura de datos y herramientas

Los datos tienen un total de 18 columnas y 8950 filas. Los tipos de datos incluidos en el conjunto son integers, decimals y strings.

La limpieza, manipulación y visualización de los datos se realizó en RStudio.

![data set desctp](https://github.com/user-attachments/assets/a8061959-c728-45d6-8fba-8b42e9d10a32)

# Alcance 
 * Calcular el porcentaje de utilización
 * Categorizar el porcentaje de utilización bajo "Low Risk", "Moderate Risk" o "High Risk"
 * Calcular cantidades de clientes bajo cada cateogoría de riesgo
 * Estudiar el comportamiento de gastos de clientes

# Descubrimientos
## Utilización del crédito
* De los 8,950 clientes 4,455 caen bajo "Low Risk", 2,786 bajo "High Risk" y 1,709 bajo "Moderate Risk". Esto significa que un 49.77% de los clientes tienen un porcentaje de utlizacion de credito menor de 0.3. Consecuentemente, 31.12% tiene un porcentaje de utlización de credito mayor de 0.6 y un 19.09% tiene un porcentaje de utlización de credito entre 0.3 y 0.6. 
* La mayoría de las cantidades de compras son realizadas por clientes con utilización baja, o que caen bajo la categoria de "Low Risk". A medida que aumenta la utilización, la cantidad de compras disminuye, lo que significa que un uso alto del crédito no se relaciona con mayores gastos.
* La mayoría de los clientes tienen balances y pagos de baja cantidad y los pagos no se ajustan proporcionalmente a los balances. Muchos de los clientes con balances altos realizan pagos de cantidades bajas.

## Comportamiento de gastos
  * Las cantidades de compras disminuyen a medida que aumenta el porcentaje de utilización y se observa un patrón en donde las cantidades de compras más altas se observan mayormente en los porcentajes de utilización bajos.
  * La mayoría de los clientes no utilizan cash advances o solicitan cantidades pequeñas. Se observa una tendencia en la que los clientes que solicitan cash advances de cantidades altas tienden a tener balances más altos.

# Visualizaciones 
## Cantidad de clientes bajo categoría de riesgo 
![file_show (2)](https://github.com/user-attachments/assets/83588aef-283e-413d-ba08-8d19373cfce8)

## Relación entre cantidad de balance y cantidad de pagos
![file_show](https://github.com/user-attachments/assets/7e6e72c7-1c9b-4ac4-9010-e84dfcf5f49f)

## Relación entre porcentage de utilización y cantidad de compras
![cu versus purchases](https://github.com/user-attachments/assets/26a13b61-242c-4099-b4e7-63edeb8960fd)

## Relación entre balance y cash advances 
![file_show (1)](https://github.com/user-attachments/assets/8a9ec978-dc3a-46c6-9b6e-7027fd04677d)


# Recomendaciones:
* Establecer sistema de alertas como recordatorio de pagos automáticos del pago mínimo para ayudar a los clientes con balances altos.
* Realizar segmentación de clientes para ofrecer asesoramiento financiero personalizado acorde su comportamiento de gastos y pagos.
* Considerar aumentar los límites de crédito para los clientes "Low Risk" con baja utilización para recompensar buen comportamiento y promover lealtad de cliente.
* Implementar alertas basadas en el uso de crédito, notificando a los clientes cuando su uso exceda los parametros seguros.(Ej. Alertar cuando su balance se acerca a un porcentaje de utilización moderado o alto).
* Ofrecer planes de pago estructurados para clientes con balances altos para ayudarlos a realizar pagos más grandes.

# Referencias

Bhasin, Arjun. (2013). CC GENERAL Dataset. Kaggle. Encontrado en  https://www.kaggle.com/datasets/arjunbhasin2013/ccdata
