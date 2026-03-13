# Reproducibility note
To reproduce the figures in section 3 of the paper, first run one of the following codes,
- 2D_mult_level_fbpinns_repr.ipynb,
- 2D_multi_level_delta_varying.ipynb,
- 2D_multi_level_hidden_units.ipynb,
- PINN_baseline.ipynb.

To reproduce the figures in section 4 of the paper, first run the code `Stress testing - 1D u'' = f.ipynb`.

To generate the actual figures, run the command `tensorboard --logdir results/summaries/`.
Now the data can be analysed in the tensorboard and exported to a csv file. 
These csv files can be imported into `plots_reproduction.ipynb`.

**Note: Prior to running this code, you should setup the environment as mentioned [here](https://github.com/benmoseley/FBPINNs).**