# RF Signal Transformation and Classification using Deep Neural Networks
Official Repository of the RF Classification Paper accepted in SPIE Defense and Commercial Symposium 2022. Paper Link [Link](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12097/1209707/RF-signal-transformation-and-classification-using-deep-neural-networks/10.1117/12.2619076.full)
## Datasets used: 
1- RadioML2016<br />
2- RF1024 
## How to Download the dataset?
1- RadioML2016 will be automatically downloaded on running RadioML_2016_Train.py<br />
2- RF1024 Dataset: [Google Drive Link to Download RF1024 Dataset](https://drive.google.com/drive/folders/1V7sZbf0UuQJ1V0Fmkg0xltx0UqNRQ8Jg?usp=sharing)<br />
Place the downloaded dataset in the folder rf1024_data
## Training
```bash
python RadioML_2016_Train.py --model resnet18
```
```bash
python RF1024_Train.py --model resnet18
```

