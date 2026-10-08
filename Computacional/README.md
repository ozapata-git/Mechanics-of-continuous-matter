# Estrategias computacionales para Medios Continuos

Este conjunto reúne tres notebooks educativos para acercarse a estrategias
computacionales aplicadas a problemas de medios continuos. Constituye una
línea paralela de formación: cada notebook parte de un fenómeno sencillo y
muestra cómo pasar de su descripción física a una representación numérica y a
la interpretación del resultado.

## Contenido

| Notebook | Estrategia | Fenómeno |
|---|---|---|
| `diferencias_finitas_flujo_inducido_por_presion.ipynb` | Diferencias finitas | Flujo inducido por presión |
| `sph_colapso_de_nubes.ipynb` | Smoothed Particle Hydrodynamics (SPH) | Colapso e interacción de nubes |
| `equilibrio_elastico_solidos_en_reposo.ipynb` | Equilibrio elástico | Sólidos en reposo |

## Ruta sugerida

Se recomienda leer primero **Diferencias finitas** y después **SPH**. El
notebook de **Equilibrio elástico** es complementario y puede abordarse de
forma independiente.

## Prerrequisitos

- conceptos básicos de Medios Continuos, derivadas y arreglos de NumPy;
- para **Diferencias finitas** y **SPH**: nociones básicas de hidrodinámica,
  como densidad, presión, velocidad, viscosidad y conservación de masa y de
  cantidad de movimiento;
- para **Equilibrio elástico**: desplazamiento, deformación, esfuerzo, ley de
  Hooke y equilibrio estático.

## Archivos y dependencias

Los tres notebooks están en la raíz de esta carpeta. Las imágenes locales están
en `source/` y se cargan mediante rutas relativas. Las URL externas permanecen
como enlaces dentro de los notebooks.

Se requiere un entorno de Jupyter con `numpy` y `matplotlib`; algunas
visualizaciones interactivas utilizan `ipywidgets`.
