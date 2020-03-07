### Performance parameters:

 1. Image size

 2. precision, recall, f1-score, support 

    ```
       			precision   recall    f1-score    support
    
    others         0.92      0.78      0.84        59
    pavbhaji       0.84      0.94      0.89        70
    
    micro avg      0.87      0.87      0.87       129
    macro avg      0.88      0.86      0.86       129
    weighted avg   0.87      0.87      0.87       129
    
    confusion matrix 
     [[46 13]
     [ 4 66]]
    ```

    

### Explain why you choose particular Model?

 Model: xception
 This particular model helps to reduce model parameters with depthwise separable convolution.



### What are the challenges you faced while working on the data?

 1. Data set is very small to segregate into categories.
 2. Image has noisy background.
 3. Imbalanced data set



### How did you overcome those and what approach you try to solve the problem?

 I used augmentation technique and pre-trained  imageNet weights.