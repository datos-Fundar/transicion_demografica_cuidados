# La pirámide pierde su forma, ¿Estamos preparados?

<!-- CAMBIAR "https://place-hold.it/1920x1080" POR EL LINK A LA IMAGEN CORRESPONDIENTE -->
[![La pirámide pierde su forma, ¿estamos preparados?](https://place-hold.it/1920x1080)](https://fund.ar)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%20NC%20SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
<!-- [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1234.svg)](https://zenodo.org/doi/10.5281/zenodo.11186044) -->

Describir aca lo que hay en el repositorio y citar al docu principal cuando esté

#### Cita sugerida:

```r
Puglia, M., Bendersky, A., de la Fuente, X., Santellán, C., Nadur, Y. (2025). La pirámide pierde su forma, ¿Estamos preparados? Una herramienta para mejorar la planificación en la provisión de cuidados en la última milla de la transición demográfica. Fundar.

Bibtex:

@report{XXXXXXXXXXXXXXX, 
  author = {Puglia, M., Bendersky, A., de la Fuente, X., Santellán, C., Nadur, Y.}, 
  title = {La pirámide pierde su forma, ¿Estamos preparados?}, 
  year = {2025}, 
  institution = {Fundar}, 
  type = {Document} 
}
               
```

> [!NOTE]
> Información importante o útil.

> [!TIP]
> Algún consejo útil a la hora de utilizar este contenido.

> [!IMPORTANT]
> Información clave para usar este repositorio.

> [!WARNING]
> Información urgente para evitar problemas.

> [!CAUTION]
> Potenciales riesgos.

## Ejemplo de código en `R`

```r
datos <- tibble(
  "iso" = c("ARG", "FRA"),
  "2006" = c(2,1),
  "2010" = c(2,1),
  "2014" = c(2,1),
  "2018" = c(2,2),
  "2022" = c(3,2)
)

datos %>% 
  pivot_longer(cols = -iso,
               values_to = "copas", names_to = "anio")
               
```

---
<div>&nbsp;</div>
<div>&nbsp;</div>
<div>
  &nbsp;
  <a href="https://fund.ar">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/datos-Fundar/fundartools/assets/86327859/6ef27bf9-141f-4537-9d78-e16b80196959">
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/datos-Fundar/fundartools/assets/86327859/aa8e7c72-4fad-403a-a8b9-739724b4c533">
    <img src="fund.ar"></img>
  </picture>
</a>
</div>
