# Título: Emergencias ambientales🌍 | Python, PowerBI 
# 🧠 Objetivo: 
</p>
El objetivo es cargar, explorar y construir un analisis estadisticos con la base de datos publica que se obtuvo de la Institución: Procuraduría Federal de Protección al Ambiente (PROFEPA) sobre las emergencias ambientales relacionadas con sustancias quimicas que se presentaron en los primeros 3 trimestres de 2025 en México

 </p>

# 📂 Datos: 
</p>
**07_Emergencias_ambientales_2025.csv** → información de los estado del país México y las emergencia ambientales suscitadas (derrames, explosion, incendio, fugas, otros)  
</p>
 
# ⚙️ Proceso: 
* <p align="justify"> Cargar y explorar: se cargo la base de datos y se exploro para identificar el numero de columnas, filas y los tipos de columnas para corroborar que coincidan con el tipo de dato.</p>
* <p align="justify">Identificación de problemas de calidad de datos: se reviso que no existan valores ausentes, nulos o duplicados. Se realizo una limpieza a la columna estado para eliminar espacios y estandarizarlos con title</p>
* <p align="justify"> Resumen estadistico: Realice la agrupacion y suma de las emergencias ambientales totales de todos los estados. Obtuve cuantas emergencias se generaron por tipo de emergencia y por estado. Se identifico cual es el estado con mayor y menor emergencias ambientales y tambien que estados tienen mas derrames, fugas, incendios, explosiones y otros  </p>
 * <p align="justify"> Con numpy se obtuvo el indice de diversidad de emergencias por estado (verificar si el estado tiene muchos tipos de problemas o solo uno)</p>
 
# Entregable:

🔗 **Notebook del proyecto:**

[Ver análisis completo en Jupyter Notebook](https://github.com/estephaniemoncada-cell/Analisis_ConnectaTel/blob/main/S7%20Version-Estudiante-Project-ConnectaTel.ipynb)

📊 **Dashboard del proyecto:**


# Insights 
* <p align="justify"> ⚠️ Problemas detectados en los datos:

* <p align="justify">En el dataset no se obsevaron valores duplicados, nulos, con falta de ortografia, se encontraron los datos limpios.

</p>🔍 Analisis de emergencias ambientales</p>
</p>
Se detecto que en los 3 trimestres del año 2025 en el país México las emergencis ambientales que mas se presentaron fueron 184 fugas, seguido de 178 derrames, 152 explosiones.</p>

</p>📊 Segmentos por Estado</p>
</p>
<p align="justify"> La ciudad de México es el estado con más emergencias ambientales registradas, esto se puede deber a multiples factores, sin embargo, la emergencia ambiental mas predominante fue las fugas.
<p align="justify"> Se detecto que el estado con mas derrames es el estado de Veracruz
<p align="justify"> El estado con mas incendios fue el estado de México
<p align="justify"> El estado con mas explosiones fue el estado de México
<p align="justify"> El estado con mas fugas fue la ciudad de México
<p align="justify"> En el top 3 de estados con mayor indice de emergencia ambientales esta: Ciudad de México, Estado de México y Nuevo León, estos tres estados son donde existe mayor concentranción de habitantes y por lo tanto mayor numero de empresas.
<p align="justify"> Aunque la Ciudad de México obtuvo el primer lugar como estado con mayor número de emergencias ambientales es importante recalcar que el Estado de México es quien mayor diversidad de emergencias tiene, es decir, es quien lidera el ranking en 3 emergencias ambientales (derrame, incendio, explosión), mientras la ciudad de México solo lidera en fugas</p>
</p>
➡️ Esto sugiere que .. 
-<p align="justify"> Las empresas y obras en construcción deben comprometerse mas con el cuidado del medio ambiente, por lo que se debe reforzar las inspecciones en campo por parte de las instituciones gubernamentales, para identificar si se les esta dando cumplimiento a las leyes y normativas ambientales.
-<p align="justify"> Pos su parte se recomienda que las empresas u obras de  contrucción realicen reportes periodicos a la institucion gubernamental sobre las medidas de prevención y mitigación para evitar que se presenten emergencias ambientales, esto puede ser por medio de una plataforma nacional, en donde se recopile la información, tomando como puntos de interes aquellas empresas que no envien información o no cumplan con las leyes o normas, para inspecciones mas puntuales.</p>
