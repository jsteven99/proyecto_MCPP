# Proyectos de inversión en Cali
#### Johan Steven Caicedo Rodríguez

### Descripción y motivación
Los proyectos de inversión gubernamentales son clave para el desarrollo económico y social de las regiones. En Colombia, el Departamento Nacional de Planeación (DNP), es la institución encargada de apoyar la planeación de proyectos orientados a la definición de políticas públicas y planes de desarrollo realizados por los distintos niveles de gobierno y entidades de orden nacional, departamental y municipal. En ese sentido, el DNP juega un papel crucial para la implementación de políticas publicas en las entidades territoriales. 

Sin embargo, la implementación efectiva de políticas públicas es heterogéneas en el orden nacional. Posiblemente algunas ciudades como Bogotá o Medellín cuentan con la capacidad técnica para proponer y ejecutar programas de políticas públicas en sus territorios; sin embargo, no es el caso de muchos municipios del país. De acuerdo con lo anterior, este trabajo busca analizar los proyectos de inversión realizados en la ciudad de Santiago de Cali, en los últimos 15 años con el objetivo de encontrar insights acerca de la efectividad de estos proyectos y alcance durante durante y luego de su ejecución.

Para el desarrollo del trabajo se utilizará como principal fuente de información las bases de datos del DNP que relacionan información de la ejecución de proyectos de inversión en Cali y su área metropolitana. A partir de esta base de datos se realizarán estadísticas descriptivas que permitan dar cuenta de la ejecución, evolución, objetivos, plazos, costos y los sectores económicos en los que interviene dichos planes en la ciudad.

### Metodología

1. La fuente de datos a utilizar son proporcionadas por el DNP disponible en la página gubernamental de [datos abiertos](https://www.datos.gov.co/):
- https://www.datos.gov.co/Econom-a-y-Finanzas/DNP-proyectos_datos_basicos/cf9k-55fw
- https://www.datos.gov.co/Econom-a-y-Finanzas/DNP-SeguimientoProyecto/7mxf-bp6x
- https://www.datos.gov.co/Econom-a-y-Finanzas/DNP-EjecucionFinancieraProy/v4ap-cvae
 
 2. Organización y limpieza de los datos
 - Por medio de la librería pandas se limpian cada base de datos.
 - Posteriormente se construye una base de datos unificada que agrega la información de las tres bases de datos descargadas.
 - Haciendo uso de otras librerías (seaborn, matplotlyb) se construyen estadísticas descriptivas.

### Hallazgos

![verbos_freq](https://user-images.githubusercontent.com/67245592/203525654-da3a36fa-7253-43e8-8a3e-950fc0895700.png)

Nube con las palabras más frecuentes en los objetivos de los proyectos de inversión

![nube de palabras](https://user-images.githubusercontent.com/67245592/203527140-6e088df7-3933-41e8-9e72-9002e278d1c6.png)


![inversion_estado](https://user-images.githubusercontent.com/67245592/203528540-3484a38a-bd20-464f-af17-64ec74931bb1.png)


![porcentaje_estado](https://user-images.githubusercontent.com/67245592/203539563-9515fd78-2865-41a7-b9aa-81670b42378a.png)


![distribucion_sector](https://user-images.githubusercontent.com/67245592/203530497-51c69dda-85b9-4d99-b35e-efe9592b4a27.png)


![distribucion_sector2](https://user-images.githubusercontent.com/67245592/203539664-1e9855c8-d8d6-4c07-8113-86797c0e5c2e.png)


![media_inver_sector](https://user-images.githubusercontent.com/67245592/203539756-e14d7896-2ceb-4dab-8217-a43cf41bef97.png)


![cantidad_sector](https://user-images.githubusercontent.com/67245592/203539801-52176f76-447e-4ab6-aae8-4c86201a7d8a.png)


![Barras_prom_cant](https://user-images.githubusercontent.com/67245592/203539850-f0cbdbf3-5def-4bb4-b610-1d09dd9b825e.png)


![swarmplot_estado](https://user-images.githubusercontent.com/67245592/203533561-0348e0e4-5105-4a63-9b8c-cc5f595d5013.png)


![proy_terminados](https://user-images.githubusercontent.com/67245592/203540052-61ee22e1-c590-41c0-a82c-baaaf2e9c5dc.png)


![fuentes_finan](https://user-images.githubusercontent.com/67245592/203540092-503e534f-7681-4757-b00b-22c469baa9ac.png)


![treemap](https://user-images.githubusercontent.com/67245592/203536137-3a91e597-4c60-4ccc-832b-31cfdffd1c57.png)
