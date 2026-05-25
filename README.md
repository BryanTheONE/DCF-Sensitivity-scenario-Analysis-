[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Sector: Aerospace / B2B & B2C Software](https://img.shields.io/badge/Sector-Aerospace%20%2F%20GPS%20Software-blue)](#)
[![Analysis Type: Corporate Finance / Valuation](https://img.shields.io/badge/Analysis-Corporate%20Finance%20%2F%20Valuation-darkgreen)](#)

# DCF-Sensitivity-scenario-Analysis: Integrated Financial Model & Intrinsic Valuation

## Executive Summary & Investment Thesis

Questo progetto presenta un modello finanziario integrato a **3 Statements (2020-2025)** e una valutazione **Discounted Cash Flow (DCF)** per **Aerospace Trajectory S.p.A**, azienda storicamente specializzata nella manifattura di componenti aerospaziali per stazioni orbitanti e navette shuttle, attualmente impegnata in una transizione strategica verso il settore del software ad alta scalabilità tramite il lancio di un'applicazione di navigazione GPS proprietaria per l'ottimizzazione del traffico veicolare.

L'analisi del **Base Case** evidenzia un forte sblocco di valore derivante dalla diversificazione digitale, ma fa emergere al contempo una temporanea tensione finanziaria legata all'ambiziosa pipeline di investimenti iniziali.

### Key Investment Insights:
**Leva Operativa e Scalabilità Software:** Il passaggio al modello software permette a Rendezvous di espandere il proprio Margine Lordo dal 72.3% (2020) fino al **75.6%** entro il 2025.La forte leva operativa si riflette sull'**EBITDA margin**, che accelera dal 20.5% iniziale al **33.4%** alla fine del periodo di forecast, portando l'EBITDA a quota **€2.67M**.
* **Analisi del Fabbisogno di Cassa (Cash Squeeze):** A causa dei massicci investimenti in CapEx e sviluppo software, l'azienda affronta una severa crisi di liquidità transitoria tra il 2021 e il 2024, con un deficit di cassa cumulato che tocca il picco negativo di **-€3.05M nel 2023**. Questo deficit evidenzia la necessità critica di un intervento straordinario sulla struttura del capitale (Aumento di capitale o finanziamento a lungo termine) prima del pieno ritorno all'autofinanziamento nel 2025 (+€670.47k).
* **Valutazione Intrinseca:** Il modello DCF (Unlevered Free Cash Flow) basato sul piano industriale stima un **Enterprise Value (EV) di €16.30M** e un **Equity Value di €16.25M**, confermando la profonda convenienza economica del progetto a fronte del superamento delle criticità di cassa operative.

---

## Financial Performance & Forecast (3-Statement Model)

Il modello prevede per lo Scenario Base una crescita sostenuta dei ricavi core pari al **+14.0% annuo** nel triennio 2021-2023, seguita da un fisiologico consolidamento nel 2024 (-1.0%) e da una ripresa al +8.0% nel 2025.

### Evoluzione dei Ricavi e del Margine Lordo
Le proiezioni catturano il progressivo efficientamento dei costi industriali (COGS) e la stabilità delle spese di struttura (SG&A), che beneficiano dell'economia di scala tipica dei prodotti digitali.

![Revenues vs Gross Profit](/images/lineplot_flussi_.png)

### Sintesi delle Proiezioni Finanziarie (€ Migliaia)
 60.00 € 	 64.80 € 	 69.98 € 	 75.58 € 	 79.36 € 	 83.33 € 

| Voce di Bilancio | 2020 (H) | 2021 (F) | 2022 (F) | 2023 (F) | 2024 (F) | 2025 (F) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Ricavi Core (Revenues)** | **5,000.00** | **5,700.00** | **6,498.00** | **7,407.72** | **7,333.64** | **7,920.33** |
| **Altri Ricavi (Other Revenues)** |**60.00** | **64.80** | **69.98** | **75.58** | **79.36** | **83.33** | 
| *Crescita YoY* | *—* | *+14.0%* | *+14.0%* | *+14.0%* | *-1.0%* | *+8.0%* |
| **Utile Lordo (Gross Margin)** | **3,660.00** | **4,196.80** | **4,827.50** | **5,568.77** | **5,555.91** | **6,053.72** |
| *Margine Lordo %* | *72.3%* | *72.8%* | *73.5%* | *74.4%* | *74.9%* | *75.6%* |
| **EBITDA** | **1,035.00** | **1,403.05** | **1,853.88** | **2,403.40** | **2,284.13** | **2,671.80** |
| *Margine EBITDA %* | *20.5%* | *24.3%* | *28.2%* | *32.1%* | *30.8%* | *33.4%* |
| **EBIT (Operating Income)** | **655.00** | **985.05** | **1,394.08** | **1,851.64** | **1,622.01** | **1,877.26** |
| **Tax Rate** | **229.90** | **340.12** | **495.55** | **652.32** | **582.16** | **679.16** |
| **Utile Netto (Net Income)** | **375.10** | **554.93** | **808.53** | **1,064.32** | **949.85** | **1,108.10** |
| *Utile Netto %* | *7.4%* | *9.6%* | *12.3%* | *14.2%* | *12.8%* | *13.8%* |

### Dinamica del Capitale Circolante Netto & TFR
Il capitale circolante è stato modellato sulla base delle indicazioni della traccia, riflettendo un incremento dei crediti e debiti commerciali proporzionale allo scale-up del business. Coerentemente con i vincoli del caso:
* Gli accantonamenti al **Fondo TFR** crescono del 5.0% annuo.
* Nel 2024 e 2025 vengono contabilizzate uscite finanziarie per **€30k/anno per liquidazioni TFR** effettive.
* Al 2023 viene assorbito un onere straordinario *una tantum* pari a **€45k**.

---

## DCF Valuation & Capital Structure

La valutazione intrinseca è stata sviluppata tramite la metodologia dei flussi di cassa scontati unlevered (**uFCFF**), isolando il valore operativo delle attività core dai componenti finanziari.

### Assunzioni sul Costo del Capitale (WACC)
* **Tasso di Sconto (WACC):** Posto al **7.36%** (Parametro stimato e ipotizzato in linea con i benchmark di mercato per finanziare la transizione tecnologica della società).
**Terminal Value (TV):** Calcolato all'anno 5 sulla base dei flussi standardizzati, pari a **€22,805.01**. Attualizzato al tasso WACC, il TV pesa per **€15,989.80** sul valore finale.

### Flussi di Cassa Scontati ed Enterprise Value
A causa della forte intensità di CapEx iniziale, i flussi dei primi due anni risultano negativi, per poi invertire bruscamente la tendenza una volta che l'applicazione entra a pieno regime commerciale:
* **NPV dei Flussi Espliciti (2021-2025):** €310.39 
* **NPV del Terminal Value:** €15,989.80 
* **Enterprise Value (EV):** **€16,300.19** 

![DCF Valuation vs Net PFN](/images/lineplot_ROIC_basecase.png)

### Dal Valore di Impresa all'Equity Value

| Voce di Valutazione | Valore (€ Migliaia) | Note / Dettagli |
| :--- | :---: | :--- |
| **Enterprise Value (EV)** | **16,300.19** | Valore generato dagli asset operativi e dal software |
| **Posizione Finanziaria Netta (PFN)** | **-(-50.00)** | Cassa Netta iniziale al 2020 (Debito €200k) - Liquidità €250k |
| **Equity Value (EqV)** | **16,350.19** | Valore di competenza degli Azionisti (EV - PFN)|

---

## Strategic & Managerial Recommendations

In base alle risposte del business case e all'andamento del **Scenario Base**, si delineano le seguenti raccomandazioni direzionali per il management:

1. **Approvazione dell'Investimento:** L'operazione è fortemente consigliata sotto il profilo economico. Il pivot strategico sul software incrementa significativamente la redditività aziendale e genera un Enterprise Value finale elevato.
2. **Mitigazione del Rischio Finanziario (Cash Squeeze):** Il principale fattore di rischio è il deficit di cassa operativo tra il 2021 e il 2024 (picco di -€3.05M). Il management deve coprire questo gap *prima* dell'inizio del piano per evitare l'insolvenza tecnica. 
3. **Strategia di Copertura e Capital Structure:**
   * **Opzione Equity:** Richiesta ai soci di un aumento di capitale pari ad almeno **€3.1M** per coprire interamente il picco del fabbisogno senza ricorrere a leva finanziaria.
   * **Opzione Debito (Consigliata):** Accensione di un finanziamento bancario a lungo termine con ammortamento a 10 anni e tasso da contrattare. La forte generazione di EBITDA a partire dal 2023 (€2.4M) garantisce un commisurato *Debt Service Coverage Ratio (DSCR)*, rendendo la struttura finanziaria solida e ottimizzando il costo del capitale.

![DCF Valuation vs Net PFN](/images/barplot_indici_reddittività_basecase.png)

![DCF Valuation vs Net PFN](/images/lineplot_indici_sostenibilità_basecase.png)
---

## Note Metodologiche e Limiti dello Studio (Project Scope)

**Assunzioni Parametriche:** Poiché la traccia non conteneva i dati di input di mercato per il calcolo analitico del CAPM (Beta, Market Risk Premium), i tassi per la storicizzazione del DCF sono stati assunti e simulati ex-novo, garantendo la totale flessibilità e dinamicità del modello tramite il foglio di *Sensitivity Analysis*.
* **Perimetro dell'Analisi:** Il presente repository copre esclusivamente la **Parte 1** della traccia (Modellizzazione a 3 Statements, DCF e Sensitivity). La **Parte 2** (relativa al confronto finanziario di capital budgeting tra i Progetti alternativi A e B tramite i criteri del VAN e del TIR) è esclusa dal perimetro per indisponibilità dei file sorgente storici.

---

## Repository Structure

```text
├── Rendezvous_Master_Model.xlsx     # Modello Finanziario Integrato (3 Statements + DCF + Sensitivity)
├── traccia.txt                      # Traccia e linee guida del caso di studio originario
├── 3_statement_model.xlsx           # Output dei prospetti previsionali (CE, SP, RF)
├── EV_EqV.xlsx                      # Calcoli uFCFF, attualizzazione WACC ed Equity Value
├── sensitivity_analysis.xlsx        # Matrice dinamica degli scenari (Base, Upside, Downside)
└── images/                          # Grafici a supporto inseriti nella documentazione Markdown
