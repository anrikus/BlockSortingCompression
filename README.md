### Block Sorting Compression Algorithm
The project is an implementation of block sorting lossless compression algorithm based on `https://ieeexplore.ieee.org/document/582009`.

It implements a novel approach to pre-process the text before implementation of move to forward encoding followed by Hoffman encoding.

An algorithm without the novel encoding is provided in the second notebook to aid in performace comparison.

The novel encoding scheme is able to achieve a bits per character rate of `3.1` as compared to `4.1` for the regular algorithm.
