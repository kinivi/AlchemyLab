# Advanced RAG

## Prequisites

- Environment: `Python 3.10.13` with `Anaconda`
- Create Conda environment with command: ```conda create -n advanced_rag_env python=3.10.13```
- Activate conda environment on terminal: ```conda activate advanced_rag_env```
- Install `pytorch` inside the environment: ```conda install pytorch torchvision -c pytorch```
- Install conda pip: ```conda install pip```
- Install requirements: ```pip install -r requirements.txt```

## Setting up wandb.ai
 
Run this code on a Python Conda environment shell: 
```python
import wandb

wandb.login(key="your_wandb_api_key")
```
