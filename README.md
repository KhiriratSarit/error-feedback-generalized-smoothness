# error-feedback-generalized-smoothness
# Image classification experiments on CIFAR-10

We present the code of the experimental results of the paper "Communication-efficient Algorithms Under Generalized Smoothness Assumptions".

The implementation uses PyTorch. 

Example commands:

 ```
python EF21-norm.py --max_it 7800 --k 2700 --num_workers 5 --factor 5000 --batch_size 128 --model resnet20 --dataset CIFAR10
python show_plots.py experiment_EF21-norm_K_2700_sz_5000_nw_5_bsz_128_resnet20_at_CIFAR10.bin
 ```

