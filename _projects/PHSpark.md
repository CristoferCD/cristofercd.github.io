---
layout: project
name: PHSpark
banner_img: /assets/img/project/phspark-banner.png
github_link: https://github.com/CristoferCD/TFG
tags:
    - Python
    - Spark
fe_inicio: Marzo 2018
fe_fin: Septiembre 2018
---

Como Trabajo de Fin de Grado se desarrolló el módulo PHSpark, un plugin de resolución de problemas estocásticos para Pyomo. Este nuevo módulo permite la ejecución paralela del algoritmo en un entorno distribuido mediante el uso del framework Apache Spark.

<br/>

Pyomo es un paquete de software basado en Python destinado a la formulación y solución de modelos de optimización. En este proyecto se amplia el módulo PySP, el paquete de Pyomo dedicado a la solución de problemas estocásticos. 

La programación estocástica resuelve problemas de optimización donde existe un cierto grado de incertidumbre. Esta variabilidad se modela como un árbol de posibles escenarios que, para llegar a una solución, deben converger a un valor único.

<br/>

El módulo PHSpark implementa el algoritmo "Progressive Hedging" para la resolución de problemas estocásticos. Para la paralelización de este algoritmo se usa el framework Apache Spark. Spark permite definir paquetes de trabajo que posteriormente repartirá en los múltiples nodos de ejecución que tenga disponibles.

<br/>

En el repositorio de GitHub adjunto se encuentra tanto la documentación del TFG como el fork de Pyomo con el módulo implementado. Puede descargar el pdf completo de la memoria [aquí](https://raw.githubusercontent.com/CristoferCD/TFG/master/Documentaci%C3%B3n/Memoria/traballo.pdf)