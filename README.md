# 4EU+ Interdisciplinary Drug Design Project

An experimental GenAI-based amino acid drug design study against SARS-CoV-2 nsp13 helicase.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Colab](https://img.shields.io/badge/Google%20Colab-F37626?style=for-the-badge&logo=google&logoColor=white)
![AlphaFold](https://img.shields.io/badge/AlphaFold2-1E4D8B?style=for-the-badge&logo=google&logoColor=white)
![ProtGPT2](https://img.shields.io/badge/ProtGPT2-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Biopython](https://img.shields.io/badge/Biopython-3CAE63?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-3c4549?style=for-the-badge&logo=gnubash&logoColor=white)


**Team Members**:
- [Younginn Park](https://github.com/young-sudo)
- [Mateusz Chojnacki](https://github.com/M-Chojnacki6)
- [Łukasz Milewski](https://github.com/lukaszmilewski)
- Hubert Wąsiewicz

An international team-based initiative organised by five 4EU+ member universities (Heidelberg, Milan, Paris, Prague, Warsaw) as part of the 4EU+ joint educational offer during the academic year 2023/2024.

![Meet-EU 2023](https://cu-bioinformatics.github.io/meet-eu-2023/assets/img/4eu.png)

>**NOTE:**: This is a curated extract of the original [4EU+ project repository](https://github.com/cu-bioinformatics/meet-eu-2023-projects), focusing solely on the work of team **Warsaw3**.

# Methods

<p align=center>
    <img src="https://raw.githubusercontent.com/young-sudo/med-gen/main/img/nsp13_pockets.png" alt="nsp13">
</p>

The SARS-CoV-2 Non-structural protein 13 ([NSP13](https://www.nature.com/articles/s41467-021-25166-6)) is chosen as a viable therapeutic target candidate.

<p align=center>
    <img src="https://raw.githubusercontent.com/young-sudo/med-gen/main/img/pipeline.png" alt="pipeline">
</p>

Experimental methodology bases on Low Data generation of amino-acid-based drug candidates using ProtGPT2, a Large Language Model trained on amino acid sequences, fine-tuned on known amino-acid based inhibitors of the enzyme. The generated sequences were then evaluated on basic metrics that would be expected from a viable drug in terms of ADMET and the Alphafold-Multimer docking simulations were conducted on those that fulfilled favorable conditions.

<p align=center>
    <img src="https://raw.githubusercontent.com/young-sudo/med-gen/main/img/protgpt2_histograms.png" alt="histograms">
</p>

Additionally, CABS-dock and HPepDock were used to verify docking results from AlphaFold-Multimer.

# Reports

>For more details on methods and results refer to the documentation in [`reports/`](https://github.com/young-sudo/med-gen/tree/f1d27e8c3de2309fa58262932ed43b1fcef90a98/reports) folder.

<p align=center>
    <img src="https://raw.githubusercontent.com/young-sudo/med-gen/main/img/report_abstract.png" alt="histograms">
</p>

# References

Ferruz, N., Schmidt, S. & Höcker, B. ProtGPT2 is a deep unsupervised language model for protein design. Nat Commun 13, 4348 (2022). [https://doi.org/10.1038/s41467-022-32007-7](https://doi.org/10.1038/s41467-022-32007-7)

Jumper, J., Evans, R., Pritzel, A. et al. Highly accurate protein structure prediction with AlphaFold. Nature 596, 583–589 (2021). [https://doi.org/10.1038/s41586-021-03819-2](https://doi.org/10.1038/s41586-021-03819-2)

Kurcinski, M., Jamroz, M., Blaszczyk, M., Kolinski, A., & Kmiecik, S. (2015). CABS-dock web server for the flexible docking of peptides to proteins without prior knowledge of the binding site. Nucleic acids research, 43(W1), W419–W424. [https://doi.org/10.1093/nar/gkv456](https://doi.org/10.1093/nar/gkv456)

Zhou, P., Jin, B., Li, H., & Huang, S. Y. (2018). HPEPDOCK: a web server for blind peptide-protein docking based on a hierarchical algorithm. Nucleic acids research, 46(W1), W443–W450. [https://doi.org/10.1093/nar/gky357](https://doi.org/10.1093/nar/gky357)
