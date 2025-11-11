<h1 align="center">Text Re-identification Evaluation with Retrieval-Augmented Generation</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Windows%2011-Working-ok" alt="Working on Windows 11"/>
</p>

This repository contains the code and data for the **text re-identification risk assessment** method based on Retrieval-Augmented Generation (RAG) presented in *B. Manzanares-Salor, D. Sánchez, Text Re-identification Evaluation with Retrieval-Augmented Generation, The Web Conference 2026, Submitted*.

Experimental data was extracted from the [bootstrapping-anonymization](https://github.com/anthipapa/bootstrapping-anonymization) repository, corresponding to the publication [A. Papadopoulou, P. Lison, L. Øvrelid, I. Pilán, Bootstrapping Text Anonymization Models with Distant Supervision, Proceedings of the Thirteenth Language Resources and Evaluation Conference, pages 4477–4487, Marseille, France, 2022](https://aclanthology.org/2022.lrec-1.476/). The exact data files utilized in the experiments, including both the corpus and anonymization methods, are located in the [data](data) folder.

The project’s implementation is provided in the interactive notebook [`rag_risk.ipynb`](rag_risk.ipynb), and the corresponding output data is available in [`results_wiki553.csv`](results_wiki553). 

The Python 3.11 environment specifications are included in [`environment.yml`](environment.yml) for Conda and [`requirements.txt`](requirements.txt) for Pip.