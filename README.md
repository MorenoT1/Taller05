<div align="center">

# ⚽ Lesiones en el Fútbol Profesional

### Introducción a la Ciencia de Datos · Grupo 3

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Arial&size=20&pause=1200&color=2E7D32&center=true&vCenter=true&width=800&lines=Proyecto+de+ciencia+de+datos+aplicado+al+fútbol;¿Se+pueden+anticipar+las+lesiones+con+datos?;Análisis+de+carga+física+y+riesgo+de+lesión)](https://git.io/typing-svg)

<br/>

<img src="https://img.shields.io/badge/Lesiones_registradas-2.184-1b5e20?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Incidencia-8,94_por_1.000_h-2e7d32?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Promedio_por_equipo-50_lesiones-388e3c?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Predicción-3_semanas-43a047?style=for-the-badge&logoColor=white"/>

<br/><br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Comfortaa&size=22&pause=1200&color=0d4a2a&center=true&vCenter=true&width=1000&height=60&lines=Estudiantes)](https://git.io/typing-svg)

**Juan Felipe Moreno** · **Evelyn Alguero Villamizar**  
**Juan Gonzalez Claros** · **Samuel Colmenares Tovars**

**Docente:** Rodrigo Taborda

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Comfortaa&size=22&pause=1200&color=20b267&center=true&vCenter=true&width=1000&height=60&lines=Detectando+riesgo+antes+de+que+sea+tarde...;Ciencia+de+datos+aplicada+al+deporte;Análisis+de+datos+con+impacto+real)](https://git.io/typing-svg)

</div>

<p align="center">
  <img src="https://grupopineda.eu/wp-content/uploads/2022/03/shutterstock_1912601503.jpg" alt="Fútbol profesional y lesiones" width="88%"/>
</p>

> "Un equipo profesional de 25 jugadores sufre en promedio 50 lesiones por temporada. La ciencia de datos existe para cambiar ese número."  
> **Barça Innovation Hub, 2023**

---

<p align="center">
  <img src="https://imfisfisioterapia.com/wp-content/uploads/2023/02/iStock-1025958882.jpg" alt="Lesión en fútbol" width="82%"/>
</p>

## ⚽ ¿Por qué este tema?

Somos un grupo al que le apasiona el fútbol y que, cuando empezamos a pensar en un proyecto de ciencia de datos, no tardamos mucho en llegar a la misma conclusión: las lesiones son uno de los problemas más frustrantes del deporte profesional y no existe una solución definitiva. Por eso nos quedamos con una pregunta sencilla pero muy importante: **¿se pueden anticipar?**

Investigamos y encontramos que la respuesta es sí, al menos parcialmente. Además, descubrimos que ya existen datos públicos que pueden ayudar a estudiar este problema. Así fue como decidimos aplicar lo que estamos aprendiendo en ciencia de datos a un tema que realmente nos interesa.

---

## 📋 ¿De qué trata el proyecto?

El proyecto busca construir un **modelo predictivo de clasificación** que identifique, a partir de datos de carga física y contexto de temporada, si un jugador de fútbol profesional tiene alto riesgo de sufrir una lesión muscular o ligamentosa en las próximas semanas.

Según un estudio sobre incidencia lesional en el fútbol profesional español, durante una temporada completa se registraron **2.184 lesiones en total**, lo que equivale a una incidencia de **8,94 lesiones por cada 1.000 horas de exposición**. Además, cada equipo tuvo en promedio **80,89 lesiones y 909 días de baja** por temporada (Apunts Sports Medicine, 2012). Estos datos muestran que las lesiones no son solo un problema deportivo, sino también humano y económico.

De la misma manera, la FIFA ha documentado una tasa de **8,5 lesiones por cada 1.000 horas de juego** en el fútbol profesional, mientras que en el fútbol amateur esa cifra sube hasta **20 por cada 1.000 horas** (Fisioterapia Francisco Lledó, 2025). Esto demuestra que el manejo de datos y la prevención pueden marcar diferencias importantes.

### 📊 Cifras de contexto

| Indicador | Dato verificado | Fuente |
|---|---|---|
| Lesiones por equipo profesional al año | ~50 por plantilla de 25 | Barça Innovation Hub (2023) |
| Incidencia en fútbol profesional español | 8,94 / 1.000 h de exposición | Apunts Sports Medicine (2012) |
| Días de baja promedio por rotura muscular | 20,4 días por lesión | Apunts Sports Medicine (2012) |
| Tasa FIFA en competición profesional | 8,5 / 1.000 h de juego | Fisioterapia Francisco Lledó (2025) |
| Jugadores lesionados en Premier League (Nov. 2023) | Más de 30 en 11 jornadas | Telemundo (2023) |
| Aumento de lesiones en ligas top 2023–2024 | Tendencia ascendente desde 2020–2021 | Newtral (2024) |
| Reducción estimada con analytics preventivo | 25 % a 30 % | Euncet Business School (2025) |

---

<p align="center">
  <img src="https://tutoeris.co/wp-content/uploads/2025/07/tecnicas.png" alt="Análisis de datos" width="78%"/>
</p>

## 🗂️ Los datos con los que trabajamos

Trabajamos con datos de acceso público provenientes de plataformas especializadas en análisis de fútbol. Combinamos registros epidemiológicos de lesiones documentados en estudios académicos con estadísticas de partido publicadas por herramientas como **StatsBomb** y **Opta**, que son proveedores de datos muy utilizados por clubes profesionales de Europa (Sports Data Campus, 2025).

Además, el portal **Barça Innovation Hub** publica estudios epidemiológicos con datos reales de temporadas profesionales, que utilizamos como referencia metodológica y para validar nuestros hallazgos.

### 📐 Variables del modelo

| # | Variable | Descripción | Tipo |
|---|---|---|---|
| 1 | Minutos acumulados (7 días) | Carga física reciente del jugador | Numérica |
| 2 | Días desde el último partido | Tiempo de recuperación entre encuentros | Numérica |
| 3 | Partidos consecutivos | Cantidad de juegos sin descanso significativo | Numérica |
| 4 | Distancia recorrida por partido | Indicador de intensidad física | Numérica |
| 5 | Historial de lesiones previas | Lesiones registradas en temporadas anteriores | Numérica |
| 6 | Momento de la temporada | Inicio, mitad o tramo final | Categórica |
| 7 | Posición en el campo | Portero, defensa, centrocampista, delantero | Categórica |
| 8 | Carga aguda vs. crónica | Relación entre esfuerzo reciente y acumulado | Numérica |
| 9 | Variable objetivo | ¿El jugador sufrió lesión en las próximas 3 semanas? | Binaria |

---

<p align="center">
  <img src="https://img.freepik.com/foto-gratis/jugadores-futbol-accion-estadio-profesional_654080-1746.jpg?semt=ais_hybrid&w=740&q=80" alt="Partido de fútbol profesional" width="84%"/>
</p>

## 🔍 Lo que encontramos

Al explorar los datos, encontramos varios resultados importantes.

El primero fue que las **lesiones musculares son de las más frecuentes** en el fútbol profesional, representando entre el **10 % y el 20 % de todas las lesiones** registradas. Sin embargo, no son las más graves por caso individual, ya que las pubalgias y las fracturas generan más días de baja por episodio (Apunts Sports Medicine, 2012).

El segundo hallazgo tiene que ver con el calendario. Según la UEFA, el número de lesiones de isquiotibiales se ha **duplicado en los últimos 20 años** debido al aumento en la intensidad del juego. Además, el *British Journal of Sports Medicine* relaciona el aumento de acciones de alta intensidad con más lesiones en tendones y rodillas (Telemundo, 2023).

El tercer hallazgo fue institucional. En la temporada 2023–2024, las lesiones aumentaron en la **Premier League, LaLiga, Bundesliga y Serie A**, mientras que la Ligue 1, al reducir el número de equipos participantes, registró una disminución del **26 % en el promedio de lesiones por equipo** (Newtral, 2024). Esto sugiere que la densidad del calendario es un factor importante de riesgo.

### 🦵 Lesiones por tipo y días de baja — fútbol profesional español

| Tipo de lesión | Días de baja por equipo/temporada | Días promedio por lesión | Frecuencia relativa |
|---|---|---|---|
| Rotura muscular | 267,2 días | 20,4 días | Alta |
| Lesión ligamentosa | 182,1 días | 15,0 días | Alta |
| Sobrecarga muscular | 87,6 días | Variable | La más frecuente |
| Pubalgia | No en top de frecuencia | 29,2 días | Media-baja |
| Fractura | Poco frecuente | 28,0 días | Baja |

> Fuente: Apunts Sports Medicine (2012), incidencia lesional en el fútbol profesional español.

### 📅 Riesgo según momento de la temporada

| Etapa | Riesgo estimado | Factor principal |
|---|---|---|
| Pretemporada | Medio | Retorno tras descanso sin carga progresiva |
| Inicio de temporada regular | Medio-alto | Ritmo competitivo brusco después del descanso |
| Mitad de temporada | Alto | Acumulación de fatiga física y mental |
| Final de temporada | Muy alto | Fatiga máxima y picos de carga |
| Competición internacional entre semana | Alto | Doble exigencia con poca recuperación |

---

<p align="center">
  <img src="https://scontent.fbog2-3.fna.fbcdn.net/v/t1.6435-9/81533347_584227908798680_565385101093896192_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=7b2446&_nc_ohc=Npewjsr4JAoQ7kNvwGvxtjN&_nc_oc=AdrKNpaNIngIhmUXeFVUCiZmiKlX5h1kIdKNSBOPdkcUNzgN1ylnnWRl3fqNM4nN5ok&_nc_zt=23&_nc_ht=scontent.fbog2-3.fna&_nc_gid=EnznFelUd5RPfU4Elxh-8A&_nc_ss=7a30f&oh=00_AfyZqTudeCdqdH7DOMhIjkM0FzZMLJQrOSMPVWpRXPCbRA&oe=69EE9CE2" alt="Trabajo de análisis" width="82%"/>
</p>

## ⚙️ Cómo lo hicimos

Seguimos el ciclo estándar de ciencia de datos, adaptado al contexto del fútbol profesional.

### Fase 1. Entendimiento del problema

Antes de trabajar con los datos, definimos con claridad qué queríamos predecir. Decidimos que la variable objetivo sería si un jugador sufriría una lesión muscular o ligamentosa en las siguientes **3 semanas**, porque ese tiempo puede ser útil para que un cuerpo técnico tome decisiones de carga y rotación.

### Fase 2. Recolección de datos

Usamos fuentes públicas y académicas que nos permitieran tener tanto información médica sobre lesiones como información relacionada con el rendimiento y la carga física de los jugadores. Entre las fuentes más importantes estuvieron estudios sobre incidencia lesional, plataformas de análisis de fútbol y reportes recientes sobre el aumento de lesiones en ligas europeas.

**Fuentes utilizadas:**

- Apunts Sports Medicine (2012)
- Barça Innovation Hub (2023)
- StatsBomb / Opta
- Newtral (2024)
- FIFA / UEFA

### Fase 3. Exploración de datos

Revisamos la distribución de lesiones por tipo, por posición, por momento de la temporada y por carga acumulada. También vimos que los datos están desbalanceados, ya que hay muchos más registros sin lesión que con lesión, lo cual representa un reto importante para el análisis.

### Fase 4. Preparación de variables

Construimos variables derivadas como la relación entre carga reciente y carga acumulada, el número de partidos jugados en los últimos **14 días** y el tiempo transcurrido desde la última lesión registrada. Esto nos ayudó a representar mejor el desgaste físico de cada jugador a lo largo de la temporada.

### Fase 5. Modelado

| Modelo | ¿Por qué lo probamos? | Resultado |
|---|---|---|
| Regresión Logística | Como punto de partida para comparar | Probado |
| Random Forest | Porque funciona bien con varios tipos de variables | Probado |
| Gradient Boosting | Porque puede adaptarse bien a este tipo de problema | Probado |
| XGBoost | Porque ofreció los resultados más sólidos | Seleccionado |

### Fase 6. Evaluación

En esta última fase revisamos cuál de los modelos se comportaba mejor frente al problema que queríamos resolver. Más que fijarnos solamente en cuál acertaba más veces, nos interesaba ver cuál daba resultados más útiles para un caso real como el de las lesiones en el fútbol.

También tuvimos en cuenta que en este tipo de problemas no basta con decir que un modelo “funciona bien”, sino que es importante analizar si realmente ayuda a identificar a tiempo a los jugadores que podrían estar en mayor riesgo. Por eso comparamos los resultados obtenidos con cada modelo y miramos cuál ofrecía el mejor equilibrio entre detectar posibles lesiones y no marcar demasiados casos que en realidad no representaban un riesgo alto.

Después de hacer esa comparación, vimos que **XGBoost** fue el modelo que mostró el comportamiento más sólido dentro del proyecto. Por esa razón, lo tomamos como la mejor opción para continuar el análisis y como la base principal de nuestra propuesta.

---
