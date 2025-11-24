# Estructura del Dataset

Para que el sistema de predicción funcione correctamente, el archivo que subas debe ser un **CSV** con las siguientes columnas. El sistema es flexible y acepta nombres en inglés o español.

## Columnas Requeridas

| Columna (Opción 1) | Columna (Opción 2) | Descripción |
|--------------------|--------------------|-------------|
| **HomeTeam**       | **Local**          | Nombre del equipo que juega en casa |
| **AwayTeam**       | **Visitante**      | Nombre del equipo visitante |
| **FTHG**           | **GolesLocal**     | Goles finales del equipo local (Full Time Home Goals) |
| **FTAG**           | **GolesVisita**    | Goles finales del equipo visitante (Full Time Away Goals) |

## Ejemplo de contenido .csv

\`\`\`csv
HomeTeam,AwayTeam,FTHG,FTAG
Alianza Lima,Universitario,1,2
Sporting Cristal,Melgar,3,0
Cusco FC,Cienciano,1,1
\`\`\`

## Notas
- El orden de las columnas no importa.
- El sistema calculará automáticamente quién ganó (Local, Visitante o Empate) basándose en los goles.
