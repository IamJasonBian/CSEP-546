1. [2 points] (Bayes Rule, from Murphy exercise 2.4.) After your yearly checkup, the doctor has bad news and
good news. The bad news is that you tested positive for a serious disease, and that the test is 99% accurate
(i.e., the probability of testing positive given that you have the disease is 0.99, as is the probability of testing
negative given that you dont have the disease). The good news is that this is a rare disease, striking only one
in 10,000 people. What are the chances that you actually have the disease? (Show your calculations as well as
giving the final result.)

            p(x = 1 | y = 1) = 0.99
            p(x = 1 | y = 0) = 0.99
            
            p(y = 1) = 0.0001
            y = 1 is the event I have the disease
            x = 1 is the event of testing positive

            Following Bays Rule:

![image](https://user-images.githubusercontent.com/16582383/136335845-7d9954d8-20f9-4363-8261-ac7af3784b94.png)
![image](https://user-images.githubusercontent.com/16582383/136337413-036e8726-4242-4610-a2e7-d874b200ba0d.png)


2. For any two random variables X, Y the covariance is defined as Cov(X, Y ) = E[(X − E[X])(Y − E[Y ])]. You
may assume X and Y take on a discrete values if you find that is easier to work with.

   a. [1 points] If E[Y |X] = X show that Cov(X, Y ) = E[(X − E[X])^2].
   
   b. [1 points] If X, Y are independent show that Cov(X, Y ) = 0.






