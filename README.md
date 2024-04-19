# Pareto HyperNetworks 




## Install

```bash
git clone https://github.com/jadboutzil/Cassiopp-eMultiMNIST.git
cd Cassiopp-eMultiMNIST
pip install -e .
```

## Run Experiments
To run the experiment follow these steps.
- Download the mult_mnist.pickle file from [here](https://drive.google.com/open?id=1VnmCmBAVh8f_BKJg1KYx-E137gBLXbGG).
- Create a `data` folder and put the `.pickle` file inside it.
- The data folder should be positioned like this:
```bash
/CASSIOPPEEMULTIMNIST/
├── experiments/
│   └── multimnist
        └──trainer.py (etc)
└── data/
    └── multi__mnist.pickle
etc.
```
-Run the LeNet experiment using : 
```bash
python experiments/multimnist/trainer.py --datapath data/multi_mnist.pickle 
```    
