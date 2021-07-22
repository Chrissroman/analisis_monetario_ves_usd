# Análisis Monetario
En el presente Notebook, se pretende implementar diversos modelos que permitan modelar el comportamiento de la moneda venezolana en en términos de devaluación  monetaria. Si bien algunos autores fijan una clara relación entre la oferta y demanda monetaria para explicar la inflación y su respectiva devaluación, puede ser conveniente ingresar distintas variables que puedan ser aceptadas o descartadas mediante hipótesis.

Los datos del tipo de cambio **VES - USD** son suministrados por el **BCV (Banco Central de Venezuela)** y el Monitor del tipo de cambio paralelo promedio, que es típicamente utilizado en la sociedad Venezolana. Dichos datos  se encuentran en la página de Instagram *[@enparalelovzla](https://www.instagram.com/enparalelovzla/)* comprendidos desde el **2018 - 2021 (julio)**.

Los datos de inflación son proporcionados por la **Asamblea Nacional**, órgano legislativo venezolano, desde el año **2017 - 2021 (mayo)**. 

## Fases Comprendidas

Las fases comprendidas para el análisis parten desde la carga de datos, cálculo de nuevos campos, identificación de tendencias mediante hipótesis y finalmente la propuesta de modelos.

1. **Carga de librerías base**
2. **Carga de CSV's**
3. **Nuevas Variables ** *Deltas de crecimiento*
4. **Análisis Gráfico**
   1. Análisis VES/USD BCV
   2. Análisis VES/USD Monitor
   3. Tipo de cambio BCV vs Monitor
   4. Correlación Devaluación vs Inflación
      1. Carga de datos de Inflación
      2. Análisis grafico de la Inflación
      3. Correlación
5. **Implementación de Modelos**
   1. Predicción por Medias
   2. Recursive Forecasting

## Notas

Conforme hayan nuevas revisiones, se irá ajustando modelos, agregando nuevos en el mundo de las *Series Temporales* y actualizando los datos de inflación y tipo de cambio.











