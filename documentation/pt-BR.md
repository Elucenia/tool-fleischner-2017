<!-- ELUCENIA technical documentation · fleischner-2017 · pt-BR · no clinical/professional/rights approval -->

# Fleischner 2017 (nódulo pulmonar sólido)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/fleischner-2017)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Diâmetro médio do nódulo (mais suspeito, se múltiplos)

`tamanho`

mm · intervalo: 1–30

### Número de nódulos

`num`

- `u` — Único
- `m` — Múltiplos

### Risco de câncer de pulmão

`risco`

- `b` — Baixo
- `a` — Alto (tabagismo, idade, exposição, história familiar, enfisema, lobo superior)

## Edição do método

Fleischner Society 2017:nódulos sólidos incidentais, diâmetromédio arredondado; exclusões preservadas

## Fórmula documentada

Diâmetro médio = (maior eixo + menor eixo) ÷ 2, arredondado para o milímetro mais próximo. Faixas: \< 6 mm (\< 100 mm³), 6 a 8 mm (100 a 250 mm³) e \> 8 mm (\> 250 mm³).

## Limites e população

Variante para nódulos pulmonares sólidos incidentais em adultos de 35 anos ou mais. As recomendações Fleischner2017 não se aplicam ao rastreamento de câncer pulmonar, a pessoas imunocomprometidas nem a pacientes com câncer primário conhecido. Nódulos subsólidos ou parcialmente sólidos exigem outro algoritmo. Em nódulos múltiplos, o nódulo mais suspeito deve orientar a avaliação; ele não é necessariamente o maior. A estratificação de risco e a decisão de seguimento dependem da avaliação clínica e radiológica.

## Referências

- [MacMahon H et al. Guidelines for management of incidental pulmonary nodules detected on CT images: from the Fleischner Society 2017. Radiology, 2017.](https://doi.org/10.1148/radiol.2017161659)

- [MacMahon et al. Radiology2017, DOI10.1148/radiol.2017161659](https://pubs.rsna.org/doi/full/10.1148/radiol.2017161659)

- [Original sixteen-page RSNA article, institutional copy at University of Wisconsin](https://wiki.radiology.wisc.edu/images/b/b9/Flesichner_Guidelines_2017.pdf)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
