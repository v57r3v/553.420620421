java c
553.420/620/421 Intro. to Probability 
Assignment #09 
Due Friday, April 19 11:59PM as a PDF upload to Canvas Gradescope. 
9.1. Suppose that X|Y = y ∼ Poisson(y) and Y ∼ exp(1).
(a) From the information given, write down the joint probability distribution. Notice here we have a mixture of different types of rvs.
(b) Derive the marginal distribution of X. Show that it has a geometric( 12) distribution.
(c) Identify the conditional pdf of Y given X = x if you can.
Remark: What changes in this problem had Y ∼ exp(a) instead for some fixed constant a > 0?
9.2. Fred and Greg are each rolling a fair 6-sided die repeatedly. They each stop rolling the moment they get a 6. If the total number of rolls it takes between them for this to happen is 14, what’s the probability it took Fred at least twice as many rolls as Greg to see his first 6?
9.3. The delayed unit exponential is the (continuous) distribution of a random variable with pdf e−(x−y)for x > y. The value y > 0 in this pdf is the “delay”. Suppose X is a delayed unit exponential but whose delay is random, say, the delay Y is Gamma(α, 1).
(a) Derive the (unconditional) pdf of X. Did you get an interesting answer?
(b) Now find the conditional pdf of Y given X = x.
(c) Assume α = 3. Compute P(Y 
9.4. Suppose X1, X2, X3, . . . , Xn represent the lifetimes of n components each of which independently has exp(λ) distribution. If Yi (for i = 1, 2, . . . , n) represent the order statistics. Determine the distribution of the lifetime of the first component to die (i.e., Y1 = min{X1, . . . , Xn}).
9.5 Consider the situation in problem 9.5 above except instead of X1, x2, . . . , Xn being iid, they are just independent; that is, assume X1, X2, . . . , Xn are independent, where, for each i = 1, 2, . . . , n, Xn ∼ Exp(λi) (and we allow the λi’s to be any positive numbers not necessarily all the same value). Show that Y1 = min{X1, X2, . . . , Xn}代 写553.420/620/421 Intro. to Probability Assignment #09C/C++
代做程序编程语言 follows another exponential distribution and identify its parameter.
Remark. Moral of the story: the minimum of independent exponentials is exponential.
9.6. Suppose X1, X2, X3 ∼ iid Exp(1).
(a) Write down the joint pdf of Y1, Y2, Y3.
(b) In class we showed that Yj has the pdf (n j−1, 1,n−j)(F(y))j−1f(y)(1 − F(y))n−j, where F(y) is the cdf of the underlying X-distribution. Write down the marginal pdf of Y2 in our situation of n = 3 and exp(1) distribution.
(c) Re-derive the pdf of Y2 from this joint pdf in part (a) by appropriately integrating out the variables y1 and y3 once a value of 0 
9.7. (continued from problem 9.6) We still have n = 3 iid Exp(1) rvs. and their order statistics Y1, Y2, Y3.
(a) Construct the joint pdf of the spacings: W1 = Y1, W2 = Y2 − Y1, W3 = Y3 − Y2 using the method of Jacobians. Be sure to get the domain of this pdf correct. Do you notice anything interesting about what this pdf says about the collection W1, W2, W3?
(b)∗ Y1 
(c) Compute the mean length of the shortest piece.
∗Hint: the shortest piece W = min{W1, W2, W3}, use the CDF method P(W ≤ w) = 1 − P(W > x).
9.8. Let X1, X2, X3 be independent unif(0,1) and let Y1, Y2, Y3 denote their order statistics.
(a) Find P(X3 > X2 > X1) and P(Y3 > Y2 > Y1).
(b) Write down the joint pdf of Y1, Y2, Y3, then from this joint pdf compute the (bivariate) marginal of Y1, Y3.
(c) Use the bivariate marginal in part (b) to compute P(Y3 > 2Y1).
(d) The sample range in this case is the rv R = Y3 − Y1. Compute E(R).
9.9. Suppose that Y1, Y2, . . . , Yn are the ordered statistics of X1, X2, . . . , Xn ∼ iid uniform(0, 1). Suppose 0 
(a) P(Y1 > a, Yn 
(b) P(Y1 > a, Yn > b)
(c) P(Y1 
(d) P(Y1  b)
(e) P(Yk  b) for 1 ≤ k ≤ n − 1
(f) P(Yk  b) for 1 ≤ k ≤ n − 2.
Hint: For parts (a,b,c,d), it might be helpful to let A = (Y1 > a) and B = (Yn 





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
