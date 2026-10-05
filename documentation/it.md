<!-- ELUCENIA technical documentation · fleischner-2017 · it · no clinical/professional/rights approval -->

# Fleischner 2017 (nodulo polmonare solido)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/fleischner-2017)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Diametro medio del nodulo (il più sospetto, se sono presenti più noduli)

`tamanho`

mm · intervallo: 1–30

### Numero di noduli

`num`

- `u` — Singolo
- `m` — Multipli

### Rischio di cancro del polmone

`risco`

- `b` — Basso
- `a` — Alto (fumo, età, esposizione, familiarità, enfisema, lobo superiore)

## Edizione del metodo

Fleischner Society 2017: noduli solidi incidentali, diametro medio arrotondato; esclusioni mantenute

## Formula documentata

Diametro medio = (asse maggiore + asse minore) ÷ 2, arrotondato al millimetro più vicino. Fasce: \< 6 mm (\< 100 mm³), 6 a 8 mm (100 a 250 mm³) e \> 8 mm (\> 250 mm³).

## Limiti e popolazione

Variante per noduli polmonari solidi rilevati incidentalmente negli adulti di 35 anni o più. Le raccomandazioni Fleischner 2017 non si applicano allo screening del carcinoma polmonare, alle persone immunocompromesse né ai pazienti con una neoplasia primitiva nota. I noduli subsolidi o parzialmente solidi richiedono un altro algoritmo. In presenza di noduli multipli, il nodulo più sospetto deve guidare la valutazione; non è necessariamente il più grande. La stratificazione del rischio e la decisione sul follow-up dipendono dalla valutazione clinica e radiologica.

## Riferimenti

- [MacMahon H et al. Guidelines for management of incidental pulmonary nodules detected on CT images: from the Fleischner Society 2017. Radiology, 2017.](https://doi.org/10.1148/radiol.2017161659)

- [MacMahon et al. Radiology2017, DOI10.1148/radiol.2017161659](https://pubs.rsna.org/doi/full/10.1148/radiol.2017161659)

- [Original sixteen-page RSNA article, institutional copy at University of Wisconsin](https://wiki.radiology.wisc.edu/images/b/b9/Flesichner_Guidelines_2017.pdf)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
