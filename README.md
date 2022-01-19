# Pulsar-Classification
![](https://github.com/EvanBagis/Pulsar-Classification/blob/master/pulsar.jpg)


In this jupyter notebook, the open dataset [predicting a pulsar star](https://www.kaggle.com/colearninglounge/predicting-pulsar-starintermediate) is used for data analysis and for building a neural network classifier. Core concepts of the analysis are demonstrated with the help of graphs and heatmaps. The model is validated via validation accuracy, validation loss and the confusion matrix. Furthermore, the concept of imbalanced classes is taken into account by building two different neural networks and comparing the results. 

## Install libraries

numpy, pandas, scikit-learn, seaborn, tensorflow, matplotlib

```bash
pip install numpy
pip install pandas
etc
```

## Results

Scatter plots
![](https://github.com/EvanBagis/Pulsar-Classification/blob/master/output_4_2.png)

Correlation heatmap

![](https://github.com/EvanBagis/Pulsar-Classification/blob/master/output_5_1.png) | Analysis
:-------------------------:|:-------------------------:

Balancing the dataset
![](https://github.com/EvanBagis/Pulsar-Classification/blob/master/output_6_1.png)   |  ![](https://github.com/EvanBagis/Pulsar-Classification/blob/master/utput_7_1.png)
:-------------------------:|:-------------------------:
Imbalanced  |  Balanced

Validation scores
![](https://github.com/EvanBagis/Pulsar-Classification/blob/master/output_11_0.png)   |  ![](https://github.com/EvanBagis/Pulsar-Classification/blob/master/output_12_0.png)
:-------------------------:|:-------------------------:
Loss  |  Accuracy

Confusion matrix
![](https://github.com/EvanBagis/Pulsar-Classification/blob/master/output_8_0.png)    |  ![](https://github.com/EvanBagis/Pulsar-Classification/blob/master/output_9_0.png)
:-------------------------:|:-------------------------:
Imbalanced  |  Balanced

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
