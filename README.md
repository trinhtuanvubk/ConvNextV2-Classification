# ConvNext V2 for Classification

## Step
### Install dependencies:
```bash
pip install -r requirements.txt
```

### Data preprocessing:
```
Dataset should be folder data
```
### Divide the dataset
```
# We use all the train data and 2/3 of the val data as the final training set, and the remaining val data as the validation dataset.

python data_arrange.py
```

### Start training
```
# We have usd a pre-trained model based on ImageNet provided by timm.
python main.py
```

### Test your model
```
# When the training is over, you can copy the checkpoint.pth.tar in reulst to the root directory and use it for testing.
python test.py
```

### TODO

