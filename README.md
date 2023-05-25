# EDA-Colonized-Countries

![Colonias](img/colonias.jpg)

# Objetivo principal

En el siguiente proyecto se busca visualizar y analizar el impacto de la colonización en los paises que alguna vez fueron colonizados. Para ello utilizaremos Tableau de cara a la visualización. 

# Proceso del proyecto a nivel general

El proceso se divide en los siguientes pasos:

- Realización de una pequeña ETL, en este caso con índices por pais (IDH, GINI, PIBpc..) 🔍

- Creación de la historia en tableau con sus respectivos dashboards 🌍

- Análisis de los datos una vez visualizados 📈

# Visualización

A pesar de que ciertos datos podrían expresarse mediante gráficas, para este trabajo he decidido visualizar todo a través de los propios mapas. A fin de cuentas, considero que es mucho más claro de este modo, siendo más sencillo visualizar tanto la visión general por pais colonizador y la visión particular por pais colonizado. 

La estructura de la historia en este caso se dividió entre:

- Establecer un contraste entre el HDI de todos los paises y que paises fueron alguna vez colonizados

- Análisis de todos los paises en general según las métricas obtenidas en la ETL

- Y luego por partes centrarnos en los tres paises colonizadores de mayor relevancia (España, Francia y Reino Unido) y en su métrica más representativa

![historia](img/dashboard.jpg)

# Análisis

En la historia[^1] para empezar se puede observar que los paises con un HDI (índice de desarrollo humano) más bajo son en su mayoría aquellos que fueron previamente colonizados por otros paises. Cabe destacar que Estados Unidos, Canadá, Australia y Nueva Zelanda (todos ellos colonizados por Reino Unido) son los únicos paises verdaderamente prósperos en lo referente al HDI y al PIB de entre los colonizados según los datos. 

También podemos apreciar una diferencia entre aquellos colonizados por España, con un Gini bajo en todos pero no muy bajo en ninguno. Por otro lado aquellos colonizados por Reino Unido, con un Gini en su mayoría inferior aunque más variable pero PIBs según el pais muy elevados para la media entre los colonizados. Y por último los colonizados en Francia que presentaban niveles bajos en todas las categorías salvo en el propio Gini, donde presentan unas métricas algo por encima del resto de paises colonizados. 

# Conclusiones

El resultado del análisis deja entrever que aquellos paises que fueron colonizados son a día de hoy paises en vías de desarrollo, con economías más precarias y una desigualdad entre sus habitantes superior a los del resto.

[^1]: https://public.tableau.com/app/profile/nacho.romero/viz/EDAPAISESCOLONIZADOS/Historia1?publish=yes