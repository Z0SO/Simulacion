

---

La identificación de las variables aleatorias es crucial para comprender el funcionamiento de un sistema. El estado del sistema se define por los valores de estas variables, y en el caso de la simulación, al menos una de ellas exhibe un comportamiento aleatorio o probabilístico.

### Determinación de la Distribución de una Variable Aleatoria

Para determinar la distribución de una variable aleatoria, es necesario observar el sistema y obtener datos reales. A partir de estos datos, buscamos una función de distribución de probabilidad (fdp) que explique su comportamiento. Algunas consideraciones importantes son:

- La suma de las probabilidades asociadas a todos los valores posibles de la variable es uno.
- La probabilidad de cada valor posible de la variable es mayor o igual a cero.
- El valor esperado de la distribución es la media, que estima la verdadera media de la población.

#### Procedimiento para Determinar la Distribución

1. Obtener al menos 30 datos de la variable aleatoria.
2. Calcular la media y la varianza de los datos.
3. Crear un histograma y obtener la frecuencia observada en cada intervalo.
4. Establecer la hipótesis nula con una distribución de probabilidad que se ajuste al histograma.
5. Calcular la frecuencia esperada a partir de la función de probabilidad propuesta.
6. Calcular el estadístico de prueba.
7. Definir el nivel de significancia (alfa) y determinar el valor crítico.
8. Comparar el estadístico de prueba con el valor crítico para aceptar o rechazar la hipótesis nula.

### Generación de Variables Aleatorias

Existen varios métodos para generar valores para las variables aleatorias, entre ellos:

- Método de la transformada inversa.
- Método del rechazo.
- Métodos empíricos especiales.
- Uso de tablas.

#### Método de la Transformada Inversa

Este método se emplea para variables aleatorias continuas y se basa en la función acumulada F(x) y números pseudoaleatorios. Los pasos a seguir son:

1. Definir la función de densidad acumulada F(x).
2. Calcular la función acumulada F(x).
3. Despejar la variable aleatoria x y obtener la función acumulada inversa.
4. Generar las variables aleatorias x, sustituyendo valores con números pseudoaleatorios en la función acumulada inversa.

---

### Etiquetas

#Identificación #Variables_Aleatorias #Generación_Aleatoria
### Enlaces
- Continua -> [Siguiente Clase](enlace_a_siguiente_clase.md)
