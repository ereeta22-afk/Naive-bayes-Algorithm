# Naive-bayes-Algorithm

Naïve Bayes is a supervised machine learning classification algorithm that uses Bayes Theorem to predict the class with the highest probability.

Bayes Theorem:

P(A∣B)=P(B)P(B∣A)P(A)
	​
Types of Naïve Bayes

1. Gaussian Naïve Bayes:
              Used for continuous numerical data.
Formula
<img width="297" height="100" alt="image" src="https://github.com/user-attachments/assets/77031658-a1fd-46a0-96f1-b7ab89250b1e" />
Example
Height,Weight,Age,Temperature

2. Multinomial Naïve Bayes
              Used for count or frequency data.
Formula
<img width="643" height="61" alt="image" src="https://github.com/user-attachments/assets/f5ddef02-c463-49f5-b07e-0ccf80eca8e6" />

Example
Free = 3
Win = 2
Offer = 1

Word counts in emails.

3. Bernoulli Naïve Bayes
             Used for binary data (0 or 1).

Formula
             P(Class∣X)=P(Class)×P(Feature∣Class)
Example
Fever = 1
Cough = 0
Headache = 1
