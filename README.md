# An Augmented Large Language Model for Patent Acceptance Prediction

This project was conducted by Anh Ta, Erin McGowan, and Maksat Kuanyshbay as a part of the curriculum for the Machine Learning (CSCI-GA.2565-001) course at the New York University Courant Institute of Mathematical Sciences.

## Files included in this repository:

- **[HUPD_metadata_preliminary_analysis.ipynb](https://github.com/egm68/ML-Final_Project/blob/main/HUPD_metadata_preliminary_analysis.ipynb):** This file contains the code that was used to conduct our preliminary analysis of the 25,000 patents we sampled from the larger HUPD dataset to determine if the “filing date,” “examiner art unit,” “ipc label”, “foreign,” “small entity indicator,” and “aia first to file” metadata variables were actually correlated with patent acceptance rate.

- **[BERT_model_benchmark.ipynb](https://github.com/egm68/ML-Final_Project/blob/main/BERT_model_benchmark.ipynb):** An implementation of [BERT](https://doi.org/10.48550/arxiv.1810.04805) fine-tuned on the [Harvard USPTO Patent Dataset](https://doi.org/10.48550/arxiv.2207.04043), which we used as a benchmark for our PatentLLM model. 

- **[PatentLLM.ipynb](https://github.com/egm68/ML-Final_Project/blob/main/PatentLLM.ipynb):** Our hierarchical transformer-based model for patent acceptance prediction, trained on a subset of the [Harvard USPTO Patent Dataset](https://doi.org/10.48550/arxiv.2207.04043). 

- **[PatentLLM_with_Metadata.ipynb](https://github.com/egm68/ML-Final_Project/blob/main/PatentLLM_with_Metadata.ipynb):** An augmented version of our hierarchical transformer-based model for patent acceptance prediction that incorporates metadat variables, trained on a subset of the [Harvard USPTO Patent Dataset](https://doi.org/10.48550/arxiv.2207.04043). 

## References for Code:
- [https://colab.research.google.com/drive/1wm8Z0ui8ZGSXoR50x52GvWMQkfSPPJ-T#scrollTo=SCFXYdbIXguc](https://colab.research.google.com/drive/1wm8Z0ui8ZGSXoR50x52GvWMQkfSPPJ-T#scrollTo=SCFXYdbIXguc)
- [https://colab.research.google.com/drive/1YRHK4HO8RktGzlYmGjBo056kzVD4_j9o#scrollTo=BJR6t_gCQe_x](https://colab.research.google.com/drive/1YRHK4HO8RktGzlYmGjBo056kzVD4_j9o#scrollTo=BJR6t_gCQe_x)
