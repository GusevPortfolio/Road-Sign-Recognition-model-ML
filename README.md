# Sign detection CNN project

Transfer learning -take a pre-trained VGG16 network and retrain it to recognize traffic signs.
Kaggle dataset -GTSRB -German Traffic Sign Recognition Benchmark. (https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)

### Test dataset analysis:
Total: 43 classes = 39209 png= 100%
Majority: 17 classes = 28710 png= 73.2%
Minority: 26 classes = 10499 png= 26.7%
 
![Data analysis](https://github.com/GusevPortfolio/Road-sign-detection-ML/blob/main/Data/Data%20analysis.jpg)

### Model results:

Epoch 10: Train Acc. = 90.8% / Test Acc. = 76.6%
![Epoch 10](https://github.com/GusevPortfolio/Road-sign-detection-ML/blob/main/Data/10%20-%20loss.jpg)
![Epoch 10](https://github.com/GusevPortfolio/Road-sign-detection-ML/blob/main/Data/10%20-%20accuracy.jpg)

Epoch 30: Train Acc. = 94.4% / Test Acc. = 78.5%
![Data analysis](https://github.com/GusevPortfolio/Road-sign-detection-ML/blob/main/Data/Data%20analysis.jpg)
![Data analysis](https://github.com/GusevPortfolio/Road-sign-detection-ML/blob/main/Data/Data%20analysis.jpg)

Epoch 50: Train Acc. = 98.0% / Test Acc. = 78.6%
![Data analysis](https://github.com/GusevPortfolio/Road-sign-detection-ML/blob/main/Data/Data%20analysis.jpg)
![Data analysis](https://github.com/GusevPortfolio/Road-sign-detection-ML/blob/main/Data/Data%20analysis.jpg)
