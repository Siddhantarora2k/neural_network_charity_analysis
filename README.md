# neural_network_charity_analysis

# Overview
The purpose of this analysis was to create a neural network model on a data where we can predict which companies are most likely to succed if funded.

----------------------------

# Results
Before Optimization

Hidden layer 1 = 90
<img width="1440" alt="Screen Shot 2022-04-02 at 4 47 02 PM" src="https://user-images.githubusercontent.com/91028094/161400731-70695fc2-9f07-4190-b3d5-fabdd385e741.png">

After Optimization

<img width="1440" alt="Screen Shot 2022-04-02 at 4 47 15 PM" src="https://user-images.githubusercontent.com/91028094/161400735-fd376934-c290-4a4f-9542-ccf9a9848925.png">

---------------------------

# Approach
1. I tried increasing the number of hidden layers but instead it decreased the accuracy.
2. I tried increasing and decreasing the number of neurons but also no luck and resulted in decreased accuracy.
3. The only thing that worked for me was When I dropped the column "SPECIAL_CONSIDERATIONS" which increased the accuracy by 2%.
