
---

Fecha: **18 mar - 2024**

---

 TPI: Modelos de Atención para la Entrega de Termos del Centro de Estudiante, Control de Stock

### Características de los números pseudoaleatorios

- Uniformemente distribuidos: Para que los números que se generen tengan una probabilidad de ocurrencia uniforme, es decir que no existan números “preferidos” que aparezcan más veces que otro.
- Estadísticamente independientes: la ocurrencia de uno no influya la ocurrencia del otro
- Características del tipo práctico:
  - Reproducibles
  - Periodo largo sin repetición
  - Generados a través de un método largo
  - No debe precisar de excesiva capacidad de almacenamiento en la computadora

### Generacion de numeros pseudoaleatorios

*Ya no se usan los siguientes métodos*

#### Método congruencial mixto 
(el método no asegura que los números cumplan las características)

**![](https://lh7-us.googleusercontent.com/TBiZBvLzWnwgcJaUoCOnFxqe5_hn-fmngOd-F6gk10xwGm6aUANks63GjiJ0_C3TeV9J9sS9_9aNo-TlftQ7TgzejJIz7SxyysNkfmpfpju6pLXWAcUD8FMgQ6kSH4nJ-xqwElXzG4np1A9kyrZjraI)**

#### Metodo congruencial multiplicativo

**![](https://lh7-us.googleusercontent.com/wqsCFlND2URMo-ksb5F8YpO9Usr-ggeVb-Knsc-0TBlW6UZJFcVGzD2lM1AKIjI8T9Kvb2_mWYEV54FAyGBBhUpmXPZ57mYsHdEdpRzqcRr83QUWX1SxUaLGKciwGU7CBipjxV4EYdc-H-09TMAF5Hg)**
### Pruebas estadísticas para números aleatorios

Para comprobar si un conjunto de números pseudoaleatorios entre cero y uno cumplen con las propiedades de los números aleatorios

Los conjuntos se obtienen con métodos modernos (excel)

Sirven para comprobar la distribución de probabilidad uniforme de los conjuntos de números aleatorios
- **Prueba de medias**: la media de una distribución uniforme es 0.5
- **hipótesis inicial**: el conjunto de números tiene una media esperada de 0.5

**![](https://lh7-us.googleusercontent.com/s81fueI4tYvsac0i-QHg-6H3CJdOl9TmabZu1loSzbW1-jPolH0pdXHUizWmUv0fjqAn8iANptZpw3yezpHkrvnurTjOwn9pQGFvHsi_BsSRe7zpBXlGLqQzE1cc8tPvAB7T2QtshU1x1_VBNCLgDU8)**
-  **Prueba de varianza**: La varianza tiene un valor de 1/12 (usa chi cuadrado)

**![](https://lh7-us.googleusercontent.com/xEKIKLPczv3VPz5nuFCMcCOWe8jwWh38XB1bNO63YWOYpqpUz59Vv0ZFgyz0zgYXFjyCsA0a3jC-YgV_mA6Hm89VFVvpaITJ5qDp7xL-6sph8X__KQhnC_RVvikV_QMPVM8bPvIOZwpAcKPuBzpq874)**

si se cumple la hipótesis H1 se puede descartar la hipótesis, por lo tanto, se descarta el conjunto

**![](https://lh7-us.googleusercontent.com/5ksgZzeOwBuw1jvICnLQxD-PzQeuC2Tj6_lopnCAdyJAcGzrstsCD5O5UeeIi0Mx2q8-bsCvSgQVqonl02fe_Bn2NvwdEgXgyCaAe2UNe1y3_0IpzS9d5T9Kvms3B88HWBH3e8eR00NBYkE5IZv_fDw)**

**Alfa**: error aceptable, con un alfa de 0.5 o 5% es aceptable el error
si la varianza se encuentra entre los límites se acepta la hipótesis inicial, sino se descarta la hipótesis, por lo tanto, se descarta el conjunto

Si pasa ambas pruebas se puede decir que el conjunto es uniforme.

#### Prueba de uniformidad

- **Prueba *chi* cuadrado**: si el valor es mayor al valor de tabla se rechaza el conjunto, por lo tanto, se descarta el conjunto
- **Prueba de independencia**: Se deben establecer hipótesis
**![](https://lh7-us.googleusercontent.com/0qVM2Bf7SzYOzN7iSj6i_makX_knnL4AZUQlZq_qLTgwIs7NO4QVIbirTG2ye9WHi6chbAB1lSgmxHR6jL-x0jbAA2TTDuKm_MhDwikBp38mo1-zQxNVVYgsVYpKzXABejJWlhY7p8KHzKvL_Wzi_GY)**
- **Prueba de series**: comprobar independencia entre números consecutivos
**![](https://lh7-us.googleusercontent.com/WZD284k8T2jmm4YZYFpVuHLMoIDWWhneZP23gqf_b00tkoUJwRn7kcHHsOlN0XCsZnLDjLeVtfwjbi2Zl7YDgI7hfz1j7ly7LLojoEgepFdMZ6w665SGZBoe52JKUTV0XCIyATvwP5q6Qj9RkAmMqZQ)**
- **Estadio de prueba**: comprobación de las hipótesis
**![](https://lh7-us.googleusercontent.com/EmMylgPZ2UwPq0YsZv1qb-XrauIheb1UAWCO38hBNHr5t77dPfmRlDsYjLLiEcwmDpapDD4mIHxxc6ILO14WqlrC0USGHIvQ9f81GcCV_4x5tfyxGxQi8dwBT6GdZaDCiccanqRv56mgGUhT4jw1uXw)**
- Si el estadio de prueba es menor al estadio de tablas, no se puede rechazar la hipótesis

---

#### Etiquetas
#Simulación #Modelos_de_Atención #Control_de_Stock #Números_Pseudoaleatorios #Pruebas_Estadísticas
#### Enlaces
- Continua -> [[4-Modelado y Generación de Variables Aleatorias]]
