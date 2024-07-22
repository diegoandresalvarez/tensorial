# Observaciones generales y temario del curso

## Citas para preguntas
Únicamente solicitándolas previamente, ya sea por correo electrónico o antes/después de la clase.

## Exámenes, talleres y fechas
El curso se evaluará mediante exámenes.

### Exámenes:
* **Examen 1:** 25%
  * Parte 1 (50%): Jueves, Febrero 22 (semana 3). Se harán dos preguntas una de álgebra lineal y otra del tema del Capítulo 2 visto hasta Febrero 19.
  * Parte 2 (50%): Jueves, Marzo 14  (semana 6). Se harán dos preguntas: una de cálculo vectorial y otra del resto de tema del capítulo 2 (incluso lo que no se explicó en clase) y todos los códigos de MATLAB/MAXIMA/PYTHON asociados.
* **Examen 2:** 25% Todo el Capítulo 3 (incluso lo que no se explicó en clase) y todos los códigos de MATLAB/MAXIMA/PYTHON  de los capítulos 2 y 3. ~~Lunes, Abril 15 (semana 10)~~ Jueves, Agosto 8 (semana 8).
* **Examen 3:** 25% Todo el Capítulo 4 (incluso lo que no se explicó en clase) y todos los códigos de MATLAB/MAXIMA/PYTHON asociados. Lunes, ~~Mayo 6 (semana 13)~~ Agosto 26 (semana 11).
* **Examen 4:** 25% Grandes deformaciones, ecuaciones fundamentales de la mecánica de los medios continuos. Se evaluarán también todos los códigos de MATLAB/MAXIMA/PYTHON asociados. Lunes, ~~Mayo 27~~ Septiembre 30 (semana 16).

## Descripción de la asignatura mecánica tensorial
En este curso se hará una introducción a la mecánica del medio continuo. En particular, se estudiarán los principios rectores de la mecánica de medios continuos (sólidos y fluidos) a traves de su formulación matemática por medio de tensores, en los sistemas de coordenadas espacial y material (Euler y Lagrange) y las ecuaciones fundamentales de la mecánica del medio continuo (masa, momentum, energía), de manera que se pueda comprender la formulación de toda clase de problemas de sólidos y fluidos. Se estudiarán los elementos básicos de los modelos constitutivos de Hooke, Newton y Coulomb que permiten modelar matemáticamente problemas de elasticidad, plasticidad, viscosidad, visco-elasticidad, visco-plasticidad, relajación y reptación. Se aplicarán los conceptos adquiridos a la formulación de las ecuaciones básicas de sólidos elásticos y fluidos Newtonianos.

Se espera que al final del curso, el estudiante esté en capacidad de:
* Analizar y explicar como varían las tensiones y las deformaciones al interior de un sólido elástico, para pequeñas y grandes deformaciones.
* Entender las diferentes suposiciones y limitaciones presentes en la teoría.
* Entender la deducción y rango de aplicación de ciertas formulaciones que se aplicarán más tarde en mecánica de sólidos, de suelos, de fluidos y pavimentos.

La materia se desarrollará mediante clases magistrales.

## Contenidos programático de mecánica tensorial

### 0. Repaso de diferentes temas de álgebra lineal y cálculo vectorial.
Cada estudiante debe repasar por cuenta propia los siguientes temas:
#### Repaso de álgebra lineal (teoría y ejercicios de aplicación)
* Cosenos directores
* Proyección de vectores
* Producto punto, producto cruz (con todas las propiedades que aparecen en el apéndice de las notas)
* Norma de un vector
* Matrices
* Determinantes
* Valores y vectores propios
* Espacios vectoriales
* Vectores linealmente dependientes/independientes
* Bases
* Planos y líneas rectas

#### Repaso de cálculo vectorial (teoría y ejercicios de aplicación)
* Gradiente
* Matriz jacobiana y jacobiano
* Divergencia
* Rotacional
* Diferenciales (se estudió en cálculo vectorial)
* Expansión en series de Taylor (univariada y multivariada)
* Regla de la cadena (se estudió en cálculo univariado y en cálculo vectorial)
* Campo vectorial (definición y ejemplos sencillos)

### 1. Introducción al cálculo tensorial
* Definición de tensor, notación indicial.
* Álgebra de tensores: vectores y valores principales, invariantes, ortogonalidad.
* Cálculo tensorial: gradiente, divergencia, rotacional, laplaciano.
* Tensores de órdenes superiores

### 2. Esfuerzos o tensiones
* Fuerzas másicas y fuerzas superficiales
* Tensor de esfuerzos de Cauchy. Principio de Cauchy.
* Esfuerzos cortantes y normales
* Tensor de tensiones
* Cambio de base
* Esfuerzos principales
* Círculo de Mohr en 2D y 3D para esfuerzos

