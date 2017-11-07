# MidtermBonusTree

Visualización en arboles para VA Uniandes

¿Cuál ha sido el comportamiento del transporte aéreo de pasajeros en Colombia en 2017?

Visualización usando árboles

De acuerdo a las cifras presentadas por la Aeronáutica Civil, la dinámica del sector aéreo en Colombia ha presentado para el año 2017 un crecimiento constante en el mercado del transporte. De acuerdo con la entidad, ha crecido cinco veces más que el terrestre.

Y es que de acuerdo con el informe, sólo en el primer semestre se movilizaron 17 millones 660 mil usuarios en 2017, representando un crecimiento del 3.2% a comparación del año anterior. En el mercado aéreo internacional, el número de pasajeros movilizados tuvo un incremento en 298 mil pasajeros.

Para el despliegue de las siguientes visualizaciones, fue necesario cargar los datasets disponibles en el sitio de Aerocivil
(http://www.aerocivil.gov.co/atencion/estadisticas-de-las-actividades-aeronauticas/bases-de-datos) en una base de datos Postgres, con el fin de agregar los datos. Estos datasets sirvieron como fuente para las visualizaciones

Hallazgos

    De acuerdo al agrupamiento realizado se encontró que definitivamente los aeropuertos de Bogotá (Aeropuerto Internacional el Dorado) y el aeropuerto José María Córdova de Rionegro, Antioquia, son los aeropuertos con más cantidad de vuelos en cuanto a destino internacionales se refiere. A nivel nacional, estos mismos aeropuertos, más Villavicencio, lideraron las cifras.

    En cuanto al análisis a partir de la cantidad de pasajeros transportados en destinos internacionales cuyo pais de origen es Colombia, se encontró que el aeropuerto de Bogotá (Aeropuerto Internacional el Dorado) es definitivamente el puerto aéreo con más cantidad de pasajeros transportados hacia el exterior. A diferencia del análisis por cantidad de vuelos, se observa que hay destinos que, a psar de no liderar la cantidad de vuelos, se suman a la visualización de mayor cantidad de pasajeros transportados (Buenos Aires, por ejemplo).

    Para destinos se observa que Bogotá es el aeropuerto donde más afluencia de pasajeros llegan desde el exterior. Esto nos conduce a las siguientes preguntas:

            ¿Es Bogotá el destino turístico preferido de los extranjeros?
            ¿Acaso el aeropuerto de la ciudad capital es el que reune las mejores condiciones para que las aerolineas a nivel mundial lo escojan como destino preferido para susu itinerarios hacia Colombia?
            A partir de las cifras visualizadas, se podría inferir que: ¿Las capitales turísticas del país (Cartagena, San andrés Isla, Medellín, Santa Marta, etc.) están perdiendo competitividad en el sector turístico versus sus pares latinoaméricanos por adolecer de una infraestructura aeroportuaria más robusta?

    Si el análisis de los destinos se hace por cantidad de vuelos, los destinos se observa que Miami, New York, Madrid y Lima lideran la lista en cuanto a cantidad de vuelos. Desde Sao Paulo se observa que Colombia es un destino frecuente, tal vez puede ser por aspectos inherentes a turismo-negocios, o tal vez que Colombia sea utilizado como escala para otros destinos.

    En cuanto a vuelos nacionales - domésticos, por cantidasd de vuelos, la ruta Villavicencio-Puerto Carreño es protagonista frecuente de las listas. Tal vez es utilizado como puente a los Llanos orientales, o tal vez es "jalonado" por la industria petrolera, con amplia frecuencia en el sector. Sin embargo, si el análisis se hace por cantidad de pasajeros transportados, observamos que las rutas más sobresalientes en este ítem son aquellas que salen de Bogotá y se dirigen hacia ciudades turísticas por excelencia, como San Andrés, Cali, Medellín y Cartagena
    
Los tipo de gráficos son una adaptación de ejemplos de Mike Bostock's.

Licence: Released under the GNU General Public License, version 3.
