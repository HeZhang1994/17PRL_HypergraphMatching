# Hyper-graph Matching
This is the **MATLAB** implementation of hyper-graph matching of the paper [Game theoretic hypergraph matching for multi-source image correspondences](https://www.sciencedirect.com/science/article/pii/S0167865516301738) pubilised on <i>Pattern Recognition Letters</i>.

# Environment
The code has been tested on a PC machine with **Windows 7 operating system (64-bit)**, using **MATLAB2013a** software. 

# Compiling
Execute `siftWin32.exe` on **Windows** operating system before running the hyper-graph matching code.

# Running
Run the `run_matching.m` file on MATLAB.

Tune parameters (i.e., `distRatio`, `imresizerate1` and `imresizerate2`) to large value (less than 1) will generate more key points and lead to low matching speed. 

It should be noted that the runtime reported in our paper did not include the establishment of hyper-graphs (i.e., the time of constructing hyper-edges).

# Citation
This MATLAB implementation is provided for research purposes only. If you use the code in your research work, please cite the following paper: 

    @Article{hz17HypergraphMatch, 
      title      = {Game theoretic hypergraph matching for multi-source image correspondences}, 
      author     = {Zhang, He and Ren, Peng}, 
      journal    = {Pattern Recognition Letters}, 
      volume     = {87}, 
      pages      = {87--95}, 
      year       = {2017}, 
      publisher  = {Elsevier} 
    } 
