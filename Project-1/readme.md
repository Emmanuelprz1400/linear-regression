# Response Time Paris Fire Brigade

Los datos fueron obtenidos de un Challenge en el que se pretende predecir el tiempo de respuesta y el tiempo de llegada de los bomberos de acuerdo a distintas características del incidente como por ejemplo la distancia, el tipo de vehículo utilizado, la altura del incidente (en caso de ser un edificio).

Pueden consultar los detalles en el siguiente [link](https://paris-fire-brigade.github.io/data-challenge/challenge.html).

Los datos se se encuentran además en esta [carpeta compartida](https://drive.google.com/drive/folders/1ebXRdrRmijtlEv19ndsHpkTLaXgQo9Wt?usp=sharing).

La hipótesis sobre estos datos que nosotros planteamos es la siguiente: predecir el tiempo de respuesta a un incidente puede ser predicho utilizando una regresión.

La variable que buscaremos predecir es el tiempo que tarda en llegar el equipo de rescate desde que sale el vehículo hasta la presentación en el lugar del siniestro (delta departure - presentation)

Esta predicción puede verse afectada gravemente por la presencia de outliers en nuestros datos, por ejemplo aquellos causados por manifestaciones, atentados o en general accidentes que dificulten la movilidad.
