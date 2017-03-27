# VLPP: Villeneuve Laboratory PET Pipeline

## Install

### Software dependencies

- [matlab](https://www.mathworks.com/)
- [spm](http://www.fil.ion.ucl.ac.uk/spm/)
- [fsl](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/)
- [freesurfer](https://surfer.nmr.mgh.harvard.edu/)
- https://github.com/SIMEXP/brainsprite.js.git
- https://github.com/keen/dashboards.git

### Python dependencies

The file `environment.yml` contains the python dependencies. Installing through [conda](https://conda.io/docs/) is highly recommended.

#### Create the environment `vlpp-env`

```
conda config --add channels conda-forge
conda env create -f environment.yml
```

#### Update the environment

`conda env update -f environment.yml`

## Launch

## Output

### scratch directory

## Informations

Developer and maintainer: *Christophe Bedetti*

*Warning: Project under active development, process data at your own risk !!*
