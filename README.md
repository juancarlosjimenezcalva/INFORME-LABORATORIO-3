# INFORME LABORATORIO 3
Informe del laboratorio 3

## OBJETIVOS

### OBJETIVO GENERAL

Realizar el análisis de nodos aplicando la Ley de corrientes de Kirchhoff y Ley de Ohm por medio de la elaboración de un circuito eléctrico para obtener los valores de los voltajes de nodo.

### OBJETIVOS ESPECIFICOS

•	Elaborar un circuito eléctrico mixto en Tinkercad y físico.
•	Realizar el análisis de nodos del circuito elaborado para encontrar los valores de los voltajes de nodo.

## MARCO TEÓRICO

### Análisis de nodos

El método de análisis de nodos es una herramienta que permite la aplicación de la Ley de corriente de Kirchhoff para la resolución de problemas complejos con un número de variables y ecuaciones.

En este método el objetivo es conocer los voltajes para cada nodo del circuito, por tanto, un nodo es la unión de dos o más elementos que se conectan en un circuito eléctrico, como se indica en la siguiente imagen.

![image](https://user-images.githubusercontent.com/105565683/172525181-4ecd93a6-ac2d-46d2-a683-1d40886c96e2.png)

En un circuito eléctrico siempre se presentará un nodo de referencia, en donde el voltaje de los demás nodos se mide con relación al nodo de referencia.

Tomando en cuenta los nodos, para su análisis se aplica la Ley de corriente de Kirchhoff, que consiste en la suma de todas las corrientes que fluyen hacia un nodo es igual a la suma de las corrientes que salen del nodo, su fórmula es:

![image](https://user-images.githubusercontent.com/105565683/172525223-adb18cbe-15c3-448f-8d57-c2018377345a.png)

El análisis de nodos guarda una relación con la Ley de Ohm para su análisis y construcción de sistema de ecuaciones, por tanto, La ley de Ohm consiste en que la corriente es directamente proporcional al voltaje e inversamente proporcional a la resistencia, manteniendo una relación entre voltaje, corriente y resistencia. Permitiendo el cálculo del voltaje por medio de esta ley, sus fórmulas son:

![image](https://user-images.githubusercontent.com/105565683/172525291-aab53002-352a-4503-87b7-c5a566243208.png)

En donde V es voltaje, R es resistencia e I es corriente.

Por tanto, para el análisis de nodos se emplea la Ley de Kirchhoff y Ley de Ohm permitiendo encontrar los voltajes de los nodos presentes en un circuito eléctrico.

Es importante que haya una ecuación por cada nodo, de esta manera el sistema de ecuaciones es consistente, así el número de incógnitas es igual al número de ecuaciones.

Los pasos para el análisis de nodos son:

#### Paso 1

Seleccionar el nodo de referencia y asignar las tensiones a los nodos restantes, se asignan respecto al nodo de referencia.

#### Paso 2

Dibuja la trayectoria de corriente en cada rama.

#### Paso 3

Aplicar la Ley de Corrientes de Kirchhoff a cada uno de los nodos y usar la Ley de Ohm para expresar las corrientes en términos de tensión del nodo.

#### Paso 4

Resolver el sistema de ecuaciones de los nodos para obtener los voltajes de los nodos desconocidos

## EXPLICACIÓN DEL PROCEDIMIENTO

### ELABORACIÓN DEL CIRCUITO

#### MATERIALES

![image](https://user-images.githubusercontent.com/105565683/172512745-b3e33877-64d6-449c-ab71-92d1b4b65fdb.png)

![image](https://user-images.githubusercontent.com/105565683/172512906-318fcfcd-b2fd-40d6-931f-2bf2b562c6eb.png)

#### PROCESO

1.	Ubicamos las resistencias como se muestra en el esquema del circuito.

![image](https://user-images.githubusercontent.com/105565683/172513040-d34e9826-d9ed-47f9-a8cd-d0ef39e74ba9.png)

2.	Conectar las resistencias por medio de los cables de acuerdo con el esquema, que cumpla con el circuito mixto.

![image](https://user-images.githubusercontent.com/105565683/172513138-b5935d4f-bf93-4a48-8385-bc4f658082f0.png)

3.	Conectamos las fuentes de voltaje C.D. (en caso de simulador), de acuerdo al esquema, en los polos positivo y negativo de las resistencias.

![image](https://user-images.githubusercontent.com/105565683/172513234-9c016f56-d718-47d3-96e7-4dbf6301b3e8.png)

#### CIRCUITO FISICO

Siguiendo el mismo proceso, armamos el circuito físico:

![1](https://user-images.githubusercontent.com/105565683/172524767-10795685-023a-43ee-9372-2490747021c8.jpg)

![2](https://user-images.githubusercontent.com/105565683/172524790-851e899d-2d5b-4249-bd25-a98a46e60832.jpg)

### CALCULO DE LOS VOLTAJES Y CORRIENTES

### ANÁLISIS DE NODOS

![image](https://user-images.githubusercontent.com/105565683/172513356-681528ab-249a-488b-ac16-049d0588418c.png)

Basándonos en el esquema de circuitos, podemos ver que existen dos nodos principales, dos nodos fantasmas y un nodo de referencia, quedando de la siguiente forma:

![image](https://user-images.githubusercontent.com/105565683/172513383-34e59255-f1e6-4eaa-b2ec-4debb7f96881.png)

![image](https://user-images.githubusercontent.com/105565683/172513422-dcba1b84-e8cc-475b-aab7-d8a8138e0f8b.png)

![image](https://user-images.githubusercontent.com/105565683/172513479-98001d75-1657-4e16-bd88-8467912bb286.png)

### SISTEMA DE ECUACIONES:

![image](https://user-images.githubusercontent.com/105565683/172513558-40d95c98-2b98-4ec0-83e4-466787c5377d.png)

Utilizando una calculadora online, resuelvo el sistema:

![image](https://user-images.githubusercontent.com/105565683/172513693-e9c0fc93-7aea-498c-abc3-63487b2b57e6.png)

![image](https://user-images.githubusercontent.com/105565683/172513736-0edaec50-4266-495d-8a12-e7790c7cb76f.png)

Obtengo los valores de los voltajes:

![image](https://user-images.githubusercontent.com/105565683/172513802-74c36312-7ea9-49a5-9ca9-7330a72373fe.png)

Una vez obtenidos los voltajes, obtengo las corrientes:

![image](https://user-images.githubusercontent.com/105565683/172513834-e1e56b73-3e29-4682-98c4-a4f4513792ea.png)

## RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

### MEDICIONES DE VOLTAJE Y CORRIENTE

1. Medir el voltaje en cada elemento del circuito con el multímetro.

![image](https://user-images.githubusercontent.com/105565683/172513966-0a1b4ca3-68d5-49db-8191-45de0c7cfc2a.png)

2. Medir la corriente en cada elemento del circuito con el multímetro.

![image](https://user-images.githubusercontent.com/105565683/172514048-4be280ea-3cb6-4903-beab-cae8e7239475.png)

3. Comparar los resultados obtenidos de voltaje y corriente, en cada elemento del circuito.

Para el circuito físico se utilizaron baterías y pilas para las fuentes de voltaje, siendo de 6 V y 9 V, por ende, existirá una ligera diferencia entre los resultados, también se tomarán en cuenta los resultados obtenidos en ambos circuitos del grupo.

![image](https://user-images.githubusercontent.com/105565683/172524856-fece0fdf-7e2e-4f8f-a5e8-1ee75b6ba127.png)

### RESULTADOS



## VIDEO



## CONCLUSIONES

•	Se utilizó un análisis y comprensión adecuado del esquema proporcionado para la elaboración del circuito eléctrico de tal forma que cumpla lo solicitado con los materiales correctos y su correcta polarización.

•	Se determinó que gracias al análisis de nodos se puede obtener los valores de los voltajes de nodo en un circuito eléctrico por medio de un sistema de ecuaciones.

## BIBLIOGRAFÍA

- McAllister, W. (2022). Khan Academy. Obtenido de https://es.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/ee-kirchhoffs-laws
- MiElectrónicaFácil.com. (2022). MiElectrónicaFácil.com. Obtenido de https://mielectronicafacil.com/analisis-de-circuitos/teorema-de-nodos/
- Salazar, A. (2009). Fundamentos de circuitos. Bogotá: Ediciones Uniandes. Obtenido de http://wwwprof.uniandes.edu.co/~ant-sala/cursos/FDC/Contenidos/03_Analisis_por_Nodos_y_Mallas.pdf
