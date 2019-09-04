Implementation of the method from [Story Cloze Ending Selection Baselines and Data Examination](https://arxiv.org/pdf/1703.04330.pdf) using hand-designed features based on word vectors to address the [Story Cloze Test](http://www.coli.uni-saarland.de/~mroth/LSDSem/pdfs/LSDSem06.pdf).

Before running the code, download the [pre-trained word2vector model](https://s3.amazonaws.com/dl4j-distribution/GoogleNews-vectors-negative300.bin.gz) into to the directory _data_.

In order to run the part using the skip-thouths model, the [pre-trained model](http://download.tensorflow.org/models/skip_thoughts_bi_2017_02_16.tar.gz) has to be downloaded to the directory _data/skipThoughts/bi_
