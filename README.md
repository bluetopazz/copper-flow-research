# Copper Flow Research

The public research archive for the **Copper Flow Atlas**, a Ronnie's Lab instrument. The atlas maps where the world's copper goes between mine and wire, built from reconciled and official customs data, with a traceable working behind every number.

- **Atlas:** [ronnieslab.systems/atlas](https://ronnieslab.systems/atlas)
- **Methods note:** [`output/pdf/copper-flow-atlas-methods.pdf`](output/pdf/copper-flow-atlas-methods.pdf) (source: [`paper/copper-flow-atlas-methods.md`](paper/copper-flow-atlas-methods.md))

| | |
|---|---|
| **Question** | Where does the world's copper physically go between mine and wire, and what changed in 2025–26? |
| **Claim** | Reconciled and official customs data can map cross-border copper by stage, 2015 to the latest month, with every number traceable to its source, method and corrections. |
| **Evidence** | China's 2023 concentrate imports come out at 27.8 Mt gross, within 1% of China's customs total of 27.54 Mt. Chile's declared shipment grades showed the value-based method overstated Chilean concentrate copper by about 10%, and the method was corrected. |
| **Limitation** | Concentrate and scrap copper content are estimated. 2025–26 figures rest on partial reporting. Routes are simulated. |

## Contents

| Path | What it is |
|---|---|
| `paper/` | Methods note, Markdown |
| `output/pdf/` | Methods note, PDF |
| `evidence/world_trade_by_stage.csv` | World cross-border copper by stage, 2015–2026, kt Cu and $M (public build) |
| `evidence/checks.csv` | Cross-checks against independent totals and declared grades |
| `evidence/sources.csv` | Every source, its licence, and whether the public atlas uses it |
| `figures/` | Figures used in the note |

## Boundary

This is a code-free archive. The pipeline and the app are a private workbench (`copper-flow-atlas`); private research layers are not part of the public record. The public atlas and this archive use only redistributable sources. Figures that depend on UN Comtrade or Peru's SUNAT appear only as aggregates in the checks, and the public atlas replaces those estimates with a production-scaled fallback.

## Citing

Ronnie's Lab (2026). *Copper Flow Atlas: measuring where the world's copper goes.* Methods note. https://github.com/bluetopazz/copper-flow-research

Please credit the underlying sources as listed in `evidence/sources.csv`, in particular CEPII BACI, Eurostat, the U.S. Census Bureau, USGS, the World Bank, Chile's Servicio Nacional de Aduanas (ODC-BY), and Jasansky et al. (2023).

## Licence

The methods note, tables and figures in this repository are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). See `LICENSE`. The underlying source data keep their own licences, listed in `evidence/sources.csv`, and should be credited when reused.

Research only, not financial advice.
