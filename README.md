# Keras-Lithium-Ion-Battery-State-of-Health-Estimation-based-on-Battery-Temperature
To estimate the battery SoH from the differences in temperature, LSTM Network is utilized to estimate the remaining SoH based on the battery state of temperature.

Details about how things work was explained briefly in the Lithium-Ion Battery SoH Estimation using LSTM.ipynb file, for detailed explanation is also discussed in the Paper.pdf file (in Bahasa Indonesia).

The dataset that used in this project was made independently using XTAR CR123 Rechargeable Battery that has been cycled thoroughly using SKYRC MC3000 Universal Battery Charger and Analyzer that each of the battery parameters were recorded with MC3000 Monitor V1.05 and sampled for each second (in the raw dataset) which later going to be processed to be able to be used as the training dataset.

To run the following notebook, run each block of code according to the following order, be careful about the loadable files placement that you might want to look carefully if you plan to run this notebook in your own device (instead of do the training all over again, you might want to load the pretrained network with the name of weight_LSTM).

![ezgif-4-fe83cb7b98](https://github.com/nrahadi/Keras-Lithium-Ion-Battery-State-of-Health-Estimation-based-on-Battery-Temperature/assets/144195641/2bdd81f2-4fd9-450e-9b9a-a5bac5834efc)
