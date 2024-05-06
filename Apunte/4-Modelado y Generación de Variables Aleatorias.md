
---

# Variables Aleatorias

Mediante la observación de eventos reales del sistema real se obtienen datos y luego se halla la función de probabilidad (distribución de probabilidad) que explica el comportamiento observado, generando un modelo que lleva a eventos simulados.

## Prueba de Chi Cuadrado

El procedimiento general de la prueba:

1. Se deben tener al menos **30 datos** de la variable aleatoria a analizar. Para tomar los 30 datos, estos deben estar bajo las mismas condiciones. Si por algún motivo no se puede completar la toma de datos el mismo día, y se quiere seguir tomando en otro momento, se deben considerar que deben estar en las mismas condiciones que el primer grupo de datos.

2. Calcular la **media** y **varianza** de los datos.

3. Crear un **histograma** de *m=raíz(n)* intervalos, y obtener la frecuencia observada en cada intervalo *Oi*.

Hay que comparar el resultado del histograma obtenido con alguna distribución de histograma conocida.

El objetivo es saber cuál es la distribución de probabilidad que determina el sistema.

Una vez que se sabe qué tipo de distribución puede ser, se procede a la generación de valores para las variables aleatorias.
![[Pasted image 20240409200759.png]]
## Generación de Valores para las Variables Aleatorias

Cuando se habla de fenómenos continuos, se usan **funciones de densidad**. Cuando se habla de fenómenos de tipo discreto, se habla de **distribuciones de probabilidad**.

### Métodos para Generar Variables Aleatorias

#### Método de la Transformada Inversa

Se usa para simular variables aleatorias continuas, mediante la función acumulada y la generación de números pseudoaleatorios.

**Función Acumulada:** función de distribución de probabilidad, varía entre 0 y 1. Es una integral entre los límites inferior y superior de la función de densidad de la distribución uniforme.

Pasos:
![[Pasted image 20240409200715.png]]
Se invierte la función acumulada y se obtiene el valor de la variable aleatoria *x*. Es importante la obtención de los valores pseudoaleatorios, si tienen una tendencia la función acumulada se verá afectada.

#### Distribución Uniforme

Cada variable tiene la misma probabilidad de ocurrencia.

Si la función de distribución es compleja, si se quiere invertir termina siendo mucho más compleja, por eso se pasa al siguiente método.

#### Métodos del Rechazo

Se basa en dos números uniformes. Se halla y evalúa la función de probabilidad y se compara con el segundo número uniforme. Si la función es mayor al segundo número, se acepta el número generado. Sino, se vuelve a determinar el número aleatorio.

Para los distintos valores de *x*, se generan la función de probabilidad y la función acumulada.

---
#### Tags
- #Modelado #Variables_Aleatorias #Pruebas_Estadísticas
#### Continua
- [[5-Identificacion y generacion de Variables Aleatorias]]