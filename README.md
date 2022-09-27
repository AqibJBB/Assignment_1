A program to compute pair-wise Euclean distances (i.e.,  𝐿2  norm) between all vectors in a set of data samples:
X={𝐱1,𝐱2,⋯,𝐱𝑁}
 
where each  𝐱𝑖∈ℝ𝑑 . Store all these pair-wise distances in a symmetric marix  𝐄∈ℝ𝑁×𝑁 , where each element  𝑒𝑖𝑗  indicates the distance between  𝐱𝑖  and  𝐱𝑗 .

1. Implementation using regular loop-based programing style.

2. Implementation using vectorization.

3. Generating some random samples, comparing the above two implementations in terms of running speed.
