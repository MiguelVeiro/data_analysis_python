# Análisis de Datos con Python

Este repositorio contiene un dataset y un Notebook sobre el que se realizan análisis del dataset.

El Notebook intenta responder a las siguientes preguntas utilizando los datos disponibles en el dataset:

1. Representa gráficamente el número de cancelaciones y reservas confirmadas para cada fecha de check in (date_checkin).

2. Número de reservas confirmadas y cancelaciones para cada agencia (agengy_id). Selecciona únicamente el top 10 en cuanto a volumen total de reservas.

3. Evolución del precio mínimo, precio medio, precio máximo y revenue para cada fecha de check in (date_checkin) (preferiblemente representadas en la misma gráfica superpuestas, revenue puede ir según la escala) (Nótese: revenue = mean_price_per_night * nights)
    - Se puede extraer alguna conclusión al comparar la evolución entre los precios y el revenue. ¿Hay fechas mal vendidas?

4. Las reservas entran con una antelación. La antelación se calcula como: date_checkin - date_gen. El objetivo de esta pregunta es observar como afecta la antelación a la cancelación y confirmación de las reservas. ¿Cuándo suelen entrar las reservas? ¿el ratio de cancelación es constante para diferentes antelaciones? (Si es posible agrupa las antelaciones en intervalos: [0,3),[3,7),[7,30),[30,90),[90,120] días)

5. Elabora 2 análisis por tu parte:
    - Algunas sugerencias: Diferencias entre precio de venta de reservas canceladas y confirmadas, cómo afecta el número de noches al precio medio de la reserva, ratio de cancelación por origen (origen_id), evolución del precio de venta por mes, qué considerarías outliers...