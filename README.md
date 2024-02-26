# SE4Hate - Small Electra for Hate

We present SE4Hate, an Electra Small-based approach for hate classification. We trained our model on the [Dynamically generated hate speech dataset](https://github.com/bvidgen/Dynamically-Generated-Hate-Speech-Dataset). We used the overall data with a 70/30 train-test ratio for training and testing. We achieved a score of 78.8785% F1 with our lightweight approach.

## Training results

We trained our model with 50 epochs and saved a temporal backup of each model by epoch and tested each one looking to achieve the best result. The overall training loss is shown in the next figure:

![Loss during training](./figures/Average_Loss_of_SE4Hate_per_epoch.png)

The score of each epoch shows that the model starts to overfit in the middle epochs, so we selected epoch 23 for our best model. Both epoch 23 and the final epoch model are available in our models folder. The performance of each training model is shown in the figure below:

![Performance of SE4Hate](./figures/Train_and_Test_F1_Scores_of_SE4Hate_Over_Epochs.png)

Finally, all images and resources are attached in this GitHub repository; the final results are in the results/ folder.

## Architecture

We used a Google Colab Pro Session with a T4 as Graphics Card. The './notebooks/SE4Hate.ipynb' compiles in around 16 hours because of the evaluation, so it is preferred to test other models by changing the names of the saving in case you want to replicate or improve the achieved results.

## Cite

You can cite our work here::

```plaintext
Coming Soon...


```
