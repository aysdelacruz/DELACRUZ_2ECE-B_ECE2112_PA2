**Programming Assignment 2**

_Problem 1 – Normalizing a 5x5 Random Array_

I knew I had to use numpy for this since it’s all about arrays.
First, I created a 5x5 array filled with random numbers between 0 and 1 using np.random.random((5, 5)).
I printed it out to see the original matrix.

Then I had to normalize it. I remembered the formula:
normalized = (X - mean) / std

So I calculated the mean with X.mean() and the standard deviation with X.std().
After that, I applied the formula and stored the result in X_normalized.

Finally, I saved the normalized array into a file called X_normalized.npy.
To wrap it up, I printed both the original and the normalized arrays to check if it worked.


_Problem 2 – Squares of Numbers and Divisible by 3_

For this problem, I again used numpy.
I started by generating the squares of the first 100 positive integers with np.arange(1, 101) ** 2.

Then, I reshaped the result into a 10x10 array using .reshape(10, 10).
I printed it out to confirm the shape and values looked right.

Next, I needed to find the numbers divisible by 3.
I used boolean indexing with (A % 3 == 0) to filter the array and keep only those values.
The result was saved into div_by_3.npy.

Lastly, I printed both the 10x10 array and the divisible-by-3 elements to make sure the output matched what I expected.
