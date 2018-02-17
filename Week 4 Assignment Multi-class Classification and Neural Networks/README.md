We need to write code in three files:-
    1. nnCostfunction.m
    2. sigmoidGradient.m
    3. predict.m

We have total 5000 examples(training set). We can say we have 5000 images of size 20px * 20px each. Each image is [20 * 20] grid matrix.
We are pretty familiar with this from Week-3 Assignment.
We will unroll each image into a vector so each image vector is having size of [400 * 1].
We will have "X" matrix of size [5000 * 400] considering all images.

We are given label(y) vector which is obviously having size = [5000 * 1]

We can now read through ex4.pdf file and ex4.m to stear through the assignment.
