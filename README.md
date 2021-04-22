# efpp-single-minded-limited-supply
Instances for the Envy Free Pricing Problem with Single-Minded Consumers and Limited Supply.

We have the following parameters:
n = number of products
m = number of clients  
d = density of each bundle. d = number of products in each bundle divided by n.
t = percentage of product supply. The supply of each product is the number of units product demands in the instance multiplied by t.

In these instances, we have n in {25,50,75}, m in {25,50,100,150}, d in {0.1, 0.2, 0.4} and t in {0.5, 0.7, 0.9}. Budgets are created randomly uniform between 1 and 1000. For each value of n, m, d and t, we create 10 random instances.

These instances are generated from the set of instances available at: https://github.com/vbucarey/smbpp.
