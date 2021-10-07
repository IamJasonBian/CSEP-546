## CSEP 546 | Jason Bian | jasonb73

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
            

      <img src="https://user-images.githubusercontent.com/16582383/136339299-34fb8b8a-c788-480d-98cb-16287044c6df.png" height="150" />



2. For any two random variables X, Y the covariance is defined as Cov(X, Y ) = E[(X − E[X])(Y − E[Y ])]. You
may assume X and Y take on a discrete values if you find that is easier to work with.

   a. [1 points] If E[Y |X] = X show that Cov(X, Y ) = E[(X − E[X])^2].
   
   https://math.stackexchange.com/questions/1479316/show-that-covx-y-covx-eyx
   
   b. [1 points] If X, Y are independent show that Cov(X, Y ) = 0.






