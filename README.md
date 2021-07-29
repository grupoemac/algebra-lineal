# Álgebra lineal (2555220)
2021, Instituto de Matemáticas, Universidad de Antioquia

## Introducción
Este es el repositorio del curso de [álgebra lineal](../main/2555220.pdf) ofrecido por el Instituto de Matemáticas a la Facultad de Ingeniería. Para los estudiantes de la Universidad de Antioquia, el curso cuenta con página moodle en la plataforma [ingeni@](http://www.ingeniaudea.co/login/index.php).

### Descripción del curso
> *El álgebra lineal es el estudio de los espacios vectoriales y de las transformaciones lineales definidas entre éstos. Es fundamental en casi todas las áreas de las matemáticas y se emplea para modelar una gran variedad de fenómenos naturales presentes en la mayoría de las ciencias y en diversos campos de la ingeniería. Este curso proporciona a los estudiantes los conceptos y las técnicas básicas para la modelación y resolución de problemas lineales, tanto en matemáticas como en otras disciplinas y sirve de fundamento para futuros cursos.*

## Clase a clase
El contenido resumido del curso es el siguiente.

| Sesión | Tema | Horas |
| :---:         | :---       | :---:          |
| 1   | Presentación del curso – Definiciones y propiedades básicas | 2 |
| 2   | Subespacio vectorial | 2 |
| 3   | Combinación lineal y espacio generado | 2 |
| 4   | Independencia lineal | 2 |
| 5   | Bases y dimensión | 2 |
| 6   | Espacios fundamentales de una matriz | 2 |
| 7   | **Parcial 1 (25%): sesiones 1 a 5** | 2 |
| 8   | Espacios fundamentales de una matriz | 2 |
| 9   | Cambio de base | 2 |
| 10  | Cambio de base (continuación) | 2 |
| 11  | Bases ortonormales y proyecciones en <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^n"> | 2 |
| 12  | Bases ortonormales y proyecciones en <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^n"> (continuación) | 2 |
| 13  | Aproximación por mínimos cuadrados | 2 |
| 14  | Espacios con producto interno y proyecciones | 2 |
| 15  | Definición y ejemplos de transformaciones lineales | 2 |
| 16  | **Parcial 2 (25%): sesiones 6 a 14** | 2 |
| 17  | El núcleo y la imagen | 2 |
| 18  | Representación matricial de una transformación lineal | 2 |
| 19  | Representación matricial de una transformación lineal (continuación) | 2 |
| 20  | Isomorfismos | 2 |
| 21  | Isometrías | 2 |
| 21  | Valores y vectores propios | 2 |
| 23  | **Parcial 3 (25%): sesiones 15 a 21** | 2 |
| 24  | Valores y vectores propios (continuación) | 2 |
| 25  | Semejanza y diagonalización | 2 |
| 26  | Aplicaciones: crecimiento poblacional y cadenas de Markov | 2 |
| 27  | Matrices simétricas | 2 |
| 28  | Diagonalización ortogonal | 2 |
| 29  | Aplicaciones: formas cuadráticas y secciones cónicas | 2 |
| 30  | Aplicaciones: formas cuadráticas y secciones cónicas (continuación) | 2 |
| 31  | La forma canónica de Jordan | 2 |
| 32  | **Parcial 4 (25%): sesiones 22 a 31** | 2 |

## Presentaciones

### Semana 1: definiciones y propiedades básicas

[semana1.pdf](../main/presentaciones/semana01/semana1.pdf)

La primera semana inicia con la presentación del curso y un repaso del tema de vectores en <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^n"> visto en cursos previos. Los ejemplos de vectores en el plano y el espacio, anteceden a las nociones abstractas de espacio vectorial y subespacio. Estas nociones son presentadas al final de la semana. La exposición incluye una lista extensa de ejemplos variados que ilustran tales conceptos.

### Semana 2: combinación lineal, espacio generado e independencia lineal

[semana2.pdf](../main/presentaciones/semana02/semana2.pdf)

La solución de sistemas de ecuaciones lineales es un tema visto en cursos previos, que conduce al concepto de combinación lineal de vectores. Durante esta semana se explora en detalle este concepto y se utiliza para la construcción de subespacios vectoriales a partir de subconjuntos finitos de vectores llamados conjuntos generadores. El objetivo es obtener conjuntos generadores con la menor cantidad de vectores posibles. Esto conduce al concepto de independencia lineal.

### Semana 3: bases y dimensión

[semana3.pdf](../main/presentaciones/semana03/semana3.pdf)

En esta semana el propósito es estudiar conjuntos finitos de vectores que cuentan con suficientes vectores para generar el espacio, pero no tantos de modo que uno de ellos pueda escribirse como una combinación lineal del resto de vectores. A un conjunto de vectores con estas características se le denomina base para el espacio  y al número de vectores se le denomina dimensión del espacio. 

### Semana 4: espacios fundamentales de una matriz

[semana4.pdf](../main/presentaciones/semana04/semana4.pdf)

Las columnas y los renglones de una matriz pueden verse como vectores de <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^n">. Estos vectores forman conjuntos que pueden ser linealmente independientes y/o generar a <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^n">. En esta semana estudiamos técnicas que nos permiten obtener bases para subespacios de <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^n"> que contienen vectores particulares.

### Semana 5: cambio de base

[semana5.pdf](../main/presentaciones/semana05/semana5.pdf)

Muchos problemas de la física y la ingeniería descritos en un sistema coordenado particular, pueden se resueltos de manera más sencilla cuando se enuncian en nuevo sistema coordenado, después de realizar un cambio de variables adecuado. Una base para un espacio vectorial proporciona un sistema coordenado para el espacio. En esta semana estudiamos matrices de cambio de base.

### Semana 6: bases ortonormales y proyecciones en  <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^n">

[semana6.pdf](../main/presentaciones/semana06/semana6.pdf)

Todo vector de <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^n"> puede expresarse de manera única como combinación lineal de los vectores de una base. Los coeficientes de estas expresiones implican cálculos dispendiosos que requieren la solución de sistemas de ecuaciones lineales. Cuando cada para de vectores distintos de la base son ortogonales, dichos cálculos se reducen consderablemente. En esta semana estudiamos bases ortonormales y proyecciones ortogonales de vectores en <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^n"> sobre subespacios. 

### Semana 7: mínimos cuadrados y espacios con producto interno

[semana7.pdf](../main/presentaciones/semana07/semana7.pdf)

El concepto de proyección ortogonal de un vector <img src="https://render.githubusercontent.com/render/math?math=\mathbf{v}"> en <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^n"> sobre un subespacio <img src="https://render.githubusercontent.com/render/math?math=H"> de <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^n">, nos permite hallar el vector en <img src="https://render.githubusercontent.com/render/math?math=H"> más próximo a <img src="https://render.githubusercontent.com/render/math?math=\mathbf{v}">. Esta idea nos proporciona un procedimiento para aproximar la "solución" de un sistema inconsistente <img src="https://render.githubusercontent.com/render/math?math=A\mathbf{x}=\mathbf{b}"> que minimiza el error cuadrático medio. La técnica es conocida como el método de mínimos cuadrados y es estudiada al inicio de la semana. Al final de la semana extendemos el concepto de ortogonalidad estudiado en <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^n"> a espacios vectoriales más generales.

### Semana 8: transformaciones lineales, núcleo e imagen

[semana8.pdf](../main/presentaciones/semana08/semana8.pdf)

Una matriz <img src="https://render.githubusercontent.com/render/math?math=A"> de <img src="https://render.githubusercontent.com/render/math?math=m\times n"> puede ser utilizada para transformar un vector <img src="https://render.githubusercontent.com/render/math?math=\mathbf{x}"> en <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^n"> en un vector <img src="https://render.githubusercontent.com/render/math?math=\mathbf{y}=A\mathbf{x}"> de <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^m"> y actuar de esta forma como una "función" de la forma <img src="https://render.githubusercontent.com/render/math?math=\mathbf{y}=T(\mathbf{x})"> de <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^n"> en <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^m">. Este tipo de funciones definidas de un espacio vectorial a otro preservan la operación de suma de vectores y la de multiplicación por escalar y reciben el nombre de transformaciones lineales. En esta semana estudiamos las transformaciones lineales y propiedades. 

### Semana 9: Transformaciones lineales: representación matricial

[semana9.pdf](../main/presentaciones/semana09/semana9.pdf)

Toda  matriz <img src="https://render.githubusercontent.com/render/math?math=A"> de <img src="https://render.githubusercontent.com/render/math?math=m\times n"> induce una transformación lineal de <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^n"> en <img src="https://render.githubusercontent.com/render/math?math=\mathbb{R}^m"> dada por <img src="https://render.githubusercontent.com/render/math?math=T(\mathbf{x})=A\mathbf{x}">. En este caso el núcleo de <img src="https://render.githubusercontent.com/render/math?math=T"> coincide con el núcleo de <img src="https://render.githubusercontent.com/render/math?math=A"> y la imagen de <img src="https://render.githubusercontent.com/render/math?math=T"> coincide con el espacio columna de <img src="https://render.githubusercontent.com/render/math?math=A">. Esto nos permite estudiar la transformación lineal por medio de la matriz <img src="https://render.githubusercontent.com/render/math?math=A">. Recíprocamente cualquier transformación lineal <img src="https://render.githubusercontent.com/render/math?math=T"> definida entre espacios vectoriales de dimensión finita se puede expresar en la forma <img src="https://render.githubusercontent.com/render/math?math=T(\mathbf{x})=A\mathbf{x}">. La matriz <img src="https://render.githubusercontent.com/render/math?math=A"> en este caso depende de la elección de bases
