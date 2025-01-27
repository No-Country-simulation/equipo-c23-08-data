# equipo-c23-08-data
Análisis exhaustivo de los comentarios de Play Store de Google acerca de la app UBER.

# Uber Customer Reviews Dataset (2024)

## Acerca del Conjunto de Datos

**Título:** Conjunto de Datos de Opiniones de Clientes de Uber (2024)  
**Subtítulo:** Análisis de opiniones y perspectivas de más de 12,000 opiniones de Google Play Store

### Descripción General

Este conjunto de datos contiene más de 12,000 opiniones de clientes sobre la aplicación Uber recopiladas de Google Play Store. Las reseñas brindan información detallada sobre las experiencias de los usuarios, incluidas:
- Calificaciones.
- Comentarios sobre servicios.
- Respuestas de los desarrolladores.

Los datos han sido limpiados y anonimizados para garantizar el cumplimiento de las normas de privacidad y un uso ético. Este conjunto de datos es ideal para proyectos de:
- **Análisis de sentimientos.**
- **Procesamiento del lenguaje natural (PLN).**
- **Aprendizaje automático.**

---

## Aplicaciones de Ciencia de Datos

### Análisis de Sentimientos
- Clasificar las reseñas como **positivas**, **neutrales** o **negativas** utilizando `score` y `content`.
- Identificar tendencias en la **satisfacción del cliente** a lo largo del tiempo.

### Procesamiento del Lenguaje Natural (PLN)
- Realizar **modelado de temas** para descubrir patrones en los comentarios.
- Generar **nubes de palabras** para visualizar palabras utilizadas con frecuencia en las reseñas.

### Aprendizaje Automático
- Entrenar un modelo de **clasificación de sentimientos** utilizando el texto de las reseñas como entrada.
- Predecir la **satisfacción del cliente** basándose en comentarios textuales.

### Perspectivas de Negocios
- Analizar comentarios para identificar **fortalezas** (por ejemplo, "conductores amigables") y **debilidades** (por ejemplo, "tiempos de espera largos").
- Comparar el desempeño de la aplicación en diferentes versiones utilizando `appVersion`.

### Análisis de Series Temporales
- Seguir los cambios en las **calificaciones promedio** a lo largo del tiempo utilizando `at`.
- Identificar patrones estacionales o anomalías en los comentarios.

### Análisis del Comportamiento del Cliente
- Estudiar la correlación entre `score` y `thumbsUpCount` para entender el impacto de las reseñas.
- Analizar el efecto de las respuestas de los desarrolladores (`replyContent`) en la satisfacción del cliente.

---

## Descriptores de Columnas
       
| **Columna**            | **Descripción**                                                                 |
|-------------------------|---------------------------------------------------------------------------------|
| `userName`             | Nombre de usuario anónimo del revisor.                                         |
| `userImage`            | URL de la imagen de perfil del revisor (si está disponible).                   |
| `content`              | Contenido textual de la reseña que describe la experiencia del usuario.        |
| `score`                | Calificación numérica dada por el usuario (1-5).                               |
| `thumbsUpCount`        | Número de "Me gusta" que recibió la reseña.                                    |
| `reviewCreatedVersion` | Versión de la aplicación en el momento de la reseña (si está disponible).       |
| `at`                   | Marca de tiempo que indica cuándo se publicó la reseña.                        |
| `replyContent`         | Respuesta del desarrollador a la reseña (si la hay).                           |
| `repliedAt`            | Marca de tiempo que indica cuándo respondió el desarrollador (si la hay).       |
| `appVersion`           | Cadena de versión de la aplicación asociada con la reseña (si está disponible).|

---

## Datos Extraídos Éticamente

Este conjunto de datos fue recopilado respetando las normas éticas de raspado web:
- Los datos provienen de reseñas disponibles públicamente en Google Play Store.
- Se eliminaron datos personales identificables (PII) como correos electrónicos, imágenes y números telefónicos.

---

## Fuentes y Créditos
- **Fuente del conjunto de datos:** [Kaggle - Uber Customer Reviews Dataset 2024](https://www.kaggle.com/datasets/kanchana1990/uber-customer-reviews-dataset-2024)
- **Google Play Store:** Por brindar acceso a reseñas de aplicaciones públicas.
- **DALL·E 3:** Para generar una imagen visualmente atractiva del conjunto de datos.

---

## Cómo Contribuir
¡Contribuciones al análisis y mejora del conjunto de datos son bienvenidas! Puedes proponer ideas o abrir un pull request en este repositorio.

---

## Licencia
Este proyecto sigue las normas y condiciones de uso de Kaggle y Google Play Store. Asegúrate de respetar las restricciones de uso ético en tus proyectos derivados.
