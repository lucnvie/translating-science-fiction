# Translating science fiction in a CAT tool: machine translation and text segmentation 

## Intro
This is the GitHub repository which contains the analysis for the two studies which were part of the Translating Science Fiction paper. These studies examined the use of neural machine translation (NMT) as a source of suggestions for translating science fiction short stories in a commercial computer aided translation (CAT) tool, Trados Studio 2019.

The first study compares NMT post-editing with unaided translation in terms of the levels of effort required by the tasks, while the second examines two ways of presenting the texts for post-editing, namely by segmenting them into paragraphs or sentences. 

This analysis accompanies a publication, which you can read [here](link-here-when-ready).

## Team
Contributions are shown using [emojis](https://allcontributors.org/docs/en/emoji-key) from the [all-contributors guidelines](https://github.com/all-contributors/all-contributors).

[Lucas Nunes Viera](mailto:): 🔍🤔💻🖋💬🔣

[Michael Carl](mailto:): 🔣🤔🖋💬

[Roy Youdale](mailto:): 🤔🖋💬

[Xiaochun Zhang](mailto:): 🔍🤔🖋💬

[Natalie Thurlby](mailto:natalie.thurlby@bristol.ac.uk):🚧🚇💻🤔💬

This work was funded by the Creative Multilingualism Open World Research Initiative of the Arts and Humanities Research Council and by the Economic and Social Research Council (Grant ES/S014446/1).

## Reproducing this analysis

### Directory Structure
The data and analysis script which you will need to reproduce the analysis can be found in:
`data/CREATIVE.csv` - data for study 1.
`data/CREATIVE2.csv` - data for study 2.
`scripts/creative.rmd` - RMarkdown notebook for both analyses.

### On your machine
We have used [renv](https://rstudio.github.io/renv/articles/renv.html) to capture the R libraries that were used to run our analyses, in order to help you reproduce the same setup. If you download this repository, then opening the R project (`translating-science-fiction.Rproj`) will automatically activate `renv`. 

The `renv.lock` file is the only file needed to restore the libraries, but `.Rprofile` and `renv/activate.R` are used to automatically initialize renv to make the process more seamless.
<!--see discussion here: https://github.com/rstudio/renv/issues/74-->

### In the cloud using [Binder](https://mybinder.readthedocs.io/en/latest/)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NatalieThurlby/translating-science-fiction/master?urlpath=rstudio)

You can also click the binder badge above, to open RStudio on BinderHub in the cloud, where you can run the analysis.
