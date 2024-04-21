# Predicción casos UCI-COVID

La enfermedad por COVID-19 ha sido la pandemia más reportada en los últimos años. Utilizando un dataset del Departamento de Epidemiología del Ministerio de Salud de Chile, con todos los registros de casos confirmados por COVID-19 en la población notificada entre Octubre del 2021 y Marzo del 2023, se realizaron agrupaciones de datos para comparar frecuencias, incidencias y evolución, teniendo en cuenta edades y estado de vacunación. En general, aquellos con el esquema de vacunación completo suelen tener una incidencia cruda de contagio más baja en comparación con aquellos sin el esquema completo, particularmente en las categorías de edad más altas. Lo notorio es que el aumento de los casos de contagio incide positivamente en el aumento de los casos de hospitalización, agravamiento y muerte. Un punto de inflexión es la ocupación de camas UCI que determina los aumentos del uso de recursos materiales y humanos sanitarios, aumentos de las restricciones sociales, adelanto de vacaciones e iclusive periodos de cuarentena. En relación a esto último es de interés determinar si es posible predecir dicho aumento y así estar preparados para enfrentar mejor el problema.


###Problema a resolver

Predecir el aumento del número de casos UCI y así enfrentar mejor el escenario sanitario.

###Contexto analítico

Se cuenta con un dataset de tipo CSV procedente del Departamento de Epidemiología del MINSAL Chile, que contiene datos de cantidad de casos confirmados para COVID-19, casos de hospitalizacion, casos de hospitalización en UCI, casos de defunciones, sus incidencias crudas y ponderadas, por semana epidemiológica, por cada estado de vacunación.

Se efectuarán las siguientes tareas con los datos: Leer, transformar y preparar datos para su visualización Realizar análisis y construir visualizaciones para identificar patrones

###Pregunta
***¿Cuánto influye el aumento de casos confirmados en el aumento de los casos UCI?***

- Hipotesis Alternativa: Influye positivamente, es decir a mayor número de casos de contagios, más aumentan los casos de pacientes UCI
- Hipótesis Nula: No existe relación entre el aumento de los casos confirmados de COVID, con los casos de hospitalización en UCI

###Objetivos 

Manipular los datos disponibles y hacer visualizaciones para responder a preguntas cómo:

¿Cómo aumenta el número de casos de pacientes que llegan a ser hospitalizados a medida que aumenta el número de casos resgitrados como positivos?

¿Cómo aumenta el número de casos de pacientes graves hospitalizados (UCI) a medida que aumenta el número de casos resgitrados como positivos?

¿En qué meses del año se dan más estas alzas de casos?

¿En qué grupo etario es mayor el riesgo de contagio y/o hospitalización?

¿En que tipo de estado de vacunación (vacunados o sin vacuna), se da la mayor alza de casos?
