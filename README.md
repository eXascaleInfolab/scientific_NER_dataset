Scientific Named Entity Recognition (NER) Dataset
-------------------------------------------------

*Judged dataset for NER in scientific documents*

Dataset contains the folowing files:

* `SIGIR_judged.csv` - Judged n-grams for SIGIR 2012 Collection, in the format `n-gram,paper title,IS_VALID`, where `IS_VALID` can be either 0 or 1
* `Physics_judged.csv` - Judged n-grams for Physics (arxiv HEP-PH) Collection, in the format `n-gram,arxiv ID,IS_VALID`, where `IS_VALID` can be either 0 or 1
* `maxent_last20.csv` - Entities extracted from SIGIR collection by Maximum Entropy classifier, without judgements. Judgements are location in `SIGIR_judged.csv`.


