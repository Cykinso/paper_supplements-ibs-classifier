# IBSclassifier
## Supplementary document for: "Usefulness of machine learning-based gut microbiome analysis for identifying patients with irritable bowel syndrome""

The document is the supplement and companion to the "Usefulness of machine learning-based gut microbiome analysis for identifying patients with irritable bowel syndrome." original research article.

This supplementary document was made to be reproducible. 

It is made using Python and report was automatically generated using jupyternotebook.

All source code will be packaged and then available on our github space for any people who wanted to reproduce the analysis and figures.

Sequences reads denoizing, quality checking, OTU clustering was made using the [QIIME pipeline](http://www.nature.com/articles/nmeth.f.303).

kinso_disease_classify_IBS_LassoRandomForest.ipynb is the code for figure 4 in the paper.
Dependent packages are given in the method in the paper.

## Usage

### Install
Prepare docker images.
```
docker-compose pull
```

### Launch and execute a notebook.
Then, launch the jupyter notebook.
```
docker-compose up
```

After that, you can access the notebook from WEB browser; http://localhost:8888 .


### To stop the containers.
```
docker-compose stop
```
