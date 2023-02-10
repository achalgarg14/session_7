# Assignment - 7
## Problem Statement

<img width="845" alt="Screenshot 2023-02-10 at 8 46 15 PM" src="https://user-images.githubusercontent.com/118976187/218132615-c0a3eec2-cd2f-43e9-8437-95a971031a0c.png">
<img width="828" alt="Screenshot 2023-02-10 at 8 49 55 PM" src="https://user-images.githubusercontent.com/118976187/218132645-9c0a99bb-20bb-4979-bf9c-e6bdc60ebf3f.png">

## Code Details
- The main code (model, main, utils) etc. are defined in the github repository [here](https://github.com/achalgarg14/eva8_main_folder)
- In notebook [Session_7_Assignment_OneCycleLR.ipynb] functions from the main github repository are called
- Model ResNet18 is trained for 20 Epochs on CIFAR10 dataset using OneCycleLR
- Training Accuracy achieved in final layer is 94.53%
- Test Accuracy achieved in final layer is 85.71%

## Training Log:
```
EPOCH: 0
Loss=1.469355583190918 Batch_id=390 Accuracy=45.76: 100%|██████████| 391/391 [00:46<00:00,  8.38it/s]

Test set: Average loss: 0.0107, Accuracy: 5399/10000 (53.99%)

EPOCH: 1
Loss=0.9286737442016602 Batch_id=390 Accuracy=64.20: 100%|██████████| 391/391 [00:45<00:00,  8.53it/s]

Test set: Average loss: 0.0060, Accuracy: 7326/10000 (73.26%)

EPOCH: 2
Loss=0.6467236280441284 Batch_id=390 Accuracy=71.46: 100%|██████████| 391/391 [00:45<00:00,  8.53it/s]

Test set: Average loss: 0.0054, Accuracy: 7650/10000 (76.50%)

EPOCH: 3
Loss=0.6445907354354858 Batch_id=390 Accuracy=76.24: 100%|██████████| 391/391 [00:45<00:00,  8.55it/s]

Test set: Average loss: 0.0061, Accuracy: 7397/10000 (73.97%)

EPOCH: 4
Loss=0.4840644896030426 Batch_id=390 Accuracy=79.36: 100%|██████████| 391/391 [00:46<00:00,  8.48it/s]

Test set: Average loss: 0.0050, Accuracy: 7859/10000 (78.59%)

EPOCH: 5
Loss=0.5377910137176514 Batch_id=390 Accuracy=81.56: 100%|██████████| 391/391 [00:45<00:00,  8.51it/s]

Test set: Average loss: 0.0044, Accuracy: 8147/10000 (81.47%)

EPOCH: 6
Loss=0.31837671995162964 Batch_id=390 Accuracy=83.84: 100%|██████████| 391/391 [00:45<00:00,  8.53it/s]

Test set: Average loss: 0.0046, Accuracy: 8115/10000 (81.15%)

EPOCH: 7
Loss=0.42120838165283203 Batch_id=390 Accuracy=85.49: 100%|██████████| 391/391 [00:45<00:00,  8.52it/s]

Test set: Average loss: 0.0047, Accuracy: 8066/10000 (80.66%)

EPOCH: 8
Loss=0.49981746077537537 Batch_id=390 Accuracy=86.64: 100%|██████████| 391/391 [00:45<00:00,  8.57it/s]

Test set: Average loss: 0.0042, Accuracy: 8334/10000 (83.34%)

EPOCH: 9
Loss=0.5603433847427368 Batch_id=390 Accuracy=88.21: 100%|██████████| 391/391 [00:46<00:00,  8.40it/s]

Test set: Average loss: 0.0050, Accuracy: 8045/10000 (80.45%)

EPOCH: 10
Loss=0.317478209733963 Batch_id=390 Accuracy=88.98: 100%|██████████| 391/391 [00:45<00:00,  8.50it/s]

Test set: Average loss: 0.0043, Accuracy: 8450/10000 (84.50%)

EPOCH: 11
Loss=0.40520644187927246 Batch_id=390 Accuracy=90.19: 100%|██████████| 391/391 [00:46<00:00,  8.47it/s]

Test set: Average loss: 0.0037, Accuracy: 8567/10000 (85.67%)

EPOCH: 12
Loss=0.3573499619960785 Batch_id=390 Accuracy=90.78: 100%|██████████| 391/391 [00:45<00:00,  8.55it/s]

Test set: Average loss: 0.0046, Accuracy: 8383/10000 (83.83%)

EPOCH: 13
Loss=0.20453336834907532 Batch_id=390 Accuracy=91.66: 100%|██████████| 391/391 [00:45<00:00,  8.53it/s]

Test set: Average loss: 0.0039, Accuracy: 8556/10000 (85.56%)

EPOCH: 14
Loss=0.10330705344676971 Batch_id=390 Accuracy=92.32: 100%|██████████| 391/391 [00:45<00:00,  8.53it/s]

Test set: Average loss: 0.0048, Accuracy: 8321/10000 (83.21%)

EPOCH: 15
Loss=0.3345770537853241 Batch_id=390 Accuracy=92.35: 100%|██████████| 391/391 [00:46<00:00,  8.49it/s]

Test set: Average loss: 0.0044, Accuracy: 8393/10000 (83.93%)

EPOCH: 16
Loss=0.20436763763427734 Batch_id=390 Accuracy=93.13: 100%|██████████| 391/391 [00:45<00:00,  8.52it/s]

Test set: Average loss: 0.0042, Accuracy: 8546/10000 (85.46%)

EPOCH: 17
Loss=0.17770162224769592 Batch_id=390 Accuracy=93.39: 100%|██████████| 391/391 [00:45<00:00,  8.58it/s]

Test set: Average loss: 0.0040, Accuracy: 8593/10000 (85.93%)

EPOCH: 18
Loss=0.18458393216133118 Batch_id=390 Accuracy=93.86: 100%|██████████| 391/391 [00:45<00:00,  8.53it/s]

Test set: Average loss: 0.0046, Accuracy: 8477/10000 (84.77%)

EPOCH: 19
Loss=0.2573799788951874 Batch_id=390 Accuracy=94.53: 100%|██████████| 391/391 [00:45<00:00,  8.53it/s]

Test set: Average loss: 0.0041, Accuracy: 8571/10000 (85.71%)

Saved Model weights in file: /content/drive/MyDrive/EVA8/Session_7/Model_final_acc_85.71.pth
Total Number of incorrectly predicted images by model is 1429
```

## Accuracy & Loss Curve
<img width="933" alt="Screenshot 2023-02-10 at 9 03 52 PM" src="https://user-images.githubusercontent.com/118976187/218133861-7a04eac7-bb50-4319-8d32-d6b35bd26d03.png">

## Misclassified Images
<img width="591" alt="Screenshot 2023-02-10 at 9 04 45 PM" src="https://user-images.githubusercontent.com/118976187/218133940-c5a13a16-31b1-4fd4-8cb6-90e60db523b9.png">

## GradCam Output
<img width="1169" alt="Screenshot 2023-02-10 at 9 05 29 PM" src="https://user-images.githubusercontent.com/118976187/218134070-08c0fc28-5800-4a10-a6fb-bef050dd2920.png">

## Conclusion
- The model has training accuracy higher than test accuracy for many last layers
- Model seems to be overfitting
- GradCam images shows that the main object is not being detected while because focus area is bad
- For example: when bird is there it is prediction ship
