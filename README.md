**Apriori Algorithm**
This algorithm was first presented in 1994 by Rakesh Agrawal and Ramakrishnan Srikant. Apriori algorithm is based on the principle that if a set of items is frequent, then all its subsets are also frequent. This means that if {10,1} is frequent then {0} and {1} are also frequent. Conversely, this rule is also true, that is, if a set of items is not frequent, its subsets are also not frequent. According to the above description, to find a set of dependency rules, you must first find the set of frequent items.
**How does Apriori work?**
To create rules of communication between elements or cases, the algorithm considers 3 important factors, which are: support, confidence, and lift.
