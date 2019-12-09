# iris-dataset
 Prediciting the class of the iris flower based on available attributes.

I was curious to see whether the implicit conversion of the dependent varible by sklearn would work and therefore do away with the need for encoding the dependent variable, it ended up  working just fine, however, I will create another solution with the variables encoded(using either Label Encoder or OneHotEncoder).
- To find out? When is this implicit conversion not enough, when would it be necessary to encode the dependent  variable explicitly?
- The model predicted the test dataset 100% accurately, not sure if it's that good or it's overfitted, will look for solutions from others and see if they have similar results (After check: Apparently a perfect score is quite common with this database)
