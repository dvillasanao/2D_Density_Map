
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Mapas de Calor de Homicidios Dolosos en México

Este repositorio contiene scripts y recursos para generar mapas de calor
de homicidios dolosos en México utilizando datos proporcionados por el
**Secretariado Ejecutivo del Sistema Nacional de Seguridad Pública
(SESNSP)**. Los mapas se visualizan mediante **mapas de calor 2D** y
**mapas cloropléticos**, que permiten analizar la distribución espacial
de los homicidios a nivel municipal y estatal.

**Ventajas de los mapas de calor**

1.  **Visualización continua de la densidad**
    - **Mapas de contornos de densidad** muestran una representación
      continua de la densidad de un fenómeno en el espacio, utilizando
      **líneas de contorno** o colores para mostrar diferentes niveles
      de concentración o densidad de eventos.
    - Son más adecuados cuando los datos no están distribuidos
      uniformemente y se quiere mostrar la **variabilidad espacial**.
    - **Ventaja**: Proporciona una visión más precisa de cómo se
      distribuyen los eventos a lo largo de un área geográfica.
2.  **Mejor manejo de la dispersión de datos**
    - Los **mapas de contornos** pueden capturar patrones complejos de
      dispersión, especialmente en situaciones en las que los eventos
      (por ejemplo, homicidios, accidentes) están **muy concentrados en
      áreas pequeñas**.
    - Mientras que un **mapa cloroplético** puede simplificar la
      representación al asignar un valor promedio a cada área
      administrativa (como un municipio), los **mapas de densidad 2D**
      muestran la **concentración real** de eventos en ubicaciones
      exactas.
3.  **Detección de “clusters” o patrones espaciales**
    - Los **contornos de densidad** permiten identificar **agrupamientos
      de eventos** (clusters), lo que ayuda a localizar **áreas de alta
      concentración** de homicidios o cualquier otro fenómeno que se
      esté analizando.
    - **Ventaja**: Si hay concentración de eventos en ciertas zonas,
      como zonas urbanas específicas, el mapa de contornos lo destacará
      de manera clara, mientras que un mapa cloroplético podría suavizar
      o perder esa información.
4.  **Mejor para representar datos dispersos**
    - Si los eventos se distribuyen de manera **no uniforme** y no
      siguen límites geográficos predefinidos, los **mapas de
      contornos** son más eficaces. Un **mapa cloroplético** puede ser
      menos útil en estos casos, ya que se basa en áreas de agregación
      (como municipios o distritos), que no reflejan necesariamente la
      distribución precisa de los eventos.
5.  **Visualización intuitiva de la variabilidad**
    - Los **colores y contornos** en un mapa de densidad 2D pueden ser
      más intuitivos y fáciles de interpretar cuando se quiere mostrar
      cómo **varía la densidad** del fenómeno en diferentes partes de un
      área.
    - Además, los contornos y colores permiten que el observador
      **identifique gradientes de densidad** de manera visual sin tener
      que lidiar con las posibles limitaciones de las clasificaciones de
      un mapa cloroplético.

## Objetivo

El objetivo de este proyecto es proporcionar una visualización clara y
detallada de la **distribución geográfica de los homicidios dolosos** en
México, utilizando datos del SESNSP. A través de mapas de calor, es
posible identificar las regiones con mayor incidencia de homicidios,
ayudando a la toma de decisiones en políticas públicas y estrategias de
seguridad.

## Requisitos

Para ejecutar los scripts en este repositorio, asegúrarse de tener
instalados los siguientes paquetes en **R**:

``` r
install.packages(c("tidyverse", "sf", "ggplot2", "ggspatial", "dplyr", "stringr"))
```

## Resultados

**Enlace**:
<https://dvillasanao.github.io/2D_Density_Map/Output/2d-density-map.html>

## Código de Conducta

Por favor, revisa nuestro [Código de Conducta](CODE_OF_CONDUCT.md) antes
de contribuir.

## Licencia

Este trabajo de Diana Villasana Ocampo está bajo una
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">
Licencia Creative Commons Atribución 4.0 Internacional.</a>.
