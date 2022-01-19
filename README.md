# 5557_FirstGrade

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/5557_FirstGrade/blob/main/5557_pro.PNG)

## What Algorithm should I use?

dynamic programming

## What was the key point and the hard part?

Similar to guitarist that I solved.

Make 2d dp array. Row will be the number's location and col will be the result of the equation.

Make 1 for the first number location. For example in the example in the problem, we can see that first number is 8, so dp[0][8] = 1

After that lookin at the previouse equation's result(dp[i-1]) , if it is no zero(if we can make that number in the previouse step) , check the number range(0~20) , then add it to the possible location(dp[i][here]).

At the end , we have to make the last number , so dp[n-2][lastnumber] will be the possible case.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
