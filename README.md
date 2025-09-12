<div align="center">
   <h1>Lake Surface Water Evaporation Modeling with Remote Sensing and Hybrid Deep Learning</h1>
</div>


This repository supports a research study on estimating lake surface water evaporation using satellite-derived water quality (WQ) parameters and in-situ meteorological (MG) data. We develop Bayesian Optimization (BO)-tuned deep learning architectures (BO-LSTM, BO-GRU) and compare them with their non-optimized counterparts (LSTM, GRU) and a physically based Penman-FAO formulation (baseline).

> Status: Active research codebase (manuscript in preparation). Structure and APIs may change.

---

## Key Contributions

- Focus on open surface water evaporation.
- Integrates remote sensing–derived WQ parameters (CHL, CDOM, TSM, temperature) with MG drivers.
- Hybrid deep learning: BO-LSTM and BO-GRU (Bayesian hyperparameter optimization).
- Benchmark against Penman-FAO physical model.
- Feature attribution using SHAP for interpretability.
- Demonstrates viability of WQ-only predictors where MG data are sparse.

---

## Installation

```bash
python -m venv .venv
source .venv/bin/activate  # or .venv\Scripts\activate on Windows
pip install -r requirements.txt
```

---

## License

MIT License (see [LICENSE](https://github.com/farzadasgari/evap?tab=MIT-1-ov-file)).

---

## Disclaimer

This repository is a research vehicle. Model outputs should not be treated as operational hydrological guidance without independent verification.

---

## Contact
For any inquiries, please contact:
- std_farzad.asgari@khu.ac.ir
- khufarzadasgari@gmail.com

---

## Links

### Farzad Asgari
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://farzadasgari.ir/)

[![Google Scholar Badge](https://img.shields.io/badge/Google%20Scholar-4285F4?logo=googlescholar&logoColor=fff&style=for-the-badge)](https://scholar.google.com/citations?user=Rhue_kkAAAAJ&hl=en)

[![ResearchGate Badge](https://img.shields.io/badge/ResearchGate-0CB?logo=researchgate&logoColor=fff&style=for-the-badge)](https://www.researchgate.net/profile/Farzad-Asgari)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/farzad-asgari-5a90942b2/)


### Seyed Hossein Mohajeri
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://khu.ac.ir/cv/1139/Seyed-Hossein-Mohajeri)

[![Google Scholar Badge](https://img.shields.io/badge/Google%20Scholar-4285F4?logo=googlescholar&logoColor=fff&style=for-the-badge)](https://scholar.google.com/citations?user=E8PFUBEAAAAJ&hl=en)

[![ResearchGate Badge](https://img.shields.io/badge/ResearchGate-0CB?logo=researchgate&logoColor=fff&style=for-the-badge)](https://www.researchgate.net/profile/Seyed-Mohajeri-2)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](
https://ir.linkedin.com/in/hossein-mohajeri)
