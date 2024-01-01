# Call-Backs-child-branch

### We have to implement the following callbacks
-  Write your own callback function, that has to print the micro F1 score and AUC score after each epoch.Do not use tf.keras.metrics for calculating AUC and F1 score.

- Save your model at every epoch if your validation accuracy is improved from previous epoch. 

- You have to decay learning based on below conditions 
        Cond1. If your validation accuracy at that epoch is less than previous epoch accuracy, you have to decrese the
               learning rate by 10%. 
        Cond2. For every 3rd epoch, decay your learning rate by 5
        
- If you are getting any NaN values(either weigths or loss) while training, you have to terminate your trainin

- You have to stop the training if your validation accuracy is not increased in last 2 epoch

- Use tensorboard for every model and analyse your scalar plots and histograms. (you need to upload the screenshots and write the observations for each model for evaluatio

