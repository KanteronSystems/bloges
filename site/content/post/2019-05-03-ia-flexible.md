---
date: 2019-05-01T00:14:57+00:00
title: Kanteron presenta la Inteligencia Artificial Flexible
tags: ["kanteron", "producto"]
image: "httpss://res.cloudinary.com/jcortell/image/upload/v1556050843/Kanteron/AIcalculation.png"
comments: true     # set false to hide Disqus comments
share: true        # set false to share buttons
thumbnailImagePosition: left
thumbnailImage: httpss://res.cloudinary.com/jcortell/image/upload/v1556050843/Kanteron/AIcalculation.png
coverImage: httpss://res.cloudinary.com/jcortell/image/upload/v1556050843/Kanteron/AIcalculation.png
metaAlignment: center
coverMeta: out

---

La Inteligencia Artificial (IA) flexible significa que puede elegir el conjunto de datos que mejor se adapte a su caso de uso y aplicarlo a sus imágenes médicas relevantes. Incluimos un conjunto de entrenamiento para el cáncer de próstata como punto de partida, ¡pero eso es solo el comienzo!
La configuración de IA permite al usuario elegir el modelo deseado de la lista de todos los modelos disponibles junto con sus descripciones.

<!--more-->

![Elija su propio conjunto de datos](httpss://res.cloudinary.com/jcortell/image/upload/v1556050843/Kanteron/AIdataset.png)

IA Flexible es resultado de la colaboración del Laboratorio de Informática Médica de la Queen's University y el Laboratorio de Planificación Quirúrgica de la Escuela de Medicina de Harvard, que permite el despliegue de modelos de IA para una segunda opinión de los radiólogos con la ayuda de IA, al tiempo que proporciona una visualización de imágenes estándar y esquemas de información.

Buscamos clientes-socios que deseen ser pioneros en la aplicación de la IA en imágenes médicas y desarrollar su propia experiencia en una plataforma flexible que les permita la libertad de aplicar esta emocionante tecnología a muchos casos de uso. Además, definitivamente queremos trabajar con usted si también desea correlacionar la imagen de patología y los datos genómicos con imágenes médicas, de una manera que solo la plataforma de Kanteron permite hoy.

Si desea ser uno de los pioneros y aprovechar la última y más flexible solución de IA disponible para imágenes médicas, ¡contáctenos!

{{< alert info >}}

Detalles técnicos.-

El componente IA se desarrolla en Flask (*microframework* de Python) y cada modelo de IA se envuelve en un punto final de interfaz de programa de aplicación (API). El tiempo de predicción es inferior a un segundo para cada hallazgo en una máquina CPU; sin embargo, los modelos se pueden escribir de manera que se beneficien del poder de las GPU.

Para cada caso, la aplicación presenta 4 pilas separadas de imágenes de Resonancia Magnética ponderadas en T2, mapa ADC, DWI de alto valor b y mapa Ktrans obtenidos a partir de imágenes con contraste. Después de elegir el modelo de IA deseado, el usuario puede ubicar la sonda en cualquier ubicación en las imágenes para ver el resultado de la predicción de IA (el usuario puede confirmar o descartar un hallazgo después de inspeccionar la predicción de IA). La información se pasará a los informes utilizando PI-RADS v2. La aplicación le da al usuario una proyección de mensaje de retroalimentación de los resultados en las 4 vistas de imagen y los resultados probados histológicamente. Las distancias relativas (en mm) entre los hallazgos definidos por el usuario y las ubicaciones de las biopsias también se calculan y se muestran.

El modelo incluido está capacitado en imágenes de resonancia magnética del Centro Médico de la Universidad de Radboud (Nijmegen) que contienen más de 200 imágenes de Resonancia Magnética con etiquetas. La arquitectura del modelo está adaptada de Densenet y recibe información de T2, ADC, BVAL y Ktrans, con un rendimiento del modelo AUC de 0,8 en 5 veces de validación cruzada.

Puntuación T2 / Puntuación DWI / Puntuación DCE para la Zona Periférica (PZ) o Zona de Transición (TZ) que conduce a PI-RADS Puntuación General - Zona Periférica (a) y Zona de Transición (b).

PI-RADS v2 tiene la intención de estandarizar la presentación de informes de mpMRI para reducir la variabilidad en las interpretaciones y resumir los niveles de riesgo / sospecha de cáncer clínicamente significativo.
httpss://www.acr.org/-/media/ACR/Files/RADS/Pi-RADS/PIRADS-V2.pdf
Hassanzadeh E, Glazer D, Dunne R, Fennessy F, Harisinghani M, Tempany C. Prostate imaging reporting and data system version 2 (PI-RADS v2): a pictorial review.  Abdominal Radiology. 2016;42(1):278-289. doi:10.1007/s00261-016-0871-z

{{< /alert >}}
