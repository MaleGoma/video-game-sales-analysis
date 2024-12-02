# Análisis de ventas de videojuegos
Este proyecto analiza las ventas de videojuegos por región, plataforma y género para identificar patrones clave que permitan a la tienda online Ice **detectar proyectos prometedores** y **planificar campañas publicitarias efectivas**. Al entender las dinámicas de mercado en Norteamérica, Europa y Japón, se busca **optimizar estrategias de marketing** y **maximizar el retorno de inversión en los títulos más prometedores**.

### Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23357ebd.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![SciPy](https://img.shields.io/badge/SciPy-%23357ebd.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Pruebas de hipótesis](https://img.shields.io/badge/Pruebas_de_hipótesis-295F98?style=for-the-badge)
![Visualización de datos](https://img.shields.io/badge/Visualización_de_datos-295F98?style=for-the-badge)

## Preguntas clave
1. ¿Cuáles son las plataformas con mayores ventas globales y cómo varían estas por región?
2. ¿Qué géneros de videojuegos son más populares en Norteamérica, Europa y Japón?
3. ¿Qué relación existe entre las puntuaciones de usuarios/críticos y las ventas globales de videojuegos?
4. ¿Existen diferencias significativas en las calificaciones promedio entre plataformas y géneros?

## Metodología
- **Preprocesamiento de datos:** Limpieza de datos (valores ausentes, duplicados, formatos de columnas, y tipos de datos adecuados).
- **Análisis exploratorio de datos:** Identificación de las plataformas y géneros más populares y evaluación de la correlación entre puntuaciones de usuarios/críticos y ventas.
- **Segmentación regional:** Comparación de preferencias por plataformas y géneros en Norteamérica, Europa y Japón.
- **Pruebas de hipótesis:** Comparación de calificaciones promedio entre plataformas y géneros.

## Conclusiones y recomendaciones
### Dinámica de ventas por región:
- Norteamérica y Europa prefieren juegos de acción y disparos en consolas como Xbox y PlayStation.
- Japón, en cambio, favorece juegos de rol en plataformas portátiles como Nintendo 3DS.

### Efecto de las reseñas:
- Las puntuaciones de críticos tienen una correlación moderada positiva con las ventas (coeficiente ≈ 0.41).
- Las puntuaciones de usuarios presentan correlación casi nula, lo que sugiere que los consumidores priorizan otras métricas al elegir juegos.

### Pruebas de hipótesis:
- Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son iguales.
- Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.

### Estretegias recomendadas:
- Dado que PS4 y Xbox One se mantienen relevantes en ventas globales, recomendamos enfocar campañas publicitarias en estas plataformas.
- Debido a las preferencias de usuarios en esta región, recomendamos enfocar promociones de RPG en Japón e impulsar títulos de acción y disparos en mercados occidentales.

## Diccionario de datos
El archivo cargado contiene un dataset con información sobre videojuegos, sus características y ventas. El dataset incluye los siguientes campos:

- `Name` — Nombre del videojuego.
- `Platform` — Plataforma para la cual se lanzó el videojuego (e.g., Wii, NES, GB).
- `Year_of_Release` — Año de lanzamiento del videojuego.
- `Genre` — Género del videojuego (e.g., Sports, Platform, Racing).
- `NA_sales` — Ventas en América del Norte (en millones de unidades).
- `EU_sales` — Ventas en Europa (en millones de unidades).
- `JP_sales` — Ventas en Japón (en millones de unidades).
- `Other_sales` — Ventas en otras regiones (en millones de unidades).
- `Critic_Score` — Puntuación promedio otorgada por críticos (escala de 0 a 100).
- `User_Score` — Puntuación promedio otorgada por usuarios (generalmente en una escala de 0 a 10, aunque puede tener valores atípicos como tbd).
-`
