# Neural_Network_Charity_Analysis


## Purpose of Analysis
The purpose of this analysis was to build a neural network to determine which applicant companies are worthy of receiving loans from Alphabet Soup.

## Results
* 1) Data Preprocessing
     * Target Column: IS_SUCCESSFUL
     * Features: All remaining columns with the exception of EIN and Name.
     * Removed: EIN & Name

* 2) Compiling, Training, and Evaluating the Model
     * I began with 2 layers with 10 and 5 neurons respectively. Ultimately I wound up with 5 layers with 10, 10, 8, 5, 5 neurons respectively. I used relu for the hidden layers and sigmoid for the output.
     * I was not able to attain a 75% accuracy with my neural network attempts.
     * I removed additional columns that seemed unneccessary to the task at hand, and added a hidden layer in each additional attempt, landing at 5 total.
     
## Summary
Based on my work with this neural network, I could not significantly improve the accuracy despite several adjustments to the data and model itself. Ultimately, it's possible that I removed too many of the columns, but I did re-apply columns that seemed to drop my accuracy rate as I tested the model, and also tried various different neuron counts. The only thing that I did not change was my choice of relu and sigmoid, which I felt were the right choices.


```bash
Kyle Schneider, 1/24/2020
```
