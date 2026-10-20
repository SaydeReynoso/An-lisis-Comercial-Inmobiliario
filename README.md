# Análisis Comercial Inmobiliario

Dashboard en Power BI y resumen ejecutivo en Jupyter para evaluar el desempeño comercial de una empresa inmobiliaria (2023–2024): crecimiento, rentabilidad y comportamiento de clientes.

## Problema
El sector inmobiliario necesita entender su desempeño comercial para tomar decisiones estratégicas basadas en datos: qué propiedades, canales y clientes generan más ingreso.

## Datos
- `hecho_ventas_propiedades`: transacciones de venta (precio, cliente, propiedad, canal y fecha).
- `dim_clientes`: información y segmentación de clientes.
- `dim_propiedades`: características de las propiedades (tipo, tamaño, ubicación).
- `dim_fecha`: tabla calendario creada como parte del modelado.

## Metodología
Modelo de datos con una tabla de hechos y tres dimensiones, medidas de ingreso, comisión y crecimiento año contra año, y análisis de recompra y cohortes de clientes.

## Herramientas
Power BI · Jupyter Notebook

## Métricas principales
| Ingreso total | Ventas | Ticket promedio | Comisión total | Crecimiento YoY |
|---|---|---|---|---|
| $6,012,502,170 | 8,500 | $707,353 | $200,627,166 | 11.14% |

## Hallazgos
- **Casa** lidera en ingreso total (37%, $2,240 M), seguida de Comercial y Departamento. **Departamento** concentra el mayor número de ventas (5,105) y **Comercial** tiene el ticket promedio más alto ($1,797,098).
- El canal **Corredor** concentra el **73%** del ingreso total frente al canal Directo.
- El segmento **Primera vez** aporta el **63%** del ingreso, seguido de Inversionista y Alto patrimonio.
- El **77.13%** de los clientes realizó más de una compra.
- Las cohortes de marzo y abril de 2023 muestran la mayor recompra e ingreso en el tiempo.

## Recomendaciones
- Priorizar la comercialización de Casa por su aporte al ingreso, y evaluar Comercial por su ticket promedio alto.
- Fortalecer el canal Corredor, por ejemplo con incentivos para los corredores de alto desempeño.
- Diseñar estrategias de fidelización para el segmento Primera vez, para convertirlos en compradores recurrentes o inversionistas.
- Replicar las tácticas de adquisición de las cohortes de marzo y abril de 2023.

## Archivos
- `S11 Estudiante_Proyecto_InmobiliarioGrupoAndes.ipynb`: notebook con el resumen ejecutivo.
