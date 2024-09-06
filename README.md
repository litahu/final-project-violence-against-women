# 👩 Previniendo la violencia contra la Mujer, niñas y niños a nivel nacional del 2013-2018

### 📂 Revisión de datasets públicos

ODS | Nombre del dataset | Herramienta | Descripción del proyecto
---|---|---|---
Salud| ⚠️Violencia contra las mujeres, niños y niñas (capítulo XII de ENDES- “ Encuesta demográfica y de salud familiar” ) [2013](https://www.datosabiertos.gob.pe/dataset/violencia-contra-las-mujeres-ni%C3%B1os-y-ni%C3%B1as-capitulo-xii-encuesta-demogr%C3%A1fica-y-de-salud-7), [2014](https://www.datosabiertos.gob.pe/dataset/violencia-contra-las-mujeres-ni%C3%B1os-y-ni%C3%B1as-capitulo-xii-encuesta-demogr%C3%A1fica-y-de-salud-5), [2015](https://www.datosabiertos.gob.pe/dataset/violencia-contra-las-mujeres-ni%C3%B1os-y-ni%C3%B1as-capitulo-xii-encuesta-demogr%C3%A1fica-y-de-salud-3), [2016](https://www.datosabiertos.gob.pe/dataset/violencia-contra-las-mujeres-ni%C3%B1os-y-ni%C3%B1as-capitulo-xii-encuesta-demogr%C3%A1fica-y-de-salud-0), [2017](https://www.datosabiertos.gob.pe/dataset/violencia-contra-las-mujeres-ni%C3%B1os-y-ni%C3%B1as-capitulo-xii-encuesta-demogr%C3%A1fica-y-de-salud) y [2018](https://www.datosabiertos.gob.pe/dataset/violencia-contra-las-mujeres-ni%C3%B1os-y-ni%C3%B1as-capitulo-xii-encuesta-demogr%C3%A1fica-y-de-salud-9)| Google sheet y Looker Studio | Se procedió con la limpieza de datos en Google Sheet(siguiendo las buenas prácticas de ETL). Luego se canalizó los datos para manejar dentro del tablero de control de Looker Studio. 

<br>

### 📊 Análisis de la información
Ante la falta de un plan estrátegico a nivel nacional para prevenir la violencia contra la mujer,niños y niñas(de aquí en adelante población vulnerable) se estan llevando a cabo "programas reactivos" que alivian el problema en el corto plazo. Sin embargo, ante la creciente ola de violencia familiar es vital abordar este tema para construir puentes preventivos de largo plazo.
En ese sentido nos hemos enfocado en comprender esta creciente problemática. Inicialmente se abordo un Analisis exploratorio de los datos que nos ayuden a identificar variables, tendencias y metricas para entender como incide la violencia contra la mujer en el Perú  

###### Formulación del problema
- ¿Cuál es el departamento con más casos de violencia sobre la población vulnerable, cuál es la tendencia y el grupo etario más afectado durante el período 2013 al 2018?
- Grupo de estudio: mujeres del Perú de 15 a 45 años, en toda su diversidad( mujeres indígenas, mujeres afrodescendientes, mujeres en situación de discapacidad, mujeres lesbianas, trans, migrantes, así como todas aquellas en situación de especial vulnerabilidad) y sus menores hijos

###### Teoría
- Vilencia contra la mujer(VCM): consiste en cualquier acción o conducta que causa muerte, daño o sufrimiento físico, sexual, psicológico y económica a las mujeres por su condición, tanto en el ámbito público como en el privado 
- Ciclo de violencia: se incrementa de acuerdo al poder y control que ejerza el sujeto acctivo sobre el sujeto pasivo. Comienza con violencia verbal, luego fisica y sexual. Un caso extremo al pasar estas fases es el feminicidio 

###### Fuentes
- MIMP (2022). Marco conceptual para la prevencion de la violencia de genero contra las mujeres Plataforma del Estado Peruano.[Url]( https://www.gob.pe/institucion/mimp/informes-publicaciones/2842546-el-marco-conceptual-para-la-prevencion-de-la-violencia-de-genero-contra-las-mujeres)
- Sria. Equidad de Género y Derechos Humanos SNTE. (2018, 10 septiembre). Ciclo de la violencia [YouTube](https://www.youtube.com/watch?v=pHGD4R4gHK4)

<br>

###### Resultado del análisis 
Frente al [Reporte de los efectos de la violencia familiar del 2013 - 2018 ](https://lookerstudio.google.com/reporting/6db874ae-cf89-41d5-b82b-6e1d2ef2ec02) determinamos los siguientes hallazgos:

<ol> 
<li>
 👨‍👨‍👦‍👦 En la parte inicial del ciclo de violencia, Apurímac es el departamento que ha sostenido la violencia psicológica sobre la media durante 3 años consecutivos(2013-2015). Luego tiene una ligera caída con un rebote marcando una tendencia en ascenso. La posible causa a esta resistencia sobre la media es el factor cultural de subordinación institucionalizada(creencias, costumbres y perjuicios)
</li> 
<li>
 🏥 Apurímac presenta 4 años(2014-2017) persistentes de violencia física siendo el 2015 el más extremo
</li>
 <li>
 🤰 En cuanto a la violencia sexual Apurímac es el que más persistencia tiene sobre la media (variación de ± 5pp) 
 </li>
<li>
 Este progresismo de la violencia en Apurímac se apoya en la insatisfacción institucional. Más del 50% de las mujeres violentadas durante los años 2013, 2014 y 2015 recurrían a solicitar ayuda a "personas cercanas"(personas no especilizada como: padres, vecinos, amigos,hermanos, etc). Al respecto se puede ver que existe una tendencia en ascenso dentro de la evolución psicológica, física y sexual durante esos mismos años. En el año 2016 hay un quiebre en esa tendencia pero con un efecto rebote para los años 2017 y 2018. A pesar que existió un fortalecimiento institucional con programas del MIDIS, la principal tendencia en ascenso es la violencia psicológica
</li>
<li>
👦 Con el fortalecimiento de las instituciones se ve un ligero control de la violencia contra la mujer pero muy por lo contrario para los menores de edad. En la encuesta del ENDES señala que los menores de edad presenciaron actos de violencia física y sexual del padre hacía la madre. Cabe resaltar que para llegar a esos grados de violencia no solamente se efectuaron durante los años señalados por dicha encuesta si no que se vienn arrastarndo de años antecesores(en un intervalo no mas de 10 años)
</li>
<li>
👨‍✈️ La confianza institucional peribida por las mujeres es menor del 50%. En efecto, existen mujeres que no asisten a denunciar la violencia. Identificando asi al grupo etario mas vulnerado: "mujeres entre 15 a 19 años". Ello se respalda por las razones que argumentan las mujeres para no realizar dicha denuncia.
</li>
<li>
👩 El 44,8% de las mujeres de 15-19 años señala que no es necesario hacer la denuncia, el 16,2% señala que ella tenía la culpa y un 11,4% señala que no lo hace para no causar problemas a su agresor(en estos items se evidencia el poder y control que tiene el agresor sobre estas feminas). Sumado a ello se agrava por la falta de información institucional por lo que un 7,5% señala que no sabe donde ir/ no conoce los servicios para las mujeres violentadas entreo otros.
</li>
</ol>

<br>

### 🚩 Identificación del hallazgo
