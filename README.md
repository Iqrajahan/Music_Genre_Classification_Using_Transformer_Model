# Music_Genre_Classification_Using_Transformer_Model
In this Project transformer model is performing Music Genre classification. 
In this project we are performing EDA (Exploratory Data Analysis) on the dataset containing temporal and frequency domain features extracted from audio music signals. We performed Principal Component Analysis (PCA) to deal with the multicolinearity. After preprocessing and data cleaning we further moved towards our classification task. Transformer Model is using AdamW optimiser and is performing the classification. We used Early stopping and Learning rate scheduler in training loop. 
Early stopping ensures that training halts once the model stops improving, avoiding overfitting and wasting computation.
Learning rate scheduling adjusts the learning rate dynamically, helping the model avoid plateaus and improving convergence. If the model's loss gets stuck (plateaus), reducing the learning rate can help the model make finer adjustments to continue reducing the loss.

Summary
