# Cross-Entropy

#Solo estoy chequeando que ahora me ande bien

#En modo de resumen

Para evaluar el modelo con la entropia cruzada vamos a necesitar:

Las variables Yi que indican la clase real de la observacion (proviene de y_train)

La probabilidad asignada de pertenencia a la clase Yi por cada observacion Xi -> La probabilidad que asigna el modelo a x_train


formula= (Clase real de la observacion x log(probabilidad que asigno el modelo de pertenecer a la clase Yi))

evaluacion = sumatoria de (dato proveniente de y_train) x log ( dato proveniente x_ train con el modelo aplicado?)

