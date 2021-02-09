# Introduction
This is the code for double-blind review of SIGKDD 2021.
# Running
The script to run:
1. Make sure you give the correct path to dataset, the var is `PATH`
2. `python process_ml100k.py`
3. `python run_TGREC.py -d ml-100k --uniform --bs 600 --lr 0.001 --n_degree 20 --agg_method attn --attn_mode prod --gpu 0 --n_head 2 --n_layer 2 --prefix Video_Games_bce --node_dim 32 --time_dim 32 --drop_out 0.3 --reg 0.3 --negsampleeval 1000`
