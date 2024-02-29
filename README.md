Please cite the following paper if you are using this code.

Reference
---------------
M. Sajid, A. K. Malik, M. Tanveer and P. N. Suganthan, "Neuro-Fuzzy Random Vector Functional Link Neural Network for Classification and Regression Problems," in IEEE Transactions on Fuzzy Systems, doi: 10.1109/TFUZZ.2024.3359652.



Bibtex
------
@ARTICLE{10416391,
  author={Sajid, M. and Malik, A. K. and Tanveer, M. and Suganthan, P. N.},
  journal={IEEE Transactions on Fuzzy Systems}, 
  title={Neuro-Fuzzy Random Vector Functional Link Neural Network for Classification and Regression Problems}, 
  year={2024},
  volume={},
  number={},
  pages={1-13},
  keywords={Training;Computational modeling;Task analysis;Predictive models;Adaptation models;Optimization;Iterative methods;Random Vector Functional Link (RVFL) Network;Neuro-Fuzzy;Fuzzy Neural Network;Extreme Learning Machine;Interpretability},
  doi={10.1109/TFUZZ.2024.3359652}}
  
Experimental Setup
-----------------
The experimental procedures are executed on a computing system possessing MATLAB R2023a software, Intel(R) Xeon(R) Platinum 8260 CPU @ 2.30GHz, 2301 Mhz, 24 Core(s),
48 Logical Processor(s) with 256 GB RAM on a Windows-10 operating platform. 

We have put a demo of the “Neuro_Fuzzy_RVFL” model with the “credit_approval” dataset 

The following are the parameters set used for the experiment 

C=0.001; %Regularization parameter
N=15; %Fuzzy Nodes
L=203; %Hidden Nodes
Act=5; %Activation Function

Description of Files
---------------------
Neuro_Fuzzy_RVFL_main.m: This is the main file to run selected models on datasets. In the path variable specificy the path to the folder containing the codes and datasets on which you wish to run the algorithm. 

Neuro_Fuzzy_RVFL_train.m: the main file calls this file for the training and testing process.

relu.m: Code of the relu activation function.

sigmoid.m: Code of the sigmoid activation function.
---------------------------------------------------

The codes are not optimized for efficiency. The codes have been cleaned for better readability and documented and are not exactly the same as used in our paper. 
For the detailed experimental setup, please follow the paper. 
We have re-run and checked the codes only in a few datasets, so if you find any bugs/issues, please write to M. Sajid (phd2101241003@iiti.ac.in).


Some parts of the codes have been taken from:
1. Zhang, Le, and Ponnuthurai N. Suganthan. "A comprehensive evaluation of random vector functional link networks." Information Sciences 367 (2016): 1094-1105.
2. Feng, Shuang, and CL Philip Chen. "Fuzzy broad learning system: A novel neuro-fuzzy model for regression and classification." IEEE transactions on cybernetics 50, no. 2 (2018): 414-424.

29-Feb-2024
