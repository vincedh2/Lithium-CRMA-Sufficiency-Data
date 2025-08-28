# Supplementary Data – Lithium Value Chain

This repository provides the supplementary dataset accompanying the academic work
**“Can European strategic autonomy be achieved without sufficiency? Modelling the implications of the Critical Raw Materials Act on the lithium value chain.”**

The data is designed for transparency and reproducibility of the modelling exercises presented in the paper. It can be used to parameterise the TIAM-IFPEN model or for related analyses of the lithium supply chain.

---

## File Structure

### `Supplementary_Data_LithiumValueChain.xlsx`

This Excel file contains three sheets:

1. **`Lithium parametrisation`**
   - **Content**: Techno-economic parameters of lithium mining and processing technologies.
   - **Columns**:
     - *Technology*: Description of the process (e.g., integrated lithium chemical production).
     - *Parameter*: Type of assumption (CAPEX, OPEX, efficiency, etc.).
     - *Unit*: Measurement units (e.g., `bnUSD2022/(ktLi/year)`).
     - *Year*: Reference year of the parameter.
     - *Regions*: Numerical values for each TIAM-IFPEN region (e.g., Africa, China, Western Europe).
   - **Use**: Input data for cost and efficiency assumptions in the model.

2. **`Lithium production cap vintages`**
   - **Content**: Historical and projected installed production capacities of lithium processing technologies by region and installation year.
   - **Columns**:
     - *Technology*: Production route (e.g., lithium chemical integrated production from salar brines).
     - *Parameter*: Always “Capacity installation.”
     - *Unit*: Installed capacity (`ktLi/year`).
     - *Year of installation (vintage)*: Commissioning year of production assets.
     - *Regions*: Regional capacity values.
   - **Use**: Sets vintaged lithium production by region and period.

3. **`Lithium trade costs`**
   - **Content**: Transport and trade costs of lithium commodities between exporting and importing regions.
   - **Columns**:
     - *Commodity*: Type of lithium product (e.g., lithium carbonate, lithium hydroxide).
     - *Exporting region* and *Importing region*: Regional trade flow.
     - *Parameter*: Cost type (currently “Transportation cost”).
     - *Unit*: Cost unit (`bnUSD2007/ktLi`).
     - *Values*: Bilateral trade costs by region pairs.
   - **Use**: Provides trade cost assumptions for modelling interregional lithium flows.

---

## Notes

- All monetary values are expressed in **constant USD** of the year indicated (2022 for parametrisation, 2007 for trade costs).
- Regional definitions follow the **16-region aggregation** of TIAM-IFPEN (see Appendix of the paper).
- These datasets are **inputs** to the scenarios described in the manuscript (S1–S4 and sensitivities). They should be read in conjunction with the methodological section of the article.

---

## How to Cite

If you use this dataset, please cite as:

**APA citation**  
Bucciarelli, P., & D’Herbemont, V. (2025). *Supplementary dataset for: Can European strategic autonomy be achieved without sufficiency? Modelling the implications of the Critical Raw Materials Act on the lithium value chain.* Zenodo. https://doi.org/10.5281/zenodo.16982528

**BibTeX citation**
```bibtex
@dataset{bucciarelli_dherbemont_2025,
  author       = {Bucciarelli, Pauline and D'Herbemont, Vincent},
  title        = {Supplementary dataset for: Can European strategic autonomy be achieved without sufficiency? Modelling the implications of the Critical Raw Materials Act on the lithium value chain},
  year         = {2025},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.16982529},
  url          = {https://doi.org/10.5281/zenodo.16982528} 
}

---

## License

This dataset is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to:
- **Share** — copy and redistribute the material in any medium or format  
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially  

Under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.  

Full license text: [https://creativecommons.org/licenses/by/4.0/legalcode](https://creativecommons.org/licenses/by/4.0/legalcode)
