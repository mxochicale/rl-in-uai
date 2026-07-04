# reinforcement-learning-examples-in-unified-ai

## skrl 

```bash
git submodule add https://github.com/mxochicale/skrl.git
```

To update the germinal submodule to its latest remote commit (optional):
```bash
git submodule update --remote skrl
```

If the submodule directory exists but is empty, run
```bash
git submodule update --init --recursive
```

Install skrl
```bash
cd skrl
pip install -e .[torch]
pip install "gymnasium[classic-control]"
```

Example
```bash
python examples/gymnasium/torch_gymnasium_cartpole_cem.py
python examples/gymnasium/torch_gymnasium_cartpole_dqn.py
```


## Clone  
```bash
git clone --recurse-submodules https://github.com/mxochicale/rle-in-uai.git
```
