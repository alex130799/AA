# SENSIBILIDAD DE LA CURVA TONELAJE - LEY DE CORTE A DIFERENTES TAMAÑOS DE BLOQUES DE EXPLOTACIÓN

El tamaño de bloques unitarios de reservas mineras en minería cielo abierto es una decisión a tomar para
obtener el mayor beneficio económico. en este trabajo se hará la sensibilidad del tamaño de bloques de un
yacimiento tipo pórfido de cobre, aplicable también con otros parámetros técnicos económicos a
diseminados de oro de alta sulfuración de baja ley. Teniendo como ejemplo la mina Chuquicamata para
tener la referencia de altura de un bloque, largo y ancho obteniendo curvas Tonelaje, Ley Media,
Contenido Metálico y Dólares USA ($) en función de la Ley de Corte, para hallar el pit final.

Para realizar la sensibilidad, se simulo leyes con el Teorema de Limite Central de Lyapunov.

# ÍNDICE

. INTRODUCCIÓN
. METODOLOGÍA
. ALGORITMO
. VISUALIZACIÓN DE INFORMACIÓN
. CONCLUSIÓN
. AGRADECIMIENTOS

# INTRODUCCIÓN

En la primera parte se simularon leyes con una media aritmética 0.7 y desviación estándar 0.6, densidades con una media aritmética 3.5 y desviación estándar 0.5 y coordenadas X, Y, Z con la implementación de un código Python. Luego, el yacimiento creado se clasifica en bloques de 5*5*5, 10*10*10, 15*15*15 y 20*20*20 de acuerdo a medidas reales de una mina, promediando las leyes que se encuentran dentro de un bloque encontrado. [1]
En la segunda parte los datos obtenidos del código anterior se procesan para clasificarlos a partir de una ley de corte, hallando el tonelaje, ley media, contenido metálico y dólares USA con sus respectivos gráficos para un análisis de sensibilidad

![image](https://user-images.githubusercontent.com/67855447/120094652-4440ae00-c0e7-11eb-8625-bb69e955dd9c.png)

# METODOLOGÍA

Para la investigación se acudió al teorema de limite central, la cual nos indica, si n tiende al infinito, las leyes cumplirán una distribución Normal.

![image](https://user-images.githubusercontent.com/67855447/120094665-5f132280-c0e7-11eb-9b8e-be75b9f6631c.png)

# ALGORITMO

La simulación se desarrolló en el lenguaje C++, y el equipo de investigación lo caracterizó en Python y Visual Basic

![image](https://user-images.githubusercontent.com/67855447/120094676-718d5c00-c0e7-11eb-9dc2-bc79fafb84da.png)

# VISUALIZACIÓN DE INFORMACIÓN

![image](https://user-images.githubusercontent.com/67855447/120094831-48210000-c0e8-11eb-899f-10560b449c59.png)
![image](https://user-images.githubusercontent.com/67855447/120094850-64bd3800-c0e8-11eb-8969-d3ef3c3b01bc.png)
![image](https://user-images.githubusercontent.com/67855447/120094844-5e2ec080-c0e8-11eb-9fdb-810014e24554.png)
![image](https://user-images.githubusercontent.com/67855447/120094873-7d2d5280-c0e8-11eb-89c3-c71b022bc2a4.png)


# CONCLUSIONES

●	El yacimiento de mayor tamaño de bloque tiene más sensibilidad comparado con los de menores tamaño. 
●	Se ha permitido estimar las reservas de un yacimiento de pórfido para luego realizar labores complementarias de estimación de reservas minables.

# AGRADECIMIENTOS

Este trabajo no hubiera podido concretar sin el apoyo del Dr. Alfredo Marín Suarez, con los conocimientos obtenidos a lo largo de sus carreras, nos guiaron de la mejor forma para el desarrollo de este proyecto.