### 3. Desplazamientos y pequeñas deformaciones
* Desplazamientos
* Translación y rotación rígida
* Deformaciones longitudinales y angulares, tensor de deformación infinitesimal.
* Galgas extensiométricas
* Especificación de la deformación en otras direcciones
* Rotación
* Deformaciones principales
* Tensores de estiramiento y rotación.
* Círculo de Mohr en 2D y 3D para deformaciones

### 4. Relación entre esfuerzos y deformaciones
* Materiales frágiles y materiales dúctiles: comportamiento elastoplástico, curva esfuerzo deformación.
* La ley de Hooke para materiales isótropos, anisótropos y ortótropos:
  * Los módulos de Young y Poisson.
  * Deformación de un sólido sometido a esfuerzos normales en las direcciones x, y y z.
  * Deformación de un sólido sometido a esfuerzos tangenciales.
  * Ecuaciones de Lamé
* Relación entre las direcciones principales asociadas a los esfuerzos y a las deformaciones para materiales isótropos
* Cambios de volumen y dilatación cúbica
* Teorema de la divergencia
* Modelos básicos de materiales: Newton y Coulomb
* Determinación experimental de las propiedades del material.
* Modelación unidimensional de: elasticidad, plasticidad, viscosidad, visco-elasticidad, visco-plasticidad, relajación y reptación

### 5. Desplazamientos y grandes deformaciones
* Descripciones de Lagrange y Euler. 
* Derivada material. 
* Tensor gradiente de deformación.
* Tensores de Cauchy-Green, Cauchy-Lagrange, Euler-Almansi.
* Descomposición polar. 
* Tasa de deformación, tensor de giro, vector de velocidad angular.
* Tensor gradiente de velocidad
* Derivadas materiales de líneas, áreas y volúmenes.
* Tensores de Piola-Kirchhoff

### 6. Ecuaciones fundamentales de la mecánica de los medios continuos
* Derivada material de integrales de línea, área y volumen
* Movimiento, flujo y derivada material; velocidad, aceleración, líneas de traza, tasa de deformación y vorticidad.
* Conservación de masa y ecuaciones de continuidad
* Momentum. Ecuaciones de movimiento
* Principio del momento del momentum
* Potencia de esfuerzos. 
* Ecuación de la energía.
* Primera y segunda ley de termodinámica
* Principio del trabajo virtual.

## Bibliografía básica
* Alvarez Diego A. (2024) - *Notas de clase del curso mecánica de sólidos*. En preparación.
* Álvarez-Marín, D. A. (2023a). Teoría de la Elasticidad usando Matlab y Maxima (volumen 1: fundamentos). Departamento de Ingeniería Civil, Facultad de Ingeniería y Arquitectura, Universidad Nacional de Colombia - Sede Manizales. ISBN 978-958-505-376-2. https://repositorio.unal.edu.co/handle/unal/84682
* Alvarez, Diego A. Video tutoriales en YouTube sobre teoría de la elasticidad https://www.youtube.com/channel/UCV0FtSuauv5WbcY-lLRMZ4g
* Lai, M., Krempl, E, Ruben, D.	(2010) - *Introduction to Continuum Mechanics*. Elsevier
* Oliver, X., Agelet, C. (2002) - *Mecánica de Medios Continuos para Ingenieros*.
* Bonet, J., Gil, A.J., Woods, R (2016) -* Nonlinear Solid Mechanics for Finite Element Analysis*. Cambridge.
* Mase, G., Smelser, R.E., Mase, G.E.	(2009) - *Continuum Mechanics for Engineers*.

## Otras observaciones que se quieren dejar por escrito:
### Asistencia al curso
La puerta se cerrará 10 minutos después de haber iniciado la clase (de acuerdo con el reloj del computador del salón).

### Falta a los exámenes
Siempre que usted falte a un examen, debe haber algún documento que lo exonere de dicha inasistencia. Cuando usted por algún motivo de fuerza mayor no pueda asistir al examen, usted debe avisarle al profesor con anterioridad ya sea personalmente o por correo. En esos casos en lo posible, debe demostrarlo. Por ejemplo: si le tocó viajar a su pueblo esa semana porque algo sucedió un evento familiar de trascendencia, entonces una forma de certificar que usted viajó son los tiquetes de ida y vuelta a su pueblo. Sin una excusa o una notificación previa no se repetirán los exámenes y usted tendrá como nota un cero.

### Fraude en los exámenes o trabajos
Estos se penalizarán así:

* Nota cero en el trabajo/examen en cuestión.
* Carta a la Dirección del Departamento de Ingeniería Civil reportando el suceso.
* Se pierden adicionalmente todos los privilegios que se tienen de una calificación con notas mayores a 5.0 en todas las notas obtenidas en el semestre y los puntos de la WIKI.

### "Minuciosamente" en los exámenes
En todos los exámenes se debe relacionar con palabras las fórmulas y motivar físicamente el por qué de un procedimiento o fórmula (es decir, se debe escribir la explicación suponiendo que usted está escribiendo un libro). Si no se hace esto, se le rebajará en ese punto en particular el 50% de la nota.
