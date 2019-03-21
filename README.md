# AMPLab-Project

The following code comprehends the two implementations of "Towards Turkish-Makam Similarity Using Symbolic Data", Gor, S. & Gusó, E., UPF-SMC, AMPLab 2019 Project. It computes similarity measures between Makams using the SymbTr corpus.

The notebook in makam_lstm compute euclidean distances between Makams using trained LSTM. "makam_similarity" notebook extract features from scores and compute the similarity measures. 

## Requeriments

### Packages

The needed packages for running the whole code are:
* numpy
* matplotlib
* pytorch
* pandas

If needed, open a terminal and run:
```
pip install numpy matplotlib pytorch pandas
```

## Dataset

The used dataset is SymbTr corpus and it must be located inside AMPLab-Project folder. 

### SymbTr 
( ```M. Kemal Karaosmanoğlu. A Turkish makam music symbolic database for music information retrieval: SymbTr. In Proceedings of 13th International Society for Music Information Retrieval Conference (ISMIR), pages 223–228, 2012.```)
