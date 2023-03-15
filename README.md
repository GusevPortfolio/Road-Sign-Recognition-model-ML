# Sign detection CNN project

![Sign list](https://github.com/GusevPortfolio/Road-sign-detection-ML/blob/main/Data/Sign%20list1.png)

Transfer learning -take a pre-trained VGG16 network and retrain it to recognize traffic signs.
Kaggle dataset -GTSRB -German Traffic Sign Recognition Benchmark. (https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)

## Test dataset analysis:
Total: 43 classes = 39209 png= 100%
Majority: 17 classes = 28710 png= 73.2%
Minority: 26 classes = 10499 png= 26.7%
 
![Data analysis](https://github.com/GusevPortfolio/Road-sign-detection-ML/blob/main/Data/Data%20analysis.jpg)

## Model results:

Epoch 10: Train Acc. = 90.8% / Test Acc. = 76.6%


![Epoch 10](https://github.com/GusevPortfolio/Road-sign-detection-ML/blob/main/Data/10%20-%20loss.jpg)
![Epoch 10](https://github.com/GusevPortfolio/Road-sign-detection-ML/blob/main/Data/10%20-%20accuracy.jpg)

Epoch 30: Train Acc. = 94.4% / Test Acc. = 78.5%


![Epoch 30](https://github.com/GusevPortfolio/Road-sign-detection-ML/blob/main/Data/30%20-%20loss.jpg)
![Epoch 30](https://github.com/GusevPortfolio/Road-sign-detection-ML/blob/main/Data/30%20-%20accuracy.jpg)

Epoch 50: Train Acc. = 98.0% / Test Acc. = 78.6%


![Epoch 10](https://github.com/GusevPortfolio/Road-sign-detection-ML/blob/main/Data/50%20-%20loss.jpg)
![Epoch 10](https://github.com/GusevPortfolio/Road-sign-detection-ML/blob/main/Data/50%20-%20accuracy.jpg)


## Conclusions:

### Transfer learning saves time.

  • 10 epochs - 23 min.

  • 30 epochs - 65 min.
  
  • 50 epochs - 116 min.



### Dataset is imbalanced.

  • 39209 pictures for 43 classes.
  
  • 1 class takes from 5.7% to 0.5% (10+ times difference).


  
### More epochs & accuracy required more training data.

  • 10 epochs – underfit. (90,8% train acc. and 76,6% test acc.);
  
  • 30 epochs vs 10 – fit. (+3,6% train acc., but +1,9% test acc.);
  
  • 50 epochs vs 30 – overfit. (+3,6% train acc., but +0,1% test acc.);
