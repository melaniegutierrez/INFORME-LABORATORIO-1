# LABORATORIO-1

### 1. OBJETIVO

Explicar y demostrar experimentalmente la Ley de Kirchhoff de Voltajes y la Ley de Kirchhoff de Corrientes mediante el cálculo teórico y simulaciones en la aplicación de Tinkercad de un circuito resistivo mixto con el fin de poner en práctica los conocimientos adquiridos en clase para el estudio de circuitos en serie y paralelo.

### Objetivos específicos

Definir las trayectorias de corriente tanto en serie o paralelo mediante la interpretación de sistemas esquemáticos de circuitos mixtos para analizar la utilidad de las leyes de Kirchhoff.

Comparar medidas de voltaje y corriente medidas con la aplicación de fórmulas, con las obtenidas en circuitos simulados para un mejor estudio de las trayectorias de corriente y consumo de voltaje.

Calcular porcentajes de error de las leyes de Kirchhoff mediante fórmulas de medidas teóricas y simuladas para comprobar la efectividad de dichas leyes en el calculo de voltaje y corriente de circuitos. 

### 2. MARCO TEORICO

![]()

### 3. EXPLICACIÓN DEL PROCEDIMIENTO

### 4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

**Tabla 1.1. Resultados obtenidos de voltaje y corriente, en cada elemento del circuito.**

| **VARIABLE** | **VALOR CALCULADO** | **VALOR MEDIDO** |
| :-------------: | :-------------: | :-------------: | 
| VR1 (V)  |        1.02 V          |      1.03 V           |
| IR1 (mA)  |       1.02 mA       |     1.03 mA            |
| VR2 (V)  |        2.12 V  |      2.12 V            |
| IR2 (mA)  |       0.54 mA          |     0.55 mA           |
| VR3 (V)  |        1.06 V     |     1.06 V            |
| IR3 (mA)  |       0.48 mA  |    0.48 mA           |
| VR4 (V)  |        1.06 V       |      1.06 V           |
| IR4 (mA)  |       0.48 mA        |    0.48 mA           |
| VR5 (V)  |        1.84 V       |       1.85 V          |
| IR5 (mA)  |       1.02 mA        |     1.03 V            |

**Tabla 1.2. Verificación de la LVK.**

|  **VOLTAJE**  | **Trayectoria 1**     | | **Trayectoria 2** | | **Trayectoria 3** | |
| :----------: | :----------: |:---------:| :-----------: |:-----------: |:--------:| :-----------: |
|  |**Calculado**| **Medido** |**Calculado**| **Medido** |**Calculado**| **Medido** |
| VT (V)  |   5 V   | 5 V   |  5 V  |  5 V   |  5 V    |  5 V    |
| VR1 (V) | -1.02 V | -1.03 V|    |     |-1.02 V  |-1.03 V      |
| VR2 (V) | -2.12 V| -2.12 V| -2.12 V| -2.12 V|      |      |
| VR3 (V) |   |       | -1.06 V |-1.06 V| -1.06 V | -1.06 V    |
| VR4 (V) |   |       | -1.06 V|-1.06 V| -1.06 V | -1.06 V   |
| VR5 (V) |-1.84 V| -1.85 V|     |     |  -1.84 V| -1.85 V |
|  **ΣV (V)** | 0.02  | 0      |0.76  |0.76 |0.02      |0      |

**Tabla 1.3. Verificación de la LCK.**

|  | **Nodo 1** | | **Nodo 2** | | **Nodo 3** | | **Nodo 4** | | **Nodo 5** | |
| :----------: | :----------: |:-------:| :----------: |:----------: |:-------:| :----------: | :----------: |:----------: |:-------:| :----------: |
|**CORRIENTE**|**Calculado**| **Medido** |**Calculado**|**Medido**|**Calculado**|**Medido**|**Calculado**|**Medido**|**Calculado**|**Medido**|
| IT (A)  | 1.02 mA| 1.03 mA|1.02 mA| 1.03 mA|1.02 mA| 1.03 mA|1.02 mA| 1.03 mA|1.02 mA| 1.03 mA|
| IR1 (A) |-1.02 mA| -1.03 mA|   |    |    |   |   |   |   |   |
| IR2 (A) |    |     |-0.54 mA|-0.55 mA|    |       |-0.54 mA|-0.55 mA|     |    |
| IR3 (A) |    |     |-0.48 mA|-0.48 mA|-0.48 mA|-0.48 mA|    |      |     |     |
| IR4 (A) |    |     |     |      |-0.48 mA|-0.48 mA| -0.48 mA|-0.48 mA|   |     |
| IR5 (A) |    |     |     |      |     |   |    |    |-1.02 mA| -1.03 mA|
|  ΣI (A) |0 mA| 0 mA|0 mA| 0 mA|0.09 mA|0.09 mA|0 mA| 0 mA|0 mA| 0 mA|

**Calculo de errores de las mediciones**



