![](../images/itam_logo.png)

M. Sc. Liliana Millán Núñez liliana.millan@itam.mx

Noviembre 2020

## Aprendizaje no supervisado

### Agenda

+ Aprendizaje no supervisado
+ Modelos de agrupación
  + H-Clust
  + K-Means


### Aprendizaje no supervisado

En el aprendizaje no supervisado a diferencia del aprendizaje supervisado no hay de antemano una respuesta correcta con la que podamos **entrenar** un modelo, aquí no sabemos cuál es el resultado esperado, no hay etiqueta asociada a la respuesta y por lo tanto no hay **entrenamiento** del modelo.

Muchos de los problemas en el mundo real son de este tipo de aprendizaje pues es muy costoso generar información con la que se permita *etiquetar* las observaciones para volverlo problema de aprendizaje de máquina supervisado. Por ejemplo: Para poder hacer un modelo de clasificación de fraude primero tuvimos que haber registrado fraude —sin saberlo— y luego tuvimos que haber puesto a humanos a *calificar* cada observación para definir si era un fraude o no... esto es muy costoso en tiempo y en dinero, porque tuvimos que haber dejado pasar fraude y porque tuvimos que tener humanos haciendo el etiquetado manualmente.

Generalmente lo que sucede es que no tenemos etiquetas asociadas/generadas e iniciamos con modelos de aprendizaje no supervisados para después convertir el problema a supervisado —de ser posible—. Los modelos que forman parte del aprendizaje no supervisado son:


+ **Modelos de agrupamiento**: Queremos encontrar grupos en el set de datos que tengan características en común. Por ejemplo: perfiles de audiencias, perfiles de clientes, perfiles de algoritmos, perfiles de compradores, perfiles de lectores, perfiles de vendedores, perfiles de ciudadanos, etc. El objetivo consiste en identificar el número de grupos que existen en el set de datos y las características propias de cada uno.

+ **Modelos de asociación**: Queremos encontrar reglas que nos indiquen qué cosas pasan *juntas* o están asociadas en el conjunto de datos que tenemos, implica conocer un poco del comportamiento de los datos —también los de agrupamiento—. El objetivo consiste en identificar reglas de asociación observables en el *set* de datos.


### Métodos de agrupamiento

Entre los algoritmos que existen para identificar grupos en un *set* de datos están:

+ K-means
+ Dendrogramas
+ SOM (Self Organized Maps)


### Métricas de desempeño

#### Con etiquetas


#### Sin etiquetas
