# Comentarios

En esta parte del Repositorio, se encuentran las simulaciones para la fuente de corriente propuestas para polarizar el BFP760 en $1 [V]$ - $40 [mA]$. Se propusieron 2 ideas para realizar este circuito para las cuales se añadieron las simulaciones en LTSpice de las mismas en 2 carpetas separadas.

Se presentan a continuación los resultados de cada forma de polarizar el transistor:
1. Polarización con OPAMP: Se obtuvo una: $V_{CE} = 1.00008 \ [V]$ e $I_{C} = 39.9992 \ [mA]$.

![OPAMP](https://github.com/ErnestMonja/Electronica_Analogica_III/blob/main/Trabajo%20Pr%C3%A1ctico%20N%C2%B02%20-%20Amplificador%20de%20Microondas/Archivos%20de%20la%20Simulaci%C3%B3n/Polarizaci%C3%B3n%20del%20BFP760/Resultados%20con%20LT1006.jpeg)
   
3. Polarización con LM317: Se obtuvo una: $V_{CE} = 0.935 \ [V]$ e $I_{C} = 39.19 \ [mA]$. 

![LM317](https://github.com/ErnestMonja/Electronica_Analogica_III/blob/main/Trabajo%20Pr%C3%A1ctico%20N%C2%B02%20-%20Amplificador%20de%20Microondas/Archivos%20de%20la%20Simulaci%C3%B3n/Polarizaci%C3%B3n%20del%20BFP760/Resultados%20con%20LM317.jpeg)


## Fuentes
* [Datasheet del BFP760](https://www.alldatasheet.com/datasheet-pdf/view/749038/INFINEON/BFP760.html)
* [Modelo en LTSPice del BFP760](https://www.infineon.com/part/BFP760)
* [Datasheet del LM317](https://www.alldatasheet.com/datasheet-pdf/view/11662/ONSEMI/LM317.html)
* [Modelo en LTSpice del LM317](https://github.com/kafana/ltspice-misc/tree/master/models)
