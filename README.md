# Neural Network Charity Analysis

## Overview
For this project, I used multiple neural network combinations and tweaks in order to create a binary classifier that could predict if a company that is funded by Alphabet Soup would end up successful. The original neural network approach did not provide a good enough accuracy score, so I tried three different tweaks in an attempt to improve the accuracy score.

## Results

1) What variable(s) are considered the target(s) for your model?
- The variables that I considered ot be the targets for the model were IS_SUCCESSFUL


2) What variable(s) are considered to be the features for your model?

   APPLICATION_TYPE—Alphabet Soup application type

   AFFILIATION—Affiliated sector of industry
   
   CLASSIFICATION—Government organization classification

   ORGANIZATION—Organization type

   STATUS—Active status

   INCOME_AMT—Income classification
   
   USE_CASE—Use case for funding

   SPECIAL_CONSIDERATIONS—Special consideration for application

   ASK_AMT—Funding amount requested.

3) What variable(s) are neither targets nor features, and should be removed from the input data?
- I removed the EIN and the NAME column, for one of the tweaks I put the columns back in.


Compiling, Training, and Evaluating the Model
4) How many neurons, layers, and activation functions did you select for your neural network model, and why?
- For the original model I just used the standard of two layers/activation functions, then for one of my tweaks I added a third one


5) Were you able to achieve the target model performance?
- I was unfortunately not able to achieve the target performance. For my second tweak of removing the NAME column, the first run through gave me a score of 77%, but on a           second run through it fell to 46%


6) What steps did you take to try and increase model performance?
- For my first tweak I chose to add back the two columns that we removed originally, the second tweak I took out only one of the two columns that added back in the first           tweak, and then for the third tweak I added a third hidden layer

Tweak #1

![Score 2](https://user-images.githubusercontent.com/75768098/118362774-94036f00-b556-11eb-8129-4ef4b3b4f523.png)

Tweak #2

![Score 3](https://user-images.githubusercontent.com/75768098/118362777-949c0580-b556-11eb-8311-1f5c8a0cb3cf.png)

Tweak #3

![Score 4](https://user-images.githubusercontent.com/75768098/118362779-9665c900-b556-11eb-9427-4be79689415f.png)


## Summary
- Overall, I was unfortunately not able to meet the goal of creating a model or tweaking an already existing one in order to reach an accuracy score of 75%. My next step for this project would be to add the third layer to my other two tweaks to see if that could get me that accuracy score that I would need. I understood that having more data to process through wouldn't necessarily bring me to the accuracy score that I needed, but I had to try, and now I believe that theres a possiblity that I could improve that with a third layer added. 
