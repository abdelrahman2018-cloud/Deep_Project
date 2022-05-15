Practical Machine Deep Learning project
Sentiment Classification
Dr.mostafa youssef

By: Abdelrahman Elgammal - 900181126
    Abdelrahman Abouzeid - 900181004



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

    python3 run.py -r -b -s

