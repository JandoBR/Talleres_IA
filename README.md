# Taller1_IA

## Integrantes
- Jose Ballestas
- Daniel Gomez
- Francesco Rosa

## Explicacion de la heurística:
Esta heurística evalúa un estado del tablero analizando qué tan cerca están las fichas de sus vecinos esperados según el estado objetivo.

Esta heurística considera la relación entre fichas adyacentes. Para cada ficha, identifica cuáles deberían ser sus vecinos en la solución y calcula qué tan alejados están actualmente esos vecinos.

El valor de la heurística aumenta cuando las fichas que deberían estar juntas se encuentran separadas, y disminuye cuando las fichas mantienen una distribución similar a la del estado objetivo.

En resumen:

* **Valor bajo:** las fichas conservan relaciones de vecindad parecidas a la solución.
* **Valor alto:** las fichas que deberían estar juntas están alejadas o desordenadas.

## Resultados De Ejecucion:
Número total de iteraciones realizadas: 415

Solución encontrada en 26 pasos:

--- ESTADO INICIAL ---
```
3 2 6
5 _ 4
1 8 7
```

Paso 1: Mover ficha 5 hacia Derecha
```
3 2 6
_ 5 4
1 8 7
```

Paso 2: Mover ficha 3 hacia Abajo
```
_ 2 6
3 5 4
1 8 7
```

Paso 3: Mover ficha 2 hacia Izquierda
```
2 _ 6
3 5 4
1 8 7
```

Paso 4: Mover ficha 6 hacia Izquierda
```
2 6 _
3 5 4
1 8 7
```

Paso 5: Mover ficha 4 hacia Arriba
```
2 6 4
3 5 _
1 8 7
```

Paso 6: Mover ficha 7 hacia Arriba
```
2 6 4
3 5 7
1 8 _
```

Paso 7: Mover ficha 8 hacia Derecha
```
2 6 4
3 5 7
1 _ 8
```

Paso 8: Mover ficha 5 hacia Abajo
```
2 6 4
3 _ 7
1 5 8
```

Paso 9: Mover ficha 6 hacia Abajo
```
2 _ 4
3 6 7
1 5 8
```

Paso 10: Mover ficha 4 hacia Izquierda
```
2 4 _
3 6 7
1 5 8
```

Paso 11: Mover ficha 7 hacia Arriba
```
2 4 7
3 6 _
1 5 8
```

Paso 12: Mover ficha 8 hacia Arriba
```
2 4 7
3 6 8
1 5 _
```

Paso 13: Mover ficha 5 hacia Derecha
```
2 4 7
3 6 8
1 _ 5
```

Paso 14: Mover ficha 1 hacia Derecha
```
2 4 7
3 6 8
_ 1 5
```

Paso 15: Mover ficha 3 hacia Abajo
```
2 4 7
_ 6 8
3 1 5
```

Paso 16: Mover ficha 6 hacia Izquierda
```
2 4 7
6 _ 8
3 1 5
```

Paso 17: Mover ficha 8 hacia Izquierda
```
2 4 7
6 8 _
3 1 5
```

Paso 18: Mover ficha 7 hacia Abajo
```
2 4 _
6 8 7
3 1 5
```

Paso 19: Mover ficha 4 hacia Derecha
```
2 _ 4
6 8 7
3 1 5
```

Paso 20: Mover ficha 8 hacia Arriba
```
2 8 4
6 _ 7
3 1 5
```

Paso 21: Mover ficha 6 hacia Derecha
```
2 8 4
_ 6 7
3 1 5
```

Paso 22: Mover ficha 2 hacia Abajo
```
_ 8 4
2 6 7
3 1 5
```

Paso 23: Mover ficha 8 hacia Izquierda
```
8 _ 4
2 6 7
3 1 5
```

Paso 24: Mover ficha 4 hacia Izquierda
```
8 4 _
2 6 7
3 1 5
```

Paso 25: Mover ficha 7 hacia Arriba
```
8 4 7
2 6 _
3 1 5
```

Paso 26: Mover ficha 5 hacia Arriba
```
8 4 7
2 6 5
3 1 _
```