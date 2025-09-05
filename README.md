# Megaline

Este proyecto contiene datos y un cuaderno Jupyter para analizar el comportamiento de 500 clientes de **Megaline**, un operador ficticio de telefonía móvil que ofrece dos tarifas de prepago: **Surf** y **Ultimate**. El departamento comercial quiere saber cuál de estas tarifas genera más ingresos para optimizar el presupuesto de publicidad. Para ello se proporcionan registros de llamadas, mensajes y tráfico de internet junto con los planes contratados por cada usuario.

## Estructura del repositorio

- `megaline_calls.csv` — datos sobre la duración de las llamadas.
- `megaline_messages.csv` — registros de mensajes enviados.
- `megaline_internet.csv` — volumen de datos utilizados por sesión.
- `megaline_users.csv` — información básica de los usuarios y el plan que poseen.
- `megaline_plans.csv` — detalles de los planes **Surf** y **Ultimate**.
- `megaline_sprint_5.ipynb` — cuaderno con el análisis realizado.

## Objetivo

Analizar el comportamiento de los clientes y determinar qué tarifa de prepago genera más ingresos. El cuaderno incluye limpieza de datos, cálculo del ingreso mensual por usuario y comparaciones entre planes. También se realizan pruebas de significancia estadística para respaldar las conclusiones.

## Herramientas de análisis

- **Python 3** — lenguaje principal para la manipulación y análisis de datos.
- **pandas** — limpieza de datos, unión de tablas y cálculo de métricas como minutos, mensajes y tráfico por usuario.
- **numpy** — soporte para operaciones numéricas y vectorizadas.
- **matplotlib** y **seaborn** — visualización de distribuciones y tendencias de uso.
- **scipy** — pruebas estadísticas (por ejemplo, `ttest_ind` para comparar ingresos entre planes).
- **Jupyter Notebook** — entorno interactivo para ejecutar el análisis paso a paso.

## Requisitos

Instala las bibliotecas necesarias para ejecutar el cuaderno y reproducir los análisis:

```bash
pip install pandas numpy matplotlib seaborn scipy
```

## Uso

1. Abre el archivo `megaline_sprint_5.ipynb` en Jupyter Notebook o JupyterLab.
2. Ejecuta las celdas para reproducir el análisis y experimentar con los datos.

El repositorio no contiene código ejecutable adicional; los datos pueden usarse para experimentar con análisis propios.
