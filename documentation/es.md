<!-- ELUCENIA technical documentation · fleischner-2017 · es · no clinical/professional/rights approval -->

# Fleischner 2017 (nódulo pulmonar sólido)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/fleischner-2017)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Diámetro medio del nódulo (el más sospechoso, si hay varios)

`tamanho`

mm · intervalo: 1–30

### Número de nódulos

`num`

- `u` — Único
- `m` — Múltiples

### Riesgo de cáncer de pulmón

`risco`

- `b` — Bajo
- `a` — Alto (tabaquismo, edad, exposición, antecedentes familiares, enfisema, lóbulo superior)

## Edición del método

Fleischner Society 2017: nódulos sólidos incidentales, diámetro medio redondeado; exclusiones preservadas

## Fórmula documentada

Diámetro medio = (eje mayor + eje menor) ÷ 2, redondeado al milímetro más próximo. Rangos: \< 6 mm (\< 100 mm³), 6 a 8 mm (100 a 250 mm³) y \> 8 mm (\> 250 mm³).

## Límites y población

Variante para nódulos pulmonares sólidos detectados incidentalmente en adultos de 35 años o más. Las recomendaciones Fleischner 2017 no se aplican al cribado del cáncer de pulmón, a personas inmunodeprimidas ni a pacientes con cáncer primario conocido. Los nódulos subsólidos o parcialmente sólidos requieren otro algoritmo. Si hay múltiples nódulos, el más sospechoso debe orientar la evaluación; no es necesariamente el de mayor tamaño. La estratificación del riesgo y la decisión de seguimiento dependen de la evaluación clínica y radiológica.

## Referencias

- [MacMahon H et al. Guidelines for management of incidental pulmonary nodules detected on CT images: from the Fleischner Society 2017. Radiology, 2017.](https://doi.org/10.1148/radiol.2017161659)

- [MacMahon et al. Radiology2017, DOI10.1148/radiol.2017161659](https://pubs.rsna.org/doi/full/10.1148/radiol.2017161659)

- [Original sixteen-page RSNA article, institutional copy at University of Wisconsin](https://wiki.radiology.wisc.edu/images/b/b9/Flesichner_Guidelines_2017.pdf)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Sin seguimiento rutinario

| Detalles del resultado | |
| --- | --- |
| Riesgo del paciente | Bajo |
| Diámetro medio redondeado | 4 mm |

No se aplica a menores de 35 años, pacientes con cáncer conocido, inmunodeprimidos o cribado de cáncer de pulmón (usar Lung-RADS).


### 2

TC en 6 a 12 meses y luego en 18 a 24 meses

| Detalles del resultado | |
| --- | --- |
| Riesgo del paciente | Alto |
| Diámetro medio redondeado | 6 mm |

No se aplica a menores de 35 años, pacientes con cáncer conocido, inmunodeprimidos o cribado de cáncer de pulmón (usar Lung-RADS).


### 3

TC en 3 a 6 meses; luego, considerar TC en 18 a 24 meses

| Detalles del resultado | |
| --- | --- |
| Riesgo del paciente | Bajo |
| Diámetro medio redondeado | 7 mm |

No se aplica a menores de 35 años, pacientes con cáncer conocido, inmunodeprimidos o cribado de cáncer de pulmón (usar Lung-RADS).


### 4

Considerar TC en 3 meses, PET-TC o muestra de tejido

| Detalles del resultado | |
| --- | --- |
| Riesgo del paciente | Bajo |
| Diámetro medio redondeado | 10 mm |

No se aplica a menores de 35 años, pacientes con cáncer conocido, inmunodeprimidos o cribado de cáncer de pulmón (usar Lung-RADS).

