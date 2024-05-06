
---

- Fecha: **12 marzo 2024**

---

## Elementos del Sistema (del Modelo de Simulación)

### Entidades
- Representación de los flujos de entrada a un sistema.
- Responsable de cambiar el estado del sistema.
- Ejemplo: los clientes que llegan a la caja de un banco.

### Estado del Sistema
- Condición que guarda el sistema en un instante dado.
- Se compone de:
  - Variables o características de operación puntuales.
  - Variables o características de operación acumuladas o promedio.
- Ejemplo: aula de clase.
  - Variables características del aula: cantidad de alumnos, temperatura, luminaria, profesores, pupitres, duración de la clase, entre otros.

### Evento
- Genera un cambio de estado actual del sistema.
- Tipos de eventos:
  - Actuales: suceden en un momento dado.
  - Futuros: determinados a partir de los eventos actuales, pueden tener una probabilidad de ocurrencia.

### Localización
- Lugares donde la entidad puede detenerse para ser atendida o esperar.

### Recursos
- Aspectos o dispositivos ubicados en diferentes localizaciones para llevar a cabo una actividad.

### Atributos
- Variables cuyos valores se crean y modifican.
  - Continuas.
  - Discretas.

### Reloj de la Simulación
- Contador de tiempo de la simulación.
  - Reloj de simulación absoluto: parte de cero y termina en un tiempo total de simulación.
  - Reloj de simulación relativo: considera el lapso entre dos eventos, permite analizar intervalos.

## Aplicaciones de la Simulación
- Procesos de manufacturas.
- Plantas industriales.
- Sistemas públicos.
- Sistemas de transportes.

## Ventajas de la Simulación
- Permite analizar un sistema sin necesidad de crearlo.
- Comprimir o expandir el tiempo según la velocidad de evolución del sistema.
- Ayuda a entender el funcionamiento de un sistema y explorar posibilidades.
- Facilita la identificación de problemas y restricciones.
- Existe una formulación matemática aunque obtener una solución analítica puede ser difícil.

## Desventajas de la Simulación
- El desarrollo del modelo puede ser costoso y laborioso.
- Los resultados pueden ser mal interpretados o llevar a errores.
- Puede ser utilizada en situaciones donde no corresponda.
- La precisión de los resultados puede ser difícil de determinar.

## Etapas de una Simulación
1. Formulación del problema.
2. Definición del sistema.
3. Formulación del modelo.
4. Colección de datos.
5. Implementación del modelo en la computadora.
6. Verificación.
7. Validación.
8. Diseño de experimentos.
9. Experimentación.
10. Interpretación.
11. Implementación.
12. Documentación.

## Elementos Claves a Considerar
- Conceptualizar un modelo requiere conocimientos del sistema y juicio de ingeniería.
- El modelado es un proceso en evolución.
- Un buen modelador debe saber remodelar.
- El problema o la declaración del problema es el elemento de control primario.

## Números Pseudoaleatorios
- Necesarios para generar valores de variables aleatorias.
- Deben ser generados de forma totalmente aleatoria.
- Pruebas estadísticas para números aleatorios: media, varianza, uniformidad, independencia.

---
#### Etiquetas
#Simulación #Aplicaciones #Ventajas #Desventajas #Números_Pseudoaleatorios

#### Enlaces
- Continua -> [[3-Modelos de Atención Stock y Generación de Números Pseudoaleatorios]]
