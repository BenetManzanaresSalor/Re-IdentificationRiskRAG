<h1 align="center">Text Re-identification Evaluation with Retrieval-Augmented Generation</h1>

This repository contains the code and data for the **text re-identification risk assessment** method based on Retrieval-Augmented Generation (RAG) and record linkage presented in *B. Manzanares-Salor, D. Sánchez, Text Re-identification Evaluation with Retrieval-Augmented Generation, Submitted*.

* **Affiliation/Authors**: Developed at the [CRISES Research Group](https://crises-deim.urv.cat/), [Universitat Rovira i Virgili](https://www.urv.cat/en/) (URV), Tarragona, Catalonia.
* **Contact information**: Benet Manzanares-Salor (benet.manzanares@urv.cat)
* **Acknowledgement**:  We acknowledge support from the Government of Catalonia (Acadèmia d'Excel·lència Prize to D. Sánchez), MCIN/AEI under grant PID2024-157271NB-I00 "CLEARING-IT" and the European Commission (project
HORIZON-101292277 "SoBigDataIP"). B. Manzanares-Salor is also supported by the Spanish Government under an FPU grant (ref. FPU23/01785).
* **Citation**: Submitted.

Experimental data was extracted from the [bootstrapping-anonymization](https://github.com/anthipapa/bootstrapping-anonymization) repository, corresponding to the publication [A. Papadopoulou, P. Lison, L. Øvrelid, I. Pilán, Bootstrapping Text Anonymization Models with Distant Supervision, Proceedings of the Thirteenth Language Resources and Evaluation Conference, pages 4477–4487, Marseille, France, 2022](https://aclanthology.org/2022.lrec-1.476/). The exact data files utilized in the experiments, including both the corpus and anonymization methods, are located in the [data](data) folder.

The project’s implementation is provided in the interactive notebook [`rag_linkage.ipynb`](rag_linkage.ipynb), and the corresponding output data is available in [`results_wiki553.csv`](results_wiki553.csv).

The Python 3.11 environment specifications are included in [`environment.yml`](environment.yml) for Conda and [`requirements.txt`](requirements.txt) for Pip.