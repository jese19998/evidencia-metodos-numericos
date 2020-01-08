# evidencia-metodos-numericos
Objetivo de la materia:
La asignatura de métodos numéricos aporta al perfil del ingeniero mecatrónico la capacidad de aplicar herramientas matemáticas, computacionales y métodos experimentales en la solución de problemas para formular modelos, analizar procesos y elaborar prototipos.
  La asignatura requiere que el alumno haya cursado cálculo diferencial y cálculo integral, así como Programación Básica.Introducción a Python
Python es un lenguaje de Programación orientados a  objetos que fue desarrollado a finales de los 80’s como un  lenguaje de tipo script. Python tiene el objetivo de ser un lenguaje para el desarrollo rápido de aplicaciones en ingeniería. Los programas de Python no son compilados, si no que trabajan bajo un intérprete.
Python tiene algunas ventajas sobre otros lenguajes de programación como:
	Python es un software de código abierto, lo que quiere decir que es libre y gratuito y es concluida en todas las computadoras con distribuciones Linux o Mac.
	Python puede correr sus scripts en todas las plataformas (Windows, Linux, Macos) sin tener que modificar ninguna parte del programa.
	 Python es fácil de aprender y produce un código más amigable que otros lenguajes.


VARIABLES
En la mayoría de lenguajes el nombre de una variable representa un valor de un determinado tipo guardado en una ubicación de memoria. El valor puede cambiar, pero no el tipo. Esto no pasa en Python ya que sus variables son tapadas dinámicamente. Una sesión del intérprete de Python cuyo pront son 3 símbolos de mayor que (>>>) ilustra esta característica. Un comentario en Python debe comenzar con el signo “#”.


CADENAS
Una cadena es una secuencia de caracteres encerrada entre apostrofes, las cadenas son concatenadas con el operador “+” mientras que el operador es usado para extraer una porción de la cadena.TUPLA
Una tupla es una secuencia de objetos arbitrarios separados por comas “ , ” y encerrados entre paréntesis “ (,) ”. Si la tupla contiene un solo objeto, una coma al final del objeto será necesaria; por ejemplo x= (2,).

>>> rec = ('Smith', 'John', (6,23,68)) # Esta es una tupla 
>>> apellido, nombre, fecha de nacimiento = rec # Desempacando la tupla 
>>> print (nombre) 
John
> >> año de nacimiento = fecha de nacimiento [2] 
>>> print (año de nacimiento) 
68 
>>> nombre = rec [1] + '' + rec [0] 
>>> print (nombre)
 John Smith
 >>> print (rec [0] : 2])

 ('Smith', 'John')
                                ¿Que es una lista? 
                                Una lista es similar a una tupla, sin embargo, sus elementos y su longitud pueden cambiar. Una lista es identificada por que sus datos están encerrados en corchetes.
a • append (4.0)
Se puede determinar la longitud de una lista con el comando “Len”, por ejemplo:
(listan ant)
Print (len(a))
También se puede modificar elementos internos en una lista, por ejemplo:
Prin (a) … (0.0, 0.5) …
Las matrices son representadas por listas anidadas, con cada fila siendo un elemento de la lista, por ejemplo, insertar matriz “(a)”.
A= ■(1&2&3@4&5&6@7&8&9)
Módulos matemáticos 
•	Math
•	Numpy
El módulo math
La mayoría de funciones matemáticas están incluidas en el núcleo de python, pero también pueden importarse. Hay 3 formas de acceder a las funciones en un módulo.
La primera forma es importando todo el módulo utilizando la instrucción:
from math import*
(Va llamar los módulos de math)
El uso de este método no es recomendable porque carga módulos y comandos que tal vez no usemos.
Una mejor manera de importar es utilizando el comando:
from math import func1, func2, …
from math import.
Hay una 3r forma de importar los módulos la cual es:
“import math”.
Un módulo puede ser accesible bajo un alias, por ejemplo, el módulo math puede ser llamado mediante el alias “m”, de la siguiente forma.
import math as chicharo
chicharo. cos (0.15)
Los contenidos de un módulo pueden ser llamados e impresos con la función 
“dir (math)”        importa en lista comandos de math.SISTEMA DE ECUACIONES ALGEBRAICAS 

