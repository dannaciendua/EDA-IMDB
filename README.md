download data from https://www.kaggle.com/datasets/ashirwadsangwan/imdb-dataset 
name_basics = pd.read_csv("/Users/dannaciendua/Documents/CodeOp/archive/name.basics.tsv", delimiter="\t")
title_akas = pd.read_csv("/Users/dannaciendua/Documents/CodeOp/archive/title.akas.tsv", delimiter="\t")
title_basics = pd.read_csv("/Users/dannaciendua/Documents/CodeOp/archive/title.basics.tsv", delimiter="\t",low_memory=False)
