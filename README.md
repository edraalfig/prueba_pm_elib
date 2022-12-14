# Libreria PM_Elib
## _Mineria de Procesos_

Esta es una primera versión de una libreria que sirve para realizar analisis de Mineria de Procesos.

## Características
### Recibe
Archivo ".CSV", que contenga cinco (5) columnas:
- Id de casos
- Nombre de Actividad
- Recurso utilizado (Cabe resaltar que al ser esta una primera versión, por el momento solo se acepta un recurso por actividad)
- Hora de Inicio de Actividad 
- Hora de fin de la Actividad

Cuando se va a ejecutar, se necesita: 

- Cuanto cuesta el proceso sin tiempos muertos.
- Cantidad de días (int) y la cantidad de horas (str) que dura el proceso sin tiempos muertos, para crear un timeStamp.


#### Ejemplo
Se crean las variables de la siguiente manera
```
dias = 4
horas "00:30:14"
```
Para que la libreria lo pueda interpretar como TimeDelta
```
4 days 00:30:14
```

### Retorna un diccionario de python con:
-- Generalidades (Cantidad de casos, filas y columnas)
-- Diccionario con las relaciones entre actividades y grupos de recursos
-- Mejor Variante
-- Costo de Mejor Variante
-- Tiempo de Mejor Variante
-- Resumen de cuellos de botella
-- Sugerencias que podrían ayudar a optimizar el proceso para ejecuciones futuras


Obtendriamos un diccionario de la siguiente manera

![](https://github.com/edraalfig/prueba/blob/main/Captura.PNG?raw=true)

