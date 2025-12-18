# Taller09

* En la asignatura ***Fundamentos computacionales***, resolvió *(análisis, diseño de algoritmos, flujograma, prueba de escritorio, etc.)*, algunos problemas con estructuras de control de datos uni y bi dimensionales. El objetivo a continuación es codificar similares algoritmos, pero en el lenguaje de programación de alto nivel **JAVA**. 
* Programar/codificar en el lenguaje de alto nivel Java *(en el IDE NetBeans)*, sus soluciones a cada uno de los problemas listados a continuación dadas las siguientes instrucciones: 
    1. Clone este repositorio en su **PC** local `git clone URL_del_repo` 
    2. En su ***IDE*** cree un nuevo proyecto de tipo ***Java Application*** con el siguiente nombre: ***Proyect-APEB2-Taller09*** eligiendo como localización del proyecto, el repositorio *(carpeta)* clonada localmente en el *paso anterior*.
    3. Para cada problema, genere una clase/programa java independiente pero dentro del único proyecto (*Java App* creado en el *paso anterior*). No olvide nombrar cada clase con el número del problema y un nombre representativo de la solución. Ejemplo: ***Ejercicio01_ProcesarMatrices***
    4. Finalizado el taller *(o cada ejercicio)*, sincronice los cambios de su **PC** local, a este repositorio remoto de **GitHub**, con los comandos: `git add .` `git commit -m "Mensaje de la versión"` `git push`
* Verifique sus soluciones con las técnicas de compilación, ejecución y depurado de programas.
* Documente las soluciones con los bloques: (1.-) ***Documentación del problema***, y (2.-) ***Evidencia del funcionamiento y resultados***. Para ello, al inicio y final como parte de la codificación (en comentarios /** ), copiar y pegar el enunciado del problema, y al final, los resultados obtenidos de consola **RUN**. Ejemplo: 

```java
/**
 * Ejercicio 01: "Texto del enunciado del ejercicio/problema...."
 * @author NombreAutor
 * @version 1.0
 */

public class Ejercicio01_ProcesarMatrices {
    //AQUÍ AGREGUE TODO SU CÓDIGO...
}

/***
 * EVIDENCIA DEL RUN:
 * Pegue aquí la evidencia de la ejecución del .java
 */
 ```
## Construcción de programas usando arreglos bidimensionales

### Ejercicio 1
---

Dada una matriz cuadrada _*(m X m)*_ de valores enteros aleatorios, desarrollar su procesamiento para presentar los elementos: 

- De la diagonal principal.
- De la diagonal segundaria.
- Ubicados bajo la diagonal principal.
- Ubicados sobre la diagonal principal.
- Ubicados bajo la diagonal secundaria.
- Ubicados sobre la diagonal secundaria.

---
### Ejercicio02
---

Dadas dos matrices _(cuadradas y/o rectangulares)_ de valores enteros aleatorios, desarrollar su procesamiento para calcular y presentar:

- La suma de las dos matrices _(considerar las restricciones matemáticas para ello)_. 
- La multiplicación de las dos matrices _(considerar las reglas matemáticas para ello)_. 

---
### Ejercicio 3
---

El primer ciclo _paralelo C_, cuenta con **28** estudiantes, de los cuáles al finalizar el periodo, la Dirección de la carrera de Computación a solicitado las siguientes estadísticas de la materia **INTRODUCCIÓN A LA PROGRAMACIÓN** en función a los promedios por estudiante, dichos promedios se deben calcular _(ponderar, ya que el docente ingresa todo sobre 10pts.)_ de 3 calificaciones _(**ACD** que representa el **35%** de la nota, **APE** del **35%** y la nota del **AA** con un peso del **30%**)_. En resumen, los requerimientos son los siguientes: 

- Registre los nombres de cada estudiante de dicho paralelo.
- Genere aleatoriamente las notas **ACD**, **APE**, **AA**, para cada uno de los 28 estudiantes de 0-10 pts. 
- Calcule el promedio de cada uno de los estudiantes del paralelo dada la siguiente ponderación: **ACD**->35%, **APE**->35%, y el **AA**->30%.
- Obtenga el promedio del curso, del _paralelo C_. 
- Liste los nombres de los estudiantes y su nota, que hayan obtenido un promedio por encima del promedio del curso. 
- Liste los nombres de los estudiantes y su nota, que hayan obtenido un promedio por debajo del promedio del curso. 
- Muestre el estudiante con su calificación, si es el del mayor promedio _(el más alto de la clase)_. 
- Muestre el estudiante con su calificación, si es el del menor promedio _(el más bajo de la clase)_. 

---
### Ejercicio 4
---

Una empresa registra el consumo eléctrico (kWh) de N hogares durante 12 meses. Construya un programa que auto-genere una la matriz de consumo, calcule el consumo total anual de cada hogar, determine el mes con mayor consumo total e Indique cuántos hogares superan un consumo anual definido como límite.

---
### Ejercicio 5
---

Crea un programa que gestione el inventario de una tienda, así como la emisión de facturas. Utiliza una matriz bidimensional para almacenar los productos disponibles en la tienda, con información como nombre, precio y cantidad. El programa debe permitir facturar un producto dado su código, y unidades deseadas. Adicional se debe agregar a la factura al _15% del IVA_, y si la compra superar los $100, se debe aplicar un descuento. 

_**Nota**_: Considere la alternativa de inexistencias en Stop, para el caso, muestre la alerta respectiva. 

---
### Ejercicio 6
---

Crea un juego de tres en raya utilizando una matriz bidimensional de _**3x3**_. Permita a dos jugadores marcar sus movimientos alternativamente. El juego debe verificar si alguno de los jugadores ha ganado o si hay un empate.

---
### Ejercicio 7
---

Una institución aplica una encuesta de satisfacción a N personas sobre M servicios, con valores del 1 al 5. Para ello requiere un programa que auto-genere la matriz de respuestas, que además calcule el promedio de satisfacción de cada servicio, identifique el servicio con menor promedio y determine cuántas personas calificaron todos los servicios con 4 o más.

---
### Ejercicio 8
---

Un cine registra la ocupación de asientos en una sala:

- Filas → filas del cine
- Columnas → asientos por fila
(1 = ocupado, 0 = libre)

Se requiere un programa para leer la matriz de ocupación, y que también muestre el mapa de asientos. Además debe contar cuántos asientos están ocupados. Y finalmente, debe indicar cuántos asisentos libres existen en cada fila.

---
### Ejercicio 9
---

Una estación meteorológica registra temperaturas durante 7 días, en 3 horarios (mañana, tarde y noche). Diseñar un programa que lea la matriz de temperaturas y que además calcule el promedio de temperatura de cada día. El programa debe encontrar la temperatura más alta registrada e indicar cuántas temperaturas superan los 30 °C.

---
### Ejercicio 10
---

Desarrolle un programa en Java que simule la organización de actividades navideñas de un curso universitario, usando una matriz bidimensional para registrar por cada estudiante su participación y aportes en varias actividades (por ejemplo: cena, intercambio de regalos y donación), donde el programa permita ingresar o generar los valores, valide que estén en rangos correctos, calcule totales y promedios por estudiante y por actividad, determine quiénes cumplen con un mínimo de participación/aporte y quiénes no.

