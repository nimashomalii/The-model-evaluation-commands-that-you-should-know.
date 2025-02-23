# The-model-evaluation-commands-that-you-should-know.
I will introduce three very useful functions for evaluating the performance of a model, which will definitely be helpful for you.

Let's assume you've built an AI model that takes an input and outputs either zero or one, meaning it needs to classify the data into two classes.

I’ll assume that you’ve trained your model and provided some data as input, and you've obtained a vector of zeros and ones, which is the result of the model's prediction on the input data.

Also, we have a vector of labels.

So, we have two vectors: one for the true labels of the data and one for the predictions made by the model on those data. These two vectors have the same length.
Since I haven't built a model yet, on which I want to explain and evaluate the results, I will manually create the two vectors I mentioned.

That is, I will create two vectors of the same length (for example, I made them of length 1000), where each vector contains only zeros and ones.

Now, I want to perform the evaluations.


