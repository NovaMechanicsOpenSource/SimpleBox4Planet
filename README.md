# SimpleBox4Planet

This **Excel-based tool** implements the **SimpleBox v4.04** multimedia fate model and includes a curated library of **3,993 PFAS substances** selectable directly within the workbook.

Developed by **NovaMechanics Ltd**, it simulates the environmental **fate, transport, and exposure** of chemicals under steady-state and quasi-dynamic conditions across key compartments:
- **Air (A)**
- **Freshwater (FW)**
- **Marine Water (MW)**
- **Soil (S)**
- **Sediment (SD)**

---

## 📅 Date of Creation

**30 September 2025**

---

## 💶 Funding

This work has received funding from the **European Union’s Horizon Europe research and innovation programme** under the **PROPLANET project**, Grant Agreement No. **101091842**.

---

## 🌐 Web Application

Access the online version of SimpleBox4Planet here:  
🔗 [https://www.enaloscloud.novamechanics.com/proplanet/simplebox4planet/](https://www.enaloscloud.novamechanics.com/proplanet/simplebox4planet/)

---

## 📚 Model References

The web tool runs the **SimpleBox version 4.04** model published on **05/04/2024**, based on the works below:

- Hollander, A.; Schoorl, M.; van de Meent, D. *SimpleBox 4.0: Improving the model while keeping it simple…*. **Chemosphere** 2016, 148, 99–107. [link](https://www.sciencedirect.com/science/article/abs/pii/S0045653516300066)
- Schoorl, M.; Hollander, A.; van de Meent, D. *SimpleBox 4.0. A multimedia mass balance model for evaluating the fate of chemical substances*. **RIVM Report** 2015. [link](https://www.rivm.nl/bibliotheek/rapporten/2015-0161.pdf)
- Den Hollander, H.; Van Eijkeren, J.; Van de Meent, D. *SimpleBox 3.0: multimedia mass balance model for evaluating the fate of chemicals in the environment*. **RIVM Report** 2004, 601200003. [link](https://www.rivm.nl/sites/default/files/2018-11/SimpleBox%203.0%20-%20Multimedia%20mass%20balance%20model%20for%20evaluating%20the%20fate%20of%20chemical%20in%20the%20environment.pdf)
- Brandes, L.; Den Hollander, H. *SimpleBox 2.0: a nested multimedia fate model for evaluating the environmental fate of chemicals*. 1996. [link](https://www.rivm.nl/bibliotheek/rapporten/719101029.pdf)
- Meent, D. *SimpleBox: a generic multimedia fate evaluation model*; National Institute of Public Health and Environmental Protection, 1993. [link](https://www.rivm.nl/bibliotheek/rapporten/672720001.pdf)

**Upstream repositories and archives:**
- GitHub repository: https://github.com/rivm-syso/SimpleBox/tree/xl_v4.0.4  
- Zenodo repository: https://zenodo.org/records/10934046

---

## 📥 Input Format

The Excel workbook (`SimpleBox4Planet_PFAS.xlsx`) expects the following user inputs on the **Input** sheet:

1. **Substance selection (PFAS):** choose one entry from the built-in list of **3,993 PFAS**.  
2. **Emission scenario:** specify emissions per compartment (e.g., air, freshwater, soil) in appropriate units (e.g., kg·day⁻¹).  
3. **Environmental settings:** provide or confirm scenario parameters (e.g., compartment volumes/areas, intermedia transfer rates, degradation half-lives, partitioning).  
4. **Run/Calculate:** update calculations to generate steady-state / quasi-dynamic **masses, concentrations, and inter-compartment fluxes**.

**Outputs** (on the **Results** sheet) typically include:  
- Predicted **concentrations** and **masses** per compartment  
- **Fluxes** between compartments  
- High-level indicators suitable for screening-level assessments

---

## 📁 Data Access

The spreadsheet is included in this repository:  
- **`SimpleBox4Planet_PFAS.xlsx`** – Excel model implementing SimpleBox v4.04 with **3,993 PFAS**.

A permanent archive (Zenodo) will be linked here once available:  
📌 **DOI:** *to be assigned upon deposit*

---

## 🧾 License

This repository is released under the **Apache License 2.0**.  
You can view the full license text here:  
🔗 [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

---

## 📣 Cite as

If you use **SimpleBox4Planet** in your work, please cite:

> Mintis, D. G.; Afantitis, A.; Melagraki, G.; Lynch, I.; Varsou, D.-D.; Kolokathis, P. D.; Tsoumanis, A.; Seif, J. P.  
> **SimpleBox4Planet: A web-enabled environmental fate model extended for PFAS assessment via the Enalos Cloud Platform**. *Preprint / Article in preparation*, 2025.

---

## 📬 Contact

For questions or feedback, please contact:  
📧 [info@novamechanics.com](mailto:info@novamechanics.com)
