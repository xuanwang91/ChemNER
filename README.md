# ChemNER: Fine-Grained Chemistry Named Entity Recognition with Ontology-Guided Distant Supervision

## Code
The code for distant supervision generation is in corpus.ipynb. The next step is to train a sequence labeling model (Bi-LSTM, RoBERTa, ChemBERTa, ...) based on distant supervision.

## Data
The data is in the folder /data. The training data is too big to be uploaded and can be found here: [CHEM_train.json](https://virginiatech-my.sharepoint.com/personal/xuanw_vt_edu/_layouts/15/download.aspx?UniqueId=eff0d607e51041b78813c8d3b06683a3&e=jNf2Hi). The human-annotated test data is in /data/CHEM_test_annotations.jsonl.

## Citation
```
@inproceedings{wang2021chemner,
  title={ChemNER: Fine-grained chemistry named entity recognition with ontology-guided distant supervision},
  author={Wang, Xuan and Hu, Vivian and Song, Xiangchen and Garg, Shweta and Xiao, Jinfeng and Han, Jiawei},
  booktitle={Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing},
  year={2021}
}
```