O bjetivo: Resolver ecuaciones simultaneas Ax=b
En este tema procedemos a la solución de N ecuaciones algebraicas lineales con N variables desconocidas. Es un tema muy importante ya que casi es imposible realizar análisis numéricos sin encontrar ecuaciones simultáneas. Además, los conjuntos de ecuaciones de problemas de ingeniería son de forma típica muy grandes y consumen demasiados recursos computacionales. Hay muchos algoritmos dedicados a la solución de grandes conjuntos de ecuaciones, cada uno diseña una forma particular una matriz de coeficientes.
El método que vamos a analizar es el de eliminación de gauss.
NOTACIÓN
Un sistema de ecuaciones algebraicas tiene la forma:
A11 X1 + A12 x2 + … + A 1 nxn = b1


“Módulo numpy”
El módulo numpy no está incluido en el módulo de python y debe descargarse e instalarse, además implementa funciones del algebra lineal y funciones de manejo de vectores.
Los arreglos pueden ser creados de diferentes formas. Uno de ellos es el uso de las funciones ARRAY para convertir una lista en un arreglo mediante el comando:
Array(lista,tipo)

La función arange devuelve una secuencia de números entre 2 límites y con un elemento configurado. 
Otra función disponible es la creación de matrices con componente CERO utilizando la función:
#zeros((dim1,dim2,) tipo)
El comando ONES crea un arreglo con definiciones del usuario :
#ones((dim1,dim2,)tipo)
                              condicionalesLa construcción if si condición: bloquear ejecuta un bloque de declaraciones (que deben tener sangría) si la condición devuelve Cierto. Si la condición devuelve False, se omite el bloqueo
def sign_of_a(a):
     if a < 0.0: 
         sign = ’negative’ 
     elif a > 0.0:
         sign = ’positive’ 
     else: 
           sign = ’zero’ 
       return sign 
a = 1.5
 print(’a is ’ + sign_of_a(a))
                                             Sistema  de ecuaciones algebraicas lineales Objetivo: Resolver ecuaciones simultaneas Ax=b
En este tema procedemos a la solución de N ecuaciones algebraicas lineales con N variables desconocidas. Es un tema muy importante ya que casi es imposible realizar análisis numéricos sin encontrar ecuaciones simultáneas. Además, los conjuntos de ecuaciones de problemas de ingeniería son de forma típica muy grandes y consumen demasiados recursos computacionales. Hay muchos algoritmos dedicados a la solución de grandes conjuntos de ecuaciones, cada uno diseña una forma particular una matriz de coeficientes.
El método qu
#Equipo Jese Manuel Acosta Avila y Gabriela Ramirez Cortez
#13/09/2019
#Ejercicio 1

from numpy import*

print(arange(1,101,2))
iniciando el ejercicio 1 en adelante se mostrarán  algunos ejemplos  que se vió en clase  de la materia "metodos numericos"
##Equipo Jese Manuel Acosta Avila y Gabriela Ramirez Cortez
#13/09/2019
#Ejercicio 2

from numpy import array

a=array([[1.44, -0.36, 5.52, 0.00], [-0.36, 10.33, -7.78, 0.00], [5.52, -7.78, 28.40, 9.00], [0.00, 0.00, 9.00, 61.00]])
print(a)

b=array([[0.04], [-2.15], [0], [0.88]])
print(b)


#Equipo Jese Manuel Acosta Avila y Gabriela Ramirez Cortez
#20/09/2019
#Ejercicio 3: Determinar que la matriz A es singular

import numpy as np
A = np.array([[2.1,-0.6,1.1],[3.2,4.7,-0.8],[3.1,-6.5,4.1]])
detA = np.linalg.det(A)
print('La determinante de A es: %.2f'%detA )

#Equipo Jese Manuel Acosta Avila y Gabriela Ramirez Cortez
#20/09/2019
#Ejercicio 4: Realizar un programaen el que el usuario introdusaca los 9 elementos de una matriz 3*3 y que el programa le debuelva al usuario si la matriz que inserto es singular o no.

import numpy as np
print('Introduce los 9 datos de tu matriz: ')
a11 = float(input('a11= '))
a12 = float(input('a12= '))
a13 = float(input('a13= '))
a21 = float(input('a21= '))
a22 = float(input('a22= '))
a23 = float(input('a23= '))
a31 = float(input('a31= '))
a32 = float(input('a32= '))
a33 = float(input('a33= '))

A = np.array([[a11,a12,a13],[a21,a22,a23],[a31,a32,a33]])
detA = np.linalg.det(A)
if np.round(detA,0) == 0.0:
    print('La matriz A es singular')
else: 
    print('la matriz A no es singular, es: %.2f' %detA )









                                             
                              
