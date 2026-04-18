# StarsBehindTheApps-
Descubriendo los secretos de las apps de Google Play Store
¿qué es lo que hace que una aplicación sea bien calificada y valorada por el público en general?, ¿será por la categoría, el tamaño, el precio?

## INPUT

`apps.csv`: contiene todos los detalles de las aplicaciones en Google Play. Hay 13 características que describen una aplicación determinada.
`user_reviews.csv`: contiene 100 reseñas para cada aplicación, reviews. El texto de cada reseña se ha procesado previamente y se le atribuyen tres características nuevas: Sentimiento (positivo, negativo o neutral), Polaridad del sentimiento y Subjetividad del sentimiento.

## DATA CLEANING 
Las cuatro variables con las que trabajaremos con más frecuencia de ahora en adelante son Installs, Size, Rating y Price. La función info() nos dice que las columnas Installs y Price son de tipo object, no son de tipo int o float como esperaríamos. Esto se debe a que la columna contiene algunos caracteres más que solo [0,9] dígitos. Idealmente, queremos que estas columnas fueran puramente numéricas

Por lo tanto, ahora necesitamos limpiar nuestros datos. Específicamente, los caracteres especiales , y + que se encuentran en la columna Installs y $ que esta en la columna Price.

## EXPLORACION DE APPS

on más de mil millones de usuarios activos en 190 países de todo el mundo, Google Play sigue siendo una importante plataforma de distribución para crear una audiencia global. Para que las empresas muestren sus aplicaciones a los usuarios, es importante hacerlas más rápida y fácilmente visibles en Google Play. Para mejorar la experiencia de búsqueda general, Google ha introducido el concepto de agrupar aplicaciones en categorías.

Esto nos lleva a las siguientes preguntas:

¿Qué categoría tiene la mayor participación de aplicaciones (activas) en el mercado?
¿Alguna categoría específica domina el mercado?
¿Qué categorías tienen la menor cantidad de aplicaciones?

## DISTRIBUCIÓN DE RAITINGS
Después de analizar la participación de mercado para cada categoría de las aplicaciones, veamos cómo se posicionan de acuerdo a las calificaciones (en una escala del 1 al 5) las cuales afectan la imagen de la marca general de la empresa. Las calificaciones son un indicador clave de rendimiento de una aplicación.

## SIZE AND PRICE

* ¿El tamaño de una aplicación afecta su calificación?
* ¿Los usuarios realmente se preocupan por las aplicaciones pesadas del sistema o prefieren las aplicaciones ligeras?
* ¿El precio de una aplicación afecta su calificación?
* ¿Los usuarios siempre prefieren las aplicaciones gratuitas a las de paga?

## RELACIÓN CATEGORÍA Y PRECIO
Los costos de las aplicaciones se basan en gran medida en las características, la complejidad y la plataforma. Hay muchos factores a considerar al seleccionar la estrategia de precios adecuada para las aplicaciones moviles. Es importante considerar la disposición de su cliente a pagar por la aplicación. 
¿Cómo se supone que las empresas y los desarrolladores cubran sus cuotas de fin de mes? ¿Qué estrategias de monetización pueden utilizar las empresas para maximizar las ganancias? 

## ANALISIS DE SENTIMIENTO
¿cómo se sienten las personas acerca de su producto, marca o servicio?

# Conclusión
> Cuando se hace un compartivo entre apps de paga y gratuitas existe la tendencia por las aplicaciones de paga, las cuales tienen comentarios más positivos en comparación con las gratuitas.