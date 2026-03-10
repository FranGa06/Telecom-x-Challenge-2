Challenge 2 - Telecom X (IA y Predicción de Bajas)
BUenas tardes, esta es la segunda parte del proyecto de Telecom X. Esta vez el objetivo fue meterme con la inteligencia artificial para tratar de predecir qué clientes tienen más probabilidades de irse de la empresa antes de que pase.

Siguiendo los pasos de las clases, resultó en lo siguiente. 

Encoding: Borré el id del cliente porque no servía para predecir nada y pasé todas las palabras a números con get_dummies para que los modelos entiendan la inforomacion.

SMOTE: como había mucha gente que se quedaba y poca que se iba, usé este método para "inventar" casos de bajas y que el modelo aprenda parejo de los dos grupos.

Gráficos: armé un mapa de calor para ver cómo se relacionan las cosas y usé boxplots para ver el tiempo que duran los clientes y el dinero que gastan.

Resultados de la IA
probé con la Regresión Logística y Random Forest y este último fue el que mejor detectó a los que se van. Lo que más influye para que la gente deje la empresa es:

El contrato: Con diferencia, las personas que mas dejan el servicio son los que pagan mensualmente. 

Tiempo de contratación: cuanto menos tiempo lleva el cliente en la empresa, más riesgo hay de que se dé de baja.

Servicio de fibra: me llamó la atención que los que tienen fibra óptica se van mucho más seguido que los de DSL. Podría indicar que el servicio es muy caro o que funciona mal.

Sugerencias finales
Prestarle más atención a los clientes nuevos durante los primeros meses para que no se vayan rápido.

Tratar de que la gente pase a contrato anual dándoles algún beneficio o descuento.

Revisar el servicio de fibra óptica comparado con el DSL.
