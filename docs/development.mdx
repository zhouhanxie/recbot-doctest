# Developer Guides

## Data Loading

Currently I organize datasets under the format of Huggingface's [datasets](https://huggingface.co/docs/datasets/dataset_script).

My idea is that we leave any dataset as it is and expose the information that a dataset provides through the `datasets` interface (if necessary, use [Multiple configurations](https://huggingface.co/docs/datasets/main/en/dataset_script#multiple-configurations) to provide different formats for certain tasks). 

And for any model-specific methods like data-preprocessing and tokenization, we write for each *model* a `Datahandler` to process the data on a per-example basis (using the `datasets.map` function). Note that the `datasets` package will cache results from `load_dataset()` and `map()`. If you need to re-run these functions, please pass`load_from_file=False`. 

The major benefits of writing the `Datahandler` is to support the Huggingface Trainer by providing it with the processed datasets (You may also use a traditional dataloader, but it requires writing manual training loop to use with the huggingface Trainer). And a by-product is we will have clear separation between data-processing and data-collation.

Here are the two huggingface datasets I have implemented:
The [ReDIAL dataset](https://github.com/McAuley-Lab/RecBot/blob/pipeline-redial/dataset/redial/redial.py) supports 3 types of tasks: sentiment analysis, AutoRec and conversational recommendation. 

The [Movielens dataset](https://github.com/McAuley-Lab/RecBot/blob/pipeline-redial/dataset/movielens/movielens.py) which is used for AutoRec pre-training.


[Here](https://github.com/McAuley-Lab/RecBot/blob/pipeline-redial/src/datahandler/redial_datahandler.py) is the `DataHandler` class for the "ReDIAL *model*". It basically handles all the dirty work before the data runs into the data collator. One thing to note is that it adopts a `@singleton` design so that certain kinds of collected information (e.g.  mapping between movies and ids) can be accessed wherever needed.

## Model training


## Share Your Own Dataset 

## Share Your Own Model