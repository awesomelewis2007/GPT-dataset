# GPT Dataset
This repository contains data that ChatGPT has created. The data is in csv format.
<img src="https://i.insider.com/63ef9e660270b1001984d9ce?width=2000&format=jpeg&auto=webp" width=400>

There are `48` datasets in this repository

> **Warning**
>
> The data in this repository is not suitable for training since it comes from Chat GPT and could be random data. You can still use it just keep in mind it might me random data and not real data.

## Datasets
The datasets are in the `dataset` folder. In this folder you will find more folders with a 4 digit number. This number is the dataset id. Inside each of these folders you will find a `dataset.csv` file. This file contains the data. You will also find a file called `prompt.txt` this file contains the prompt that was used to generate the data and you will find a file called `README.md` this file contains information about the dataset.

```
.
└── dataset
    └── <dataset_id>
        ├── data.csv
        ├── prompt.txt
        └── README.md
```

## Example prompt

For some examples of prompts you can look at the [prompts.md](prompts.md) file.