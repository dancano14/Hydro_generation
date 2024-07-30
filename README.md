# Hydro_generation
Revisión Analítica a la 2024 73rd edition Statistical Review of World Energy - Publicación del instituto de energía que analiza datos sobre los mercados energéticos mundiales del año anterior. Para esta publicación trabajaremos lo correspondiente a Generación Hidroeléctrica en Teravatio-hora (TWh) para los años 1965 - 2023.

Statistical Review of World Energy - 2024 73rd edition Statistical Review of World Energy - Publication of the energy institute that analyzes data on global energy markets from the previous year. For this publication we will work on the Hydroelectric Generation in Terawatt-hour (TWh) for the years 1965 - 2023.


## Cargue de archivos

Luego de ajustar el archivo CSV residual del informe del instituto de energía, nos concentramos en el apartado de Generación Hidroeléctrica. Ajustamos algunos valores como:
  1. Integración de la Columna Continente que contendrá categorías para agrupar los registros por geografía.
  2. Eliminar registros que no contengan registros o que su generación Hidroeléctrica no supere los 2TWh registrados, entre ellos: Luxemburgo, Países Bajos, Singapur, Dinamarca, Estonia, entre otros.
