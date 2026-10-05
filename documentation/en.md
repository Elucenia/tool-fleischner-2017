<!-- ELUCENIA technical documentation · fleischner-2017 · en · no clinical/professional/rights approval -->

# Fleischner 2017 (solid pulmonary nodule)

[conditions, sources and permissions](https://elucenia.org/en/tools/fleischner-2017)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Mean nodule diameter (most suspicious nodule if there are several)

`tamanho`

mm · range: 1–30

### Number of nodules

`num`

- `u` — Single
- `m` — Multiple

### Lung cancer risk

`risco`

- `b` — Low
- `a` — High (smoking, age, exposure, family history, emphysema, upper lobe)

## Method edition

Fleischner Society 2017: incidental solid nodules, rounded mean diameter; exclusions preserved

## Documented formula

Mean diameter = (longest axis + shortest axis) ÷ 2, rounded to the nearest millimetre. Ranges: \< 6 mm (\< 100 mm³), 6 to 8 mm (100 to 250 mm³) and \> 8 mm (\> 250 mm³).

## Limits and population

Variant for incidentally detected solid pulmonary nodules in adults aged 35 years or older. The Fleischner 2017 recommendations do not apply to lung cancer screening, immunocompromised people or patients with known primary cancer. Subsolid or part-solid nodules require a different algorithm. For multiple nodules, the most suspicious nodule should guide assessment; it is not necessarily the largest. Risk stratification and the follow-up decision depend on clinical and radiological assessment.

## References

- [MacMahon H et al. Guidelines for management of incidental pulmonary nodules detected on CT images: from the Fleischner Society 2017. Radiology, 2017.](https://doi.org/10.1148/radiol.2017161659)

- [MacMahon et al. Radiology2017, DOI10.1148/radiol.2017161659](https://pubs.rsna.org/doi/full/10.1148/radiol.2017161659)

- [Original sixteen-page RSNA article, institutional copy at University of Wisconsin](https://wiki.radiology.wisc.edu/images/b/b9/Flesichner_Guidelines_2017.pdf)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
