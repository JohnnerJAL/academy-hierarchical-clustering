# Análisis del modelo Hierarchical Clustering

### Descripción de los Datos
El dataset contiene información sobre 200 clientes, incluyendo las siguientes características:

*CustomerID*: Un identificador único para cada cliente.
*Gender*: El género del cliente (Male o Female).
*Age*: La edad del cliente.
*Annual Income*: El ingreso anual del cliente.
*Spending Score (1-100)*: Una puntuación asignada por el centro comercial en función del comportamiento de gasto del cliente.

### Exploración de los Datos
- El dataset no tiene valores faltantes.
- La distribución de género muestra que hay 112 mujeres y 88 hombres.
- La edad de los clientes varía entre 18 y 70 años.
- El ingreso anual oscila entre 15k y 137k dólares.
- La puntuación de gasto varía entre 1 y 99.

### Clustering Jerárquico
El clustering jerárquico se realizó utilizando el método de enlace de Ward. Se generó un dendrograma para visualizar las distancias entre los clusters y se decidió utilizar 3 clusters. Los resultados del clustering fueron evaluados con las siguientes métricas:

Silhouette Score: 0.461
Calinski-Harabasz Index: 143.78

*Estas métricas indican una separación razonable entre los clusters.*

### Visualización de los Clusters
Para visualizar los clusters, se utilizó un scatter plot que muestra la relación entre el ingreso anual y el gasto.
