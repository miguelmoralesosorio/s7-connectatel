# Análisis de clientes de ConnectaTel

## Descripción y objetivo

Este proyecto analiza el comportamiento de los clientes de ConnectaTel en el uso de llamadas y mensajes. Se estudian la cantidad de llamadas, la cantidad de mensajes y la duración de las llamadas, considerando el plan contratado y el grupo de edad. El objetivo es identificar patrones de consumo y proponer opciones de planes acordes con las necesidades de los clientes.

## Preguntas de negocio

- ¿Cómo varía el uso de llamadas y mensajes según el plan y el grupo de edad?
- ¿Qué nivel de uso concentra a la mayoría de los clientes y qué tipo de plan podría cubrir mejor sus necesidades?

## Datasets usados

- **`users`**: información de los clientes, como ciudad, plan contratado, edad, fecha de registro y fecha de cancelación.
- **`usage`**: actividad de uso de los servicios, incluidas llamadas, mensajes, duración de llamadas y fechas de actividad.

## Metodología resumida

Se limpiaron y validaron los datos, revisando valores nulos, sentinels, duplicados y posibles valores inválidos. Después se realizó un análisis exploratorio y se segmentó a los clientes por uso, grupo de edad y plan. Las visualizaciones y el análisis estadístico ayudaron a identificar patrones y formular recomendaciones de negocio.

## Principales hallazgos

- **Uso de servicios:** La mayoría de los clientes presenta un uso bajo o medio de llamadas y mensajes; un grupo menor concentra un consumo elevado, especialmente en duración de llamadas.
- **Segmentación:** El grupo de edad de 30 a 60 años reúne la mayor cantidad de clientes. Entre los usuarios jóvenes predomina un nivel de uso bajo o medio.
- **Recomendación de negocio:** Mantener los planes Básico y Premium según el nivel de consumo, considerar un plan de entrada económico para jóvenes y ofrecer opciones con llamadas y mensajes ilimitados a clientes de alto uso para apoyar la retención y la rentabilidad.

## Cómo ejecutar el notebook

Abre el archivo `.ipynb` en Jupyter Notebook o JupyterLab y ejecuta las celdas en orden, desde la primera hasta la última.

