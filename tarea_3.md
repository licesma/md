![](./images/itam_logo.png)

M. Sc. Liliana Millán Núñez liliana.millan@itam.mx

Noviembre 2020

### Tarea 3

Tarea **individual**

A entregar máximo el **30 de noviembre de 2020 a las 23:59:59 CST**. Enviar por correo electrónico a liliana.millan@itam.mx con el subject `md_tarea_3`.

Utilizando los datos de [clientes de un centro comercial](https://www.dropbox.com/s/hk08dou8xahrccj/Mall_Customers.csv?dl=0) generarás *clusters* a través del algoritmo de K-means.

Utilizando un `random seed` de `20201122`:

1. Convierte la columna `gender` a binaria cambiando `male` a `0` y `female` a `1`.
2. Escala los datos de edad, salario y el score de gasto con el método `scale` de `sckikit-learn`.
3. Genera *clusters* utilizando `k-means` con la siguiente configuración de hiperparámetros:
  + Grupos: 3,4,5,6,7,8,9,10,13
  + Máximo de iteraciones: 50
4. Genera una gráfica de codo e indica cuál es el número de grupos óptimos
5. Cuántos elementos tiene cada grupo
6. Cuáles son los centroides de cada grupo
7. Cuántas iteraciones utilizó el algoritmo
8. Grafica en la escala original de los datos el salario y el score de gasto utilizando un color por cada grupo e incluyendo los centroides.
9. Genera un describe a cada grupo, ¿cuáles son las 3 características más importantes de cada grupo con respecto a las variables con las que realizamos los grupos?


¿Qué se entrega?

Tu notebook `ipynb` con el código que ocupaste y el texto asociado.
