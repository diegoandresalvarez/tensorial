# Observaciones generales y temario del curso

## Citas para preguntas
Únicamente solicitándolas previamente, ya sea por correo electrónico o inmediatamente después de la clase.

## Exámenes
Ver tema de los exámenes en el archivo [examenes.md](examenes.md). Los exámenes se realizarán en las fechas que se indican a continuación:
* **Examen 1:** Porcentaje: 25%. Jueves 17 de septiembre de 2026 (semena 4).
* **Examen 2:** Porcentaje: 25%. Jueves 15 de octubre de 2026 (semana 8).
* **Examen 3:** Porcentaje: 25%. Jueves 12 de noviembre de 2026 (semana 12).
* **Examen 4:** Porcentaje: 25%. Jueves 10 de diciembre de 2026 (semana 16).

En los exámenes siempre se preguntará: teoría, demostraciones, ejercicios numéricos y ejercicios de programación.

NOTA: se prohíbe en estos exámenes el uso de calculadoras Hewlett-Packard, Texas Instrument y calculadoras programables Casio.

<!---
<code style="color: #ff0000;">Se permite para los exámenes, que el profesor indique, traer una hoja tamaño carta en la cual ustedes pueden escribir (POR UN SOLO LADO) todas las fórmulas y comandos de MATLAB/MAXIMA/PYTHON que deseen. En la hoja no se pueden ni escribir programas, ni textos explicativos, ni se pueden escribir demostraciones. Dicha hoja debe ser de elaboración personal (no se pueden traer las hojas hechas por compañeros de este o semestres pasados) y debe hacerse a mano (se prohíbe explícitamente traer fotocopias/impresiones/reducciones).</code>
--->

## Descripción de la asignatura mecánica tensorial (mecánica de medios continuos)
En este curso de pregrado se estudiarán los principios rectores de la mecánica de medios continuos. Se estudiará el tensor de esfuerzos de Cauchy, las pequeñas y grandes deformaciones en los sistemas de coordenadas espacial y material (Euler y Lagrange), las ecuaciones de balance y conservación de masa, momentum (linear y angular) y energía, y las ecuaciones constitutivas para sólidos elásticos y fluidos Newtonianos; estos conceptos son aplicables por igual a sólidos y fluidos. Esto aporta al perfil profesional una capacidad analítica crítica: no solo aplicarán fórmulas, sino que entenderán la deducción teórica y las limitaciones físicas detrás de los problemas ingenieriles. En lo actitudinal, fortalece rigor analítico, abstracción, autonomía intelectual y capacidad para cuestionar modelos matemáticos.

Se espera que al final del curso, el estudiante esté en capacidad de:
* Analizar y explicar como varían las tensiones y las deformaciones al interior de un sólido elástico, para pequeñas y grandes deformaciones.
* Entender las diferentes suposiciones y limitaciones presentes en la teoría.
* Entender la deducción y rango de aplicación de ciertas formulaciones que se aplicarán más tarde en mecánica de sólidos, de suelos, de fluidos y pavimentos.

Para su desarrollo, es indispensable dominar álgebra lineal, cálculo vectorial, física mecánica y estática.

La materia se desarrollará mediante clases magistrales.

## Contenidos programático

### 0. Repaso de diferentes temas de álgebra lineal y cálculo vectorial

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
* Curvas paramétricas
* Diferenciales (se estudió en cálculo vectorial)
* Optimización de funciones multivariadas sin restricciones
* Optimización de funciones multivariadas con restricciones de igualdad (multiplicadores de Lagrange)
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
* Alvarez-Marín, Diego A. (2026). *Notas de clase del curso mecánica de sólidos*. En preparación.
* Alvarez-Marín, Diego A. (2026). *Notes for a course on continuum mechanics*. En preparación.
* Álvarez-Marín, D. A. (2023a). Teoría de la Elasticidad usando Matlab y Maxima (volumen 1: fundamentos). Departamento de Ingeniería Civil, Facultad de Ingeniería y Arquitectura, Universidad Nacional de Colombia - Sede Manizales. ISBN 978-958-505-376-2. https://repositorio.unal.edu.co/handle/unal/84682
* Alvarez, Diego A. Video tutoriales en YouTube sobre teoría de la elasticidad https://www.youtube.com/channel/UCV0FtSuauv5WbcY-lLRMZ4g
* Lai, M., Krempl, E, Ruben, D.	(2010) - *Introduction to Continuum Mechanics*. Elsevier
* Oliver, X., Agelet, C. (2002) - *Mecánica de Medios Continuos para Ingenieros*.
* Bonet, J., Gil, A.J., Woods, R (2016) -* Nonlinear Solid Mechanics for Finite Element Analysis*. Cambridge.
* Mase, G., Smelser, R.E., Mase, G.E.	(2009) - *Continuum Mechanics for Engineers*.

## Otras observaciones que se quieren dejar por escrito:

### Falta a los exámenes
Siempre que usted falte a un examen, debe haber algún documento que lo exonere de dicha inasistencia. Cuando usted por algún motivo de fuerza mayor no pueda asistir al examen, usted debe avisarle al profesor con anterioridad ya sea personalmente o por correo. En esos casos en lo posible, debe demostrarlo. Por ejemplo: si le tocó viajar a su pueblo esa semana porque algo sucedió un evento familiar de trascendencia, entonces una forma de certificar que usted viajó son los tiquetes de ida y vuelta a su pueblo. Sin una excusa o una notificación previa no se repetirán los exámenes y usted tendrá como nota un cero.

### Dispositivos electrónicos durante los exámenes
Durante los exámenes, los celulares, relojes inteligentes, gafas inteligentes, y en general cualquier dispositivo electrónico debe permanecer apagado y guardado en el morral. Si el estudiante porta alguno de estos dispositivos electrónicos en sus manos, bolsillos o en cualquier lugar diferente del morral, independientemente de si está apagado o encendido, esto resultará en la anulación del examen. Esta medida se aplica como parte de las normas contra el fraude académico, ante la proliferación del fraude con la tecnología.

### Fraude en los exámenes o trabajos
Estos se penalizarán así:
* Nota cero en el trabajo/examen en cuestión.
* Carta al Consejo de Facultad reportando el suceso.
<!---
* Se pierden adicionalmente todos los privilegios que se tienen de una calificación con notas mayores a 5.0 en todas las notas obtenidas en el semestre y cualquier bonificación adicional de notas que el profesor decida otorgar al grupo.
--->

### "Minuciosamente" en los exámenes
En todos los exámenes se debe relacionar con palabras las fórmulas y motivar físicamente el por qué de un procedimiento o fórmula (es decir, se debe escribir la explicación suponiendo que usted está escribiendo un libro). Si no se hace esto, se le rebajará en ese punto en particular el 50% de la nota.
