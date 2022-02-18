# CLV-calculated-for-each-client

## Overview
Calculate the monetary value of each customer throughout his life, understanding that his life is the time he spends as a customer in a given company.


## Forecast of future transactions assumptions
<strong>Assumption 1: </strong> While a client is active, the number of transactions made by the client follows a Poisson distribution with a ratio λ (λ is the number of transactions expected in a given time interval)

<strong>Assumption 2: </strong> The heterogeneity in the transaction ratio (λ) follows a Gamma distribution. This means that each client has its own probability in each number of transactions and it is independent from that of the other clients.

<strong>Assumption 3: </strong> After each transaction the customer will leave the company with probability p and will remain alive with probability (1-p). The moment in which the client abandons is distributed among the transactions according to a Geometric distribution.

<strong>Assumption 4: </strong> The heterogeneity in the probability of dying/dropping out (p) follows a Beta distribution. This means that each client has its own probability of being alive and it is independent from that of the other clients.

<strong>Assumption 5: </strong> The probability of dying/abandoning (p) and the transaction ratio (λ) vary independently among clients.

## Prediction of the average monetary value of future transactions assumptions

<strong>Assumption 1: </strong> The monetary value of a given future transaction varies randomly around the average value of past transactions.

<strong>Assumption 2: </strong> The average value of transactions varies between clients but is maintained over time for the same client.

<strong>Assumption 3: </strong> The distribution of the average value of transactions between clients is independent of the transaction process. There should be no correlation between frequency and monetary value.

<br><br><br>
