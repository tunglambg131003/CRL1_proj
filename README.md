# CRL1\_proj

**Comparative study of machine learning & NLP models**

This repository contains experiments, notebooks, and resources for a coursework/research project that explores multiple approaches to text classification (classical ML, BiLSTM, and transformer-based models). It includes data, model implementations, training/evaluation notebooks, and a final project report.

> **Note:** This README was generated from the repository structure. For full experimental details, results, and discussion, see `CRL-1_Final_Report.pdf` in this repository.

---

## Repository structure

```
CRL1_proj/
├── albert/               # ALBERT fine-tuning experiments (notebooks / scripts)
├── bayes/                # Naive Bayes experiments
├── bilstm/               # BiLSTM model implementation and training notebooks
├── data/                 # Dataset(s) and preprocessing scripts
├── fine-tune-bert/       # BERT fine-tuning experiments
├── logistic/             # Logistic Regression experiments
├── random-forest/        # Random Forest experiments
├── roberta/              # RoBERTa fine-tuning experiments
├── svm/                  # SVM experiments
├── CRL-1_Final_Report.pdf # Final written report (results, analysis, discussion)
└── README.md             # <- you are here
```

> If a folder contains a notebook, open that notebook and run the cells; if it contains scripts, consult the top of the file for usage details.

---

## Quick overview

The project compares and analyses different approaches to text classification, including:

* Traditional machine learning methods: Logistic Regression, SVM, Naive Bayes, Random Forest
* Recurrent architectures: BiLSTM
* Transformer-based approaches: BERT, RoBERTa, ALBERT (fine-tuning)

Each subfolder contains code or notebooks to reproduce experiments, plus utilities for preprocessing, feature extraction, training and evaluation.

---

## How to run

1. Clone the repository:

```bash
git clone https://github.com/tunglambg131003/CRL1_proj.git
cd CRL1_proj
```

2. Inspect the `data/` folder and place your dataset(s) there. Many notebooks expect the preprocessed data (CSV/JSON) or scripts that produce them.

3. Reproduce experiments:

* For notebooks: launch Jupyter Lab / Notebook and run the relevant `.ipynb` file in each model folder.

```bash
jupyter lab
# then open e.g. fine-tune-bert/finetune_bert.ipynb
```

(Please check each folder for exact notebook/scriptnames and CLI arguments.)

---

## Reproducing results & evaluation

* Most experimental notebooks include training, validation, and evaluation cells. Run them end-to-end to reproduce metrics and plots.
* The final report `CRL-1_Final_Report.pdf` contains the full results, tables, and analysis — consult it for model comparisons and conclusions.

---

## Suggestions & next steps

* Add a `requirements.txt` or `environment.yml` with exact package versions to simplify reproduction.
* Include small example dataset or a `download_data.sh` script to fetch/prepare data automatically.
* Add a `scripts/` directory with standardized CLI entry points (`train.py`, `evaluate.py`) to make experiments easily repeatable.
* Add a `results/` folder to store model checkpoints and evaluation outputs.

---

## Contributing

Contributions are welcome. Suggested workflow:

1. Fork the repository
2. Create a feature branch
3. Add or update notebooks / scripts
4. Open a pull request describing your changes

---

## License
This repository contains coursework developed as part of a course at VinUniversity. The project is provided for educational and research purposes only.

---

## Contact
If you have any questions, please don’t hesitate to contact us at 

* Nguyen Tung Lam — 21lam.nt@vinuni.edu.vn

* Nguyen Nhat Minh — 21minh.nn2@vinuni.edu.vn

* Nguyen Mau Hoang Hiep — 21hiep.nmh@vinuni.edu.vn

