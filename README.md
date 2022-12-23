# Fact-Based Logical Reasoning
This is the code for the project "Fact-Based Logical Reasoning".



## Environment
(I've set the environment with the latest versions of following libraries)

- python
- pytorch
- dgl-cu110
- transformers
- tensorboardX
- spacy



## How to run?

Run the following code in bash terminal/console:

```bash
bash scripts/run_roberta_large.sh
```


Can change the dataset directory in the scripts to run different tasks. For example, to run logiQA, set 

```BASH
RECLOR_DIR = logiQA_data
TASK_NAME = logiqa
```

The accuracies of the "FOCAL REASONER" model on the dev sets are stored in the folder "Checkpoints", with test results stored in "test_pred.npy"
