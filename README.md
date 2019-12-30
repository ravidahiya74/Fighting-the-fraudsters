# Why Fraud Detection

For years, fraud has been a major issue in sectors like banking, medical, insurance, and many others. Due to the increase in online transactions through different payment options, such as credit/debit cards, PhonePe, Gpay, Paytm, etc., fraudulent activities have also increased. Moreover, fraudsters or criminals have become very skilled in finding escapes so that they can loot more. Since no system is perfect and there is always a loophole them, it has become a challenging task to make a secure system for authentication and preventing customers from fraud. So, Fraud detection algorithms are very useful for preventing frauds.

Here comes Machine Learning which can be used for creating a fraud detection algorithm that helps in solving these real-world problems.
<img src="Images/fraud_cartoon.png">

# Different Approaches

### Rule-based Approach or Traditional Approach in Fraud Detection Algorithms

In the rule-based approach, the algorithms are written by fraud analysts. They are based on strict rules. If any changes have to be made for detecting a new fraud, then they are done manually either by making those changes in the already existing algorithms or by creating new algorithms. In this approach, with the increase in the number of customers and the data, human effort also increases. So, the rule-based approach is time-consuming and costly. Another drawback of this approach is that it is more likely to have false positives. This is an error condition where an output of a test specifies the existence of a particular condition that does not even exist. The output of a transaction depends upon the rules and guidelines made for training the algorithm for non-fraudulent transactions. So, for a fixed risk threshold, if a transaction is rejected where it should not be, it will generate a condition of high rates of false positives. This false-positive condition will result in losing genuine customers.

### ML-based Fraud Detection Algorithms

In the rule-based approach, the algorithms cannot recognize the hidden patterns. Since they are based on strict rules, they cannot predict fraud by going beyond these rules. But in real world, fraudsters are very skilled and can adopt new techniques every time to commit a crime. Therefore, there is a need for a system that can analyze patterns in data and predict and respond to new situations for which it is not trained or explicitly programmed.

Hence, we use Machine Learning for detecting fraud. Here, a machine tries to learn by itself and becomes better by experience. Also, it is an efficient way of detecting fraud because of its fast computing. It does not even require the guidance of a fraud analyst. It helps in reducing false positives for transactions as the patterns are detected by an automated system for streaming transactions that are in huge volume.

# Unsupervised Learning Used in Fraud Detection Algorithm
Unsupervised learning models are built to detect unusual behavior in transactions which is not detected previously. Unsupervised learning models involve self-learning that helps in finding hidden patterns in transactions. In this type, the model tries to learn by itself, analyzes the available data, and tries to find the similarities and dissimilarities between the occurrences of transactions. This helps in detecting fraudulent activities.

# Self Organizing Maps (SOM)

Core purpose of SOM is to reduce dimentionality. The example below shows a complex data set consisting of a massive amount of columns and dimensions and demonstrates how that data set's dimensionality can be reduced.
<img src="Images/som.png">

So, instead of having to deal with hundreds of rows and columns (because who would want that!), the data is processed into a simplified map; that's what we call a self-organizing map. The map provides you with a two-dimensional representation of the exact same data set; one that is easier to read.

# Data

Data available in the transactions.csv is an actual transaction file from a bank.
We don't need the list of fraudsters to train the model, as SOM is an unsupervised Deep Learning technique.

# Result

We were able to identify 104 customers whose transaction patterns are different from others. These users and their transactions can be sent to relevant department for further investigation.