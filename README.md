# ENER958-ESBC: Operational research for urban solar development

Solar Academy, Université Savoie Mont Blanc. Course material, released session
by session.

Regional-scale performance modelling of photovoltaic systems: from hourly
weather data to the production of a whole region, built up from single systems
and compared with the production published by the grid operator.

## Sessions

| Session | Date | Content |
|---|---|---|
| 1 | Monday 19/10, 8h00 - 9h30 | Lecture: the modelling chain, weather data, plane-of-array irradiance. Notebook 1 |
| 2 | Tuesday 20/10, 13h15 - 14h45 | Cell temperature and DC power. One hour of one day. Notebook 2 |
| 3 | 21/10 (TP 1), 22/10 (TP 2) | Losses, inverter, performance metrics. Notebook 3 |
| 4 | 09/11 (TP 1), 10/11 (TP 2) | The regional fleet. Project launch. Notebook 4 |
| 5 | 24/11 (TP 2), 27/11 (TP 1) | Project work, oral presentations |

Material appears here as the course progresses.

## Notebooks

| Notebook | Open in Colab |
|---|---|
| 1. Python introduction and POA calculation | [python_intro_poa.ipynb](https://colab.research.google.com/github/Mohamed-ENNHIRI/ENER958/blob/main/notebooks/python_intro_poa.ipynb) |

Before running anything: **File, Save a copy in Drive**. Without a copy, your
work is lost when the tab closes.

## Data

`data/` holds the hourly weather of the course site, Savoie, 45.64° N, 5.92° E,
year 2023, from PVGIS SARAH3, and the solar position for the same hours. Time
stamps are in UTC.

## Acknowledgement

The structure of this course, its session format, its notebooks and its project
follow the course given by Alexandre Mathieu at the Solar Academy in 2024, "PV
failure detection based on operational time series". Physics and data: pvlib,
PVGIS SARAH3, ODRE, RTE eCO2mix, BDPV.
