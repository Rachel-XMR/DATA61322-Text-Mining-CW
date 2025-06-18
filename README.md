# DATA61322-Text-Mining-CW

Overview： [⁠⁠⁠Lark Docs](https://kjpmqncy06v6.jp.larksuite.com/wiki/FKsBww0Bsi99zYkBIsLj6Ly9puh?fromScene=spaceOverview)

# Textual relationship extraction based on LSTM model and attention mechanism

## Project Information

To perform the task of relation extraction using LSTM model and introducing multi-head attention mechanism on LSTM model and to compare the performance of these two approaches

## Task

* Task1：The training of two models, LSTM model and LSTM+multi-head attention Mechanism, was completed respectively.
* Task2：Completed evaluation of the performance of both models
* Task3：The task of relationship extraction can be performed online using the trained model

## Start

### Environmental requirements

* Requirement 1:Capable of running Pytorch
* Requirement 2:GPUs are required to run the text-relational extraction method in colab
* Requirement 3:If you want to explore Hugging face space, please visit [https://huggingface.co/spaces/Henry010/lstm-relation-extraction](https://huggingface.co/spaces/Henry010/lstm-relation-extraction) to explore the online text-relational extraction

### How to use

It is recommended to enter Hugging face space https://huggingface.co/spaces/Henry010/lstm-relation-extraction for a better interaction experience!

## Project structure

```
Textming_Coursework/

├── notebooks/

│   ├── Multi-head attention+ LSTM.ipynb     # LSTM+multi-head attention Mechanism

│   └── LSTM.ipynb                           # LSTM Code

│   └── Online Relation Extraction.ipynb # Relation Extraction only in colab

│   └──Deploying models to hugging face space.ipynb #online Relation Extraction

├── output/                                  # Model output catalogue

│   ├── LSTM/                               # LSTM model related outputs

│   │   ├── final_model.pkl                 # LSTM's final model

│   │   └── config.json                     # LSTM's config

│   │

│   └── Att_LSTM/                           # Multi-head Attention Mechanism + LSTM Model Related Outputs

│       ├── final_model.pkl                 # final model

│       └── config.json                     # config

│

├── embedding/                              # word embeddings

│   └── glove.6B.100d.txt                  # GloVe pre-trained word vectors(100 dims)

│

└── data/                                   # data

    ├── train.json                         # train dataset

    ├── test.json                          # test dataset

    └── relation_with_id.txt               # Relational ID mapping file
```


## Configuration

Once configured according to the project structure, you can run the ipynb file and train the model.
