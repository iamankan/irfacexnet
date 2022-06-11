# irfacexnet

Publication: https://www.nature.com/articles/s41598-021-99998-z

Data: https://drive.google.com/file/d/15XoRfZMgOekrsfuZwRIncVwxB25caa2F/view?usp=sharing

The real image data was image. So, the data is converted into a csv of pixel values, in grayscale.

The data is fed into a customized CNN, as mentioned in the paper.

The CNN is trained with varying learning rate in a *cosine annealing* manner.

The models are saved at 50 or 100 intervals.

Each of the models (5 or 10) is then ensembled and ran for the final result.