# Easy Guide to Credit Risk Analysis Using Logistic Regression
## What's This Project About?
We're trying to make a program that can tell us if a loan is risky or not. We call this "credit risk analysis." We're using a type of machine learning called logistic regression to help us do this.

How's The Project Broken Down?
We've split our project into several steps:

Step 1: Gather and Split Our Data
First, we read our loan data from a file named lending_data.csv. We look at the loan_status column to see if a loan is risky or not (this is our "target"). The rest of the information in the other columns helps us predict our target (we call these "features").

We also check if we have equal numbers of risky and non-risky loans. If they're not equal, that's okay, we have a way to deal with this later.

After that, we split our data into two parts: one for training our program (so it can learn) and one for testing it (to see how well it learned).

Step 2: Teach Our Program with Original Data
Next, we use our training data to teach our program how to predict loan risk. After it's learned, we use our test data to see how well it does.

We also calculate the program's "accuracy" (how often it's right), make a "confusion matrix" (a table that helps us see where the program's making mistakes), and create a "classification report" (this gives us more detailed information about the program's performance).

Step 3: Balancing Our Data and Teaching Our Program Again
In this step, we use a technique called "oversampling" to balance our data. This just means we create extra data for our program to learn from if we don't have equal numbers of risky and non-risky loans.

We use this balanced data to teach our program again and then see how well it does this time.

Wrapping Up
Finally, we compare the performance of our program when it's learned from our original data and from our balanced data. This helps us understand how well logistic regression can predict loan risk and how important balanced data is for our program's performance.




