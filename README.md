# CWL Novice tutorial template

CWL Template for the [CWL Novice tutorial](https://carpentries-incubator.github.io/cwl-novice-tutorial/index.html).

This template contains some of the scripts used in the tutorial. 
It also contains instructions for installing the bio-cwl-tools library.

Before following the tutorial you will need to install [VSCode](https://code.visualstudio.com/), [docker](https://www.docker.com/), and [cwltool](https://github.com/common-workflow-language/cwltool). You will also need a working python installation, and either `pip` or `conda`. See the course [Setup page](https://carpentries-incubator.github.io/cwl-novice-tutorial/setup.html) for more details.

 
#### Setup Instructions

This template should be used to create a new git repository. The steps to do this are:

1. Click the `Use this template` button, and create a new repository on github as you would usually
   * Before the next step you can, if you wish, copy this repository to a different git service (such as [gitlab](https://gitlab.com/)).  
2. Clone the repository locally, using `git clone --recursive [template address]` (the `[template address]` can be got from the `Code` button at the top of the page)
   * Using the `--recursive` flag will automatically load the bio-cwl-tools library for you, using `git submodules`.

#### CWLTool and Graphviz Install Instructions

`cwltool` and `graphviz` can be installed using the included conda environment file:
```
conda env create --file cwltutorial.yml
```
To activate the conda environment for these once they are installed use:
```
conda activate cwltutorial
```

If you do not wish to use conda to install these then alternative install instructions 
are included on the course [Setup page](https://carpentries-incubator.github.io/cwl-novice-tutorial/setup.html).

