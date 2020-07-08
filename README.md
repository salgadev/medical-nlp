# medical-nlp
Dataset compiled for Natural Language Processing using a corpus of medical transcriptions and custom-generated clinical stop words and vocabulary.

# Usage
Clone or download files for use in medical text Natural Language Processing (NLP) experiments.

# data

- `mtsamples.csv`. Compiled from Kaggle's medical transcriptions dataset by [Tara Boyle](https://github.com/terrah27), scraped from [Transcribed Medical Transcription Sample Reports and Examples](https://www.mtsamples.com/). See [Kaggle repository](https://www.kaggle.com/tboyle10/medicaltranscriptions#mtsamples.csv).
- `clinical-stopwords.txt`. Compiled from [Dr. Kavita Ganesan](https://github.com/kavgan) [clinical-concepts](https://github.com/kavgan/clinical-concepts) repository. See the [Discovering Related Clinical Concepts Using Large Amounts of Clinical Notes
](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5015701/) paper.
- `vocab.txt`. Generated vocabulary text files for Natural Language Processing (NLP) using the [Systematized Nomenclature of Medicine International (SNMI) data](https://bioportal.bioontology.org/ontologies/SNMI). See how to [Generate your own vocab file](https://github.com/socd06/snmi_vocab/blob/master/notebooks/snmi_vocab.ipynb).
- [`X.csv`](https://github.com/socd06/medical-nlp/blob/master/data/X.csv). Fully processed dataset obtained from running the [Data Modelling](https://github.com/socd06/private_nlp/blob/master/notebooks/medical-text-data-modelling.ipynb) notebook. Simplified dataset to 4 classes.
- [`classes.txt`](https://github.com/socd06/medical-nlp/blob/master/data/classes.txt). Text file describing the dataset's classes: `Surgery`, `Medical Records`, `Internal Medicine` and `Other`
- [`train.csv`](https://github.com/socd06/medical-nlp/blob/master/data/train.csv). Training data subset. Contains 90% of the `X.csv` processed file.
- [`test.csv`](https://github.com/socd06/medical-nlp/blob/master/data/test.csv). Test data subset. Contains 10% of the `X.csv` processed file.


# License
[GNU GENERAL PUBLIC LICENSE VERSION 3](https://github.com/socd06/medical-nlp/blob/master/LICENSE)
