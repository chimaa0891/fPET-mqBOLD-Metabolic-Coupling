# Analysis Notebooks

This directory contains the two original analysis notebooks used during
development of the fPET-mqBOLD metabolic-coupling project.

## Final / Corrected Notebook

Use:

`final/fPET_mqBOLD_coupling_pipeline_CMRglcFIX.ipynb`

This is the scientifically valid corrected analysis notebook.

The correct fPET CMRglc condition construction is:

CMRglc_REST = baseline

CMRglc_STIM = baseline + checker GLM effect

The final manuscript results and scientific interpretation should be based
on this notebook.

## Legacy / Pre-Fix Notebook

`legacy/fPET_mqBOLD_coupling_pipeline.ipynb`

This notebook is retained only for transparency and development history.

IMPORTANT:

The legacy notebook predates the correction to stimulation CMRglc
construction. It must NOT be used for final CMRglc, OGI, stimulation,
or coupling-deviation results.

For scientific reproduction, use the notebook in the `final/` directory.
