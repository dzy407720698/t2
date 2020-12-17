# CommonsenseQA

Method
In this project, by training modelson a set of seed QA data sets of different formats,we construct a single pre-trained QA model, takingnatural text as input without using format-specificprefixes.  Without using format-specific prefixes,we takes natural text as an input. we use Bert andRoberta to predict the results for a given question,and find BERT has the best accuracy.
Hyper-parameters Setting
Learning Rate: 1e-5
Batch Size: 6
Epoch: 10
