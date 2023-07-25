# Pipelines

Column TRansformer-

when we want to apply different feature tranformation to different feature/columns
if dont use tranformer then have to do a lot of hactic work, applying different techs by
isolating them then merging them.

but columns tranformer in skleaern can do that with one line


Pipelines-

chain together multiple steps
in deployment it helps a lot as data comes all things done one after another, output
of one serves as input to another


#pipeline steps
#1- fill missing values to age and embarked
#2- OHE of sex and embarked
#3- scaling
#4- fearue selection, selecting most prominent features out of 10 created
#5- train using decision tree
