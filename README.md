

Experiments for various configuration can be run using the `run.py`. First of all, install the python packages (preferably in a clean virtualenv): `pip install -r requirements.txt`

```
Usage: run.py [OPTIONS]

  Train BERT sentiment classifier.

  Options:
    -c, --bert-config TEXT  Pretrained BERT configuration
    -b, --binary            Use binary labels, ignore neutrals
    -r, --root              Use only root nodes of SST
    -s, --save              Save the model files after every epoch
    -h, --help              Show this message and exit.
```

For example, to run the experiment for binary labels and root nodes, run:

    python3 run.py -rb

