## How to run
I created two training models: one trained on multiple choice questions (train_mc), and the other was trained on question answering (train_qa). 

By running ```train.sh```, you could start training your models with the data provided, which will be put inside the folder, data, with the names of ```train.json``` for training data, and ```valid.json``` for validation data. I saved the results to their correponding respositories: 


## Training on hfl/chinese-roberta
I first use ```format.transform.py``` to make the format of our original dataset to the format that the pre-trained model could use.


README.md
run.sh
download.sh
report.pdf
your code/script (all the code/script you used to train, predict, or plot report figures should be included).
```
/
ADL_hw1/
│   ├── README.md
│   ├── run.sh
│   ├── download.sh
│   ├── report.pdf
│   ├── dataset/
│   │   ├── train.json
│   │   ├── valid.json
│   │   ├── test.json
```
