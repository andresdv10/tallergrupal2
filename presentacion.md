# Guion para Exposición: Cálculo Integral en la Ingeniería

**Tema:** Cálculo Integral en la Ingeniería: Áreas y Volúmenes
**Integrantes:** Juan Pablo Arenas Montoya, Jaime Andres Botero Ochoa, Henry Caicedo Rodriguez

---

## Parte 1: Fundamentos y Conceptos (Expositor 1: Juan Pablo Arenas Montoya)

### Diapositiva 1: Título

**(Inicio de la presentación)**

"Buenos días a todos. Hoy vamos a explorar una de las herramientas matemáticas más importantes para la ingeniería: el **Cálculo Integral**, y nos enfocaremos en su aplicación para el cálculo de áreas y volúmenes."

### Diapositiva 2: Introducción - La Necesidad de Precisión

"La ingeniería moderna, desde el diseño de un puente hasta una misión espacial, exige una precisión casi perfecta. Un pequeño error de cálculo puede tener consecuencias catastróficas. Además, la optimización de recursos es fundamental; cada centímetro de material cuenta."

"Pero, ¿cómo medimos con exactitud las formas complejas y curvas del mundo real? La respuesta está en el **Cálculo Integral**."

### Diapositiva 3: Conceptos - La Suma de Partes Infinitesimales

"El fundamento teórico detrás del cálculo de áreas de superficies curvas es la **Suma de Riemann**. La idea es simple pero poderosa: dividimos una forma compleja en un número infinito de rectángulos muy pequeños."

"La suma del área de todos estos rectángulos nos da una aproximación del área total. El cálculo integral lleva este concepto al límite: cuando el ancho de los rectángulos tiende a cero, la suma se convierte en el valor exacto del área. Esto se formaliza con la integral definida:

$$ 	ext{Área} = 
int_{a}^{b} f(x) \,dx $$

Donde f(x) representa la altura de la curva en cada punto."

### Diapositiva 4: Extensión a Volúmenes

"Este mismo principio de 'dividir y conquistar' se aplica para calcular volúmenes de sólidos irregulares. En lugar de rectángulos, usamos 'rebanadas' de un grosor infinitesimal."

"Si conocemos una función A(x) que describe el área de la sección transversal del sólido en cualquier punto, podemos 'sumar' todas esas áreas a lo largo de un eje para obtener el volumen total. La fórmula es:

$$ V = 
int_{a}^{b} A(x) \,dx $$

Con esto, podemos calcular el volumen de casi cualquier forma tridimensional. A continuación, mi compañero Jaime les hablará sobre los desafíos de aplicar estos conceptos en la práctica."

---

## Parte 2: Desafíos y Aplicaciones Prácticas (Expositor 2: Jaime Andres Botero Ochoa)

### Diapositiva 5: Desafíos de la Aplicación Práctica

"Gracias, Juan Pablo. Ahora que entendemos la teoría, hablemos de los desafíos en el mundo real."

"Primero, el **Modelado Matemático**. Los objetos reales rara vez se describen con funciones simples. Los ingenieros deben usar datos de tecnologías como escáneres 3D para construir un modelo matemático preciso."

"Segundo, la **Complejidad Analítica**. Las funciones que describen objetos reales suelen ser tan complejas que es imposible resolver su integral a mano."

"Por esto, en la práctica, recurrimos a **Soluciones Numéricas**. Usamos software especializado que implementa métodos como la regla de Simpson o el Análisis de Elementos Finitos para aproximar el valor de la integral con una precisión increíble."

### Diapositiva 6: Caso de Estudio - Análisis Estructural de una Presa

"Para ilustrar estas ideas, analicemos un caso de estudio: el diseño de una presa de hormigón. Aquí, la precisión no es solo una cuestión de costos, sino de seguridad."

### Diapositiva 7: Aplicación 1 - Cuantificación de Materiales

"La primera aplicación es calcular la cantidad de material necesario. Usando integrales triples, podemos determinar el volumen exacto de la estructura de la presa."

"Este cálculo es la base para estimar los costos del hormigón y para planificar toda la logística del proyecto. Un error aquí podría costar millones."

"Ahora, mi compañero Henry continuará con otras aplicaciones críticas del cálculo integral en este mismo caso de estudio."

---

## Parte 3: Análisis Avanzado y Conclusión (Expositor 3: Henry Caicedo Rodriguez)

### Diapositiva 8: Aplicación 2 - Cálculo de Fuerza Hidrostática

"Gracias, Jaime. Además de los materiales, debemos entender las fuerzas que actúan sobre la presa. La presión del agua no es constante; aumenta con la profundidad."

"Para calcular la fuerza total que el agua ejerce sobre la cara de la presa, integramos esta presión variable sobre toda la superficie sumergida. La fórmula es:

$$ F = 
int_{c}^{d} ho g h(y) w(y) \,dy $$

Este cálculo es vital para asegurar que la estructura pueda soportar la presión del embalse."

### Diapositiva 9: Aplicación 3 - Análisis de Estabilidad

"Finalmente, no solo importa cuánta fuerza se aplica, sino dónde se aplica. Necesitamos encontrar el **centro de presión**, que es el punto donde actúa la fuerza resultante del agua."

"Este punto se calcula con otra integral, que pondera la presión según su posición. Un cálculo incorrecto del centro de presión podría hacer que la presa se vuelque. Por lo tanto, es fundamental para diseñar una base estable."

### Diapositiva 10: Conclusión

"En conclusión, el cálculo integral es mucho más que un tema académico. Es un pilar fundamental de la ingeniería moderna."

"Nos proporciona el lenguaje para modelar la complejidad del mundo físico y nos permite analizar, predecir y cuantificar con la precisión necesaria para construir soluciones que sean **seguras, eficientes y económicamente viables**."

"Cada gran obra de ingeniería que vemos es un testimonio del poder de este método. Muchas gracias."

### Diapositiva 11: Bibliografía y Preguntas

"Aquí pueden ver algunas de las fuentes que utilizamos para nuestra investigación. Ahora, abrimos el espacio para sus preguntas."