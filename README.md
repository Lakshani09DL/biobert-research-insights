# biobert-research-insights- Fine-tuning on PubMed 20k RCT Dataset

This repository contains the dataset and training notebook for fine-tuning **BioBERT** on the **PubMed 20k RCT** dataset to classify sentences from biomedical abstracts into five categories:

- BACKGROUND  
- OBJECTIVE  
- METHODS  
- RESULTS  
- CONCLUSIONS  

## Contents

- `Dataset Files`
- `train_biobert_pubmed.ipynb` — Jupyter notebook for data preprocessing and model fine-tuning.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Lakshani09DL/biobert-research-insights.git
   cd biobert-research-insights

   ```
2.Open and run the training notebook in Jupyter or VSCode.

3. The notebook contains step-by-step code to preprocess data, fine-tune BioBERT, and evaluate performance.

## 🔗 Model on Hugging Face Hub
You can directly use or explore the model here:  
👉 [SubhaL/biobert-research-insights](https://huggingface.co/SubhaL/biobert-research-insights)

## 🧪 Evaluation Metrics

- **Accuracy**: 0.8663
- **Precision**: 0.8667
- **Recall**: 0.8663
- **F1-Score**: 0.8662

Detailed classification report:

| Label       | Precision | Recall | F1-Score | Support |
|-------------|-----------|--------|----------|---------|
| BACKGROUND  | 0.6854    | 0.7468 | 0.7148   | 3621    |
| OBJECTIVE   | 0.6555    | 0.5945 | 0.6235   | 2333    |
| METHODS     | 0.9304    | 0.9444 | 0.9374   | 9897    |
| RESULTS     | 0.9262    | 0.9118 | 0.9189   | 9713    |
| CONCLUSIONS | 0.8538    | 0.8342 | 0.8439   | 4571    |

- **Macro Avg**: Precision 0.8103, Recall 0.8063, F1-score 0.8077  
- **Weighted Avg**: Precision 0.8667, Recall 0.8663, F1-score 0.8662


## References


- [PubMed 20k RCT dataset](https://github.com/Franck-Dernoncourt/pubmed-rct/tree/master/PubMed_20k_RCT) 
- Lee, Jinhyuk, et al. "BioBERT: a pre-trained biomedical language representation model for biomedical text mining." *Bioinformatics* 36.4 (2020): 1234-1240.  
  [Paper link](https://academic.oup.com/bioinformatics/article/36/4/1234/5566506)
