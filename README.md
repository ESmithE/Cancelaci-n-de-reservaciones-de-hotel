# Cancelacion_de_reservaciones_de_hotel

## Objetivo:

Predecir si una reserva será cancelada o no basada en datos históricos y otros factores relevantes.

## Fuente de datos

La información oficial provista por https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2020/2020-02-11/hotels.csv

## Métodos
- Análisis Del Problema
- ETL 
- Análisis Exploratorio De Datos
- Análisis de penetración
- Generación De Insights
- Tabla de reporteo

## Tech Stack
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- plotnine
- Scikit-learn
- Tableau
- GitHub

## Tools

| VSCODE  | [![My Skills](https://img.icons8.com/?size=48&id=9OGIyU8hrxW5&format=png)](https://skillicons.dev)  | 
| :------------ |:---------------:| 
| TABLEAU |[![My Skills](https://img.icons8.com/?size=48&id=9Kvi1p1F0tUo&format=png)](https://skillicons.dev) | 
| GITHUB | [![My Skills](https://skillicons.dev/icons?i=git,github)](https://skillicons.dev)


## Explora
- [Notebook](https://deepnote.com/workspace/esmithe-6179-00a5df71-fb48-44a8-ba43-4410de40e4ac/project/MODELO-RESERVACIONES-CANCELADAS-5902584a-5bd2-4fde-b55c-e3c4d8034576/notebook/Notebook%201-a523de00f8c04b85853da74e2a26e00f)

- [Descarga Código](https://deepnote.com/workspace/esmithe-6179-00a5df71-fb48-44a8-ba43-4410de40e4ac/project/MODELO-RESERVACIONES-CANCELADAS-5902584a-5bd2-4fde-b55c-e3c4d8034576/notebook/Notebook%201-a523de00f8c04b85853da74e2a26e00f)

## Análisis

Las cancelaciones de reservas representan un desafío significativo para los hoteles, afectando tanto sus ingresos como su capacidad para planificar operaciones. Comprender la pérdida monetaria asociada a estas cancelaciones es crucial para enfocar recursos, minimizar el impacto financiero y optimizar la gestión del negocio. Los siguientes puntos aclaran mejor el problema:

- La cancelación implica que la habitación reservada no generará los ingresos esperados, especialmente si se realiza con poca antelación, reduciendo las posibilidades de volver a ocupar la habitación.
- La habitación cancelada podría haber sido ocupada por otro cliente, lo que es particularmente perjudicial durante temporadas altas o eventos especiales, cuando la demanda es alta.
- Gestionar cancelaciones requiere recursos adicionales, como tiempo del personal y sistemas de procesamiento de reservas y reembolsos.
- Las cancelaciones frecuentes dificultan la planificación de la ocupación y afectan las estrategias de precios y optimización de ingresos.
- Políticas de cancelación poco flexibles o una gestión ineficiente de las cancelaciones pueden dañar la reputación del hotel y disminuir la satisfacción del cliente.

## Solución

Para minimiazar las perdidas causadas por cancelaciones, se crea un modelo de Machine Learning que prediga si un cliente cancele la reservació. Este solución permite a los hoteles identificar clientes con alto riesgo de cancelación y tomar medidas, por ejemplo: Un plan flexible para poder cambiar la fecha de la reservación en lugar de cancelar. 



## Vistaso rápido a los resultados

> Dashboard
![](https://github.com/ESmithE/Deserci-n_Laboral/blob/master/Fuga_de_empleados.png)

> Riesgo de abandono por puesto
![](https://github.com/ESmithE/Deserci-n_Laboral/blob/master/Riesgo_abandono_por_puesto.png)

Nota: Los puestos con más riesgo de abandono laboral son "Sales Representative"

> Riesgo de abandono por edad 
![](https://github.com/ESmithE/Deserci-n_Laboral/blob/master/Riesgo_abandono_por_edad.png)

Nota: Empleados que abandonan la empresa son personas entre los 20 a 22 años.

> Árbol de decisiones

![](https://github.com/ESmithE/Deserci-n_Laboral/blob/master/Arbol%20de%20perfil%20de%20empleado.png)

Nota: El árbol de decisiones señala que los empleados con mayor probabilidad a abandonar la empresa son: aquellas personas que hacen horas extras, con posiciones bajas dentro de la empresa, son solteros y la distacia del trabajo a su casa es mas de 6 kilometros



