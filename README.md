# Adriana-Jamileth-Mendoza-Ortiz
<p align="center"><b><span style="font-family: Negrita; font-size: 200px;">"EJERCICIOS DEL TEMA #2"</span></b></p>

[Bisección #2](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/4528f5929dda57491257504bcff4ef674c95c96f/Bisecci%C3%B3n2)

[Bisección #3](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/b18deb2faa33452bc8a499617f38469146b504e2/Bisecci%C3%B3n3)

[Bisección #4](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/0a7a4227779b7f94ccc542b8af1d564bb6e264fb/Bisecci%C3%B3n4)

[Bisección #5](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/faeee8b343c17af2ce3539f609a66385ce7f3570/Bisecci%C3%B3n5)

[Ejercicio #2](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/a28d9f75a66e84e42a9f74034151857d9a32d5dc/Ejercicio2)

[Ejercicio #3](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/cab3e098500cbb2ca78298d6605dd4b7e5bf9666/Ejercicio3)

[Ejercicio #4](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/3aaf3c060e37bedea29478af3863acf698bdd69e/Ejercicio4)

[Newton #2](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/376debaa367c2e0f77dabc3e13fa202d4b349b05/Newton2)

[Newton #3](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/f2de5d688072f67427ca2ac09bbc9984b3e68213/Newton3)

[Newton #4](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/f08c866286e785a9674b38a1d5d4caeceb4929b9/Newton4)

[Newton #5](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/e85119e0246679ee3da633668ad14b8a09c46cae/Newton5)

[Regla Falsa #2](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/b66319f5f06141f8400d13f2b7bdc2fe7fa4bb6b/ReglaFalsa2)

[Regla Falsa #3](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/a15ed6fe2325253e7d32cb369a23b24617bbec5b/ReglaFalsa3)

[Regla Falsa #5](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/c9089cd3073689e0256b7abcf86df8bef17e6b1e/ReglaFalsa5)

[Secuencial #2](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/c5e0e5da74f28394cd177c0c0ef0cd6c927d7c1a/Secejr2)

[Secuencial #3](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/edb113f08f4b512c0325a0571b9af95dc0c0c395/Secejr3)

[Ejemplo secuencial #4](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/444402f2bf4d18cad23e21ec490e3d6f780b49c4/Secuencial%20%234)


<p align="center"><b><span style="font-family: Negrita; font-size: 200px;">"Apuntes tema #3"</span></b></p>

<p align="left"><b><span style="font-family: Negrita; font-size: 200px;">"Equipo: Wenceslao Benitez Rosquero, Jair Cano Rojas y Adriana Jamileth Mendoza Ortiz"</span></b></p>

**ELIMINACIÓN GAUSSIANA**
---

El método de eliminación gaussiana consiste en:
1) Llevar un sistema de ecuaciones a la forma matricial.
2) Convertir una matriz cuadrada en una matriz triangular superior, que es equivalente a la matriz original.
3) Resolver el sistema, sustituyendo las variables en cada ecuación resultante.

En otras palabras, el sistema transforma un sistema como:

[![Captura-de-pantalla-2024-03-13-223457.png](https://i.postimg.cc/yNTLbCMX/Captura-de-pantalla-2024-03-13-223457.png)](https://postimg.cc/bGs0ZWNs)

En una matriz como:

[![Captura-de-pantalla-2024-03-13-223600.png](https://i.postimg.cc/pdVSxdY1/Captura-de-pantalla-2024-03-13-223600.png)](https://postimg.cc/TKS0Jfsr)

Y, usando operaciones de suma, resta y producto, convertir la matriz en una triangular del tipo:

[![Captura-de-pantalla-2024-03-13-223713.png](https://i.postimg.cc/qRwMqq9h/Captura-de-pantalla-2024-03-13-223713.png)](https://postimg.cc/8JFVnpkN)

Para obtener:

[![Captura-de-pantalla-2024-03-13-223755.png](https://i.postimg.cc/mrwGNqVK/Captura-de-pantalla-2024-03-13-223755.png)](https://postimg.cc/WDhKs5B7)



[Implementación de la Eliminación Gaussiana en Java](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/817479e8f9e1d3c37112a8a8af7ddf19fa1cd0ff/Imp_Elim_Gaussiana)

Algoritmo:
1) Clonar la matriz original para no modificarla directamente.
2) Inicializar índices i y j a 0.
3) Entrar en un bucle mientras i sea menor que la altura de la matriz y j sea menor que el ancho de la matriz.
4) En cada iteración, se busca el pivote en la columna actual (j) buscando el elemento con el mayor valor absoluto en esa columna.
5) Si el pivote encontrado no es cero, se intercambia la fila actual (i) con la fila del pivote.
6) Se normaliza la fila actual dividiendo todos los elementos de la fila por el valor del pivote.
7) Se eliminan los elementos por debajo del pivote, es decir, se hace cero los elementos debajo del pivote en la columna actual, usando la fila actual y operaciones de fila elementales.
8) Se incrementan los índices i y j.
9) El bucle continúa hasta que i sea mayor o igual que la altura de la matriz o j sea mayor o igual que el ancho de la matriz.
10) Se devuelve la matriz modificada que representa la matriz inversa.

[Ejemplo 1](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/d1559bcc35962bc76f0a4ecfd72828550e443085/Eliminaci%C3%B3n%20Gaussiana%201)

[Ejemplo 2](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/9b8363e80ef38c004e1c7db13103d91cc4e86a90/ElimGaus2)

[Ejemplo 3](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/5018cc6db5b7fb7fce9a765a9d6dabd9e1250a4e/ElimGauss3)

[Ejemplo 4](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/20ba9cb5e5739511ff419be4dba1750cbc4d3780/ElimGaus4)

[Ejemplo 5](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/224999a645bb1735d51cd6ea531ac94870a28830/ElimGauss5)


**GAUSS-JORDAN**
---

Consiste en transformar un sistema de ecuaciones en otro equivalente de forma que este sea escalonado.
Para facilitar el cálculo vamos a transformar el sistema en una matriz, en la que pondremos los coeficientes de las variables y los términos independientes (separados por una recta).

[![image.png](https://i.postimg.cc/dQGF64ns/image.png)](https://postimg.cc/nMVNcK6g)

[Implementación de Gauss-Jordan en Java](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/4cf04d8aeeaaedb0b99996b9851d0003ca7c5c4c/ImJordan)


Algoritmo:
1) Se define una matriz a[][] que representa el sistema de ecuaciones lineales en forma aumentada, donde las primeras n columnas representan los coeficientes de las variables y la última columna representa los términos constantes.
2) Se define una función PerformOperation() que reduce la matriz a la forma escalonada reducida por filas. Esta función recorre cada fila i de la matriz y realiza las siguientes operaciones:
   1) Si el elemento diagonal a[i][i] es cero, se intercambia esa fila con una fila debajo de ella que tenga un elemento no nulo en la misma columna. Esto se hace para evitar divisiones
      por cero y para hacer ceros por debajo de la diagonal principal.
   2) Luego, se realiza la eliminación gaussiana para hacer ceros en las columnas por encima y por debajo de la diagonal principal.
3) Se define una función CheckConsistency() que determina si hay soluciones únicas, soluciones infinitas o ninguna solución, según la matriz resultante después de la eliminación gaussiana. Esta función calcula la suma de los coeficientes de cada ecuación y compara esa suma con el término constante. Si todas las sumas son iguales a los términos constantes, significa que hay soluciones infinitas. Si al menos una suma no es igual a su término constante correspondiente, significa que no hay solución. En caso contrario, hay soluciones únicas.
4) Se realiza la impresión de la matriz resultante y se imprime el resultado del sistema de ecuaciones, ya sea que existan soluciones únicas, soluciones infinitas o ninguna solución.



[Ejemplo 1](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/efa0f6306229e46c0c5382e798b987f3bd03ef9d/Jordan1)

[Ejemplo 2](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/1aafca1859e2d36dd1473641faf4c8292761b801/Jordan2)

[Ejemplo 3](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/22f5cecc47634c2d8ac2ade23cfa8988494fb9f3/Jordan3)

[Ejemplo 4](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/985f01b147c8edb0c57fc6966cd87d35bbc157d7/Jordan4)

[Ejemplo 5](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/3f510db0abe26754ee6c63d640b1ab0bdaf19465/Jordan5)


**GAUSS-SEIDEL**
---

consiste en hacer iteraciones, a partir de un vector inicial, para encontrar los valores de las incógnitas hasta llegar a una tolerancia deseada, la diferencia radica en que cada vez que se desee encontrar un nuevo valor de una xi, además de usar los valores anteriores de las x, también utiliza valores actuales de las x encontradas antes (desde x0 hasta xi-1). La ecuación es la siguiente:

[![image.png](https://i.postimg.cc/W39mrMK0/image.png)](https://postimg.cc/sQhZCZ32)


[Implementación de Gauss-Seidel en Java](https://github.com/adrianaMendoza1/Adriana-Jamileth-Mendoza-Ortiz/blob/2ac4cf42f06b5b1c98435f24447c0fdf93c1411f/ImpSeidel)



Algoritmo:

1) Se define una clase GFG que contiene métodos para realizar la transformación a una matriz diagonalmente dominante, imprimir la matriz y resolver el sistema de ecuaciones.
2) Se define una constante MAX_ITERATIONS que establece el número máximo de iteraciones permitidas para evitar un bucle infinito.
3) Se define un constructor GFG que toma una matriz de coeficientes como argumento.
4) El método print() se utiliza para imprimir la matriz.
5) El método transformToDominant() intenta transformar la matriz en una matriz diagonalmente dominante. Se utiliza recursión para encontrar la permutación de filas que hará que la matriz sea diagonalmente dominante.
6) El método makeDominant() verifica si la matriz es diagonalmente dominante o no. Si no lo es, intenta transformarla utilizando transformToDominant().
7) El método solve() se encarga de resolver el sistema de ecuaciones utilizando el método de Gauss-Seidel. Utiliza un bucle while para iterar hasta que se cumpla el criterio de convergencia o hasta que se alcance el número máximo de iteraciones. En cada iteración, se calculan las aproximaciones de las variables X[] utilizando la fórmula de Gauss-Seidel. Se imprimen las aproximaciones en cada iteración.
8) En el método main(), se crea una matriz de ejemplo y se instancia un objeto de la clase GFG. Se verifica si la matriz es diagonalmente dominante y, si no lo es, se imprime un mensaje de advertencia. Luego, se imprime la matriz y se resuelve el sistema de ecuaciones utilizando el método solve().

[Ejemplo 1]()

[Ejemplo 2]()

[Ejemplo 3]()

[Ejemplo 4]()

[Ejemplo 5]()
