# High Throughput Training of Deep Surrogates from Large Ensemble Runs

**Journal/Conference**: The International Conference for High Performance Computing, Networking, Storage and Analysis (SC '23)

[Link to the paper](https://doi.org/10.1145/3581784.3607083)

## Summary
The paper named *High Throughput Training of Deep Surrogates from Large Ensemble Runs* presents an open-source software designed to enhance online training of deep surrogates. It provides solutions that encompass the problem of dealing with big data in the case when these data originate from computationally demanding numerical calculations. The authors are able to control memory and I/O issues by the use of multi-level parallelism while at the same time training the neural networks.

Key contributions include:
- An approach of **multi-level parallelism** that incorporates ensemble simulations, the distributed data parallel training, and fault tolerance.
- This brought about the **training reservoir** that would help in managing the data streaming and the reduction of biases in order to achieve maximum, diverse batch training for GPIs.

Some experiments were performed to demonstrate that this framework could be used to train a surrogate model with 4 * 8TB data in less than 2 hours, with 47% higher accuracy, 13 times higher throughput than the offline training paradigm.

## Key Points:
- **Online training** also enables a deep surrogate model to be trained in parallel with data generation and there is no need for a huge storage and I/O operations.
- Utilizing **parallelism** and analyze in-transit data eliminates storage containers’ constraints and speeds up the training.
- **Training reservoirs** allows to achieve high throughput of the training batches and always keep GPU loaded.

The described approach seems to provide significant enhancements in the ability of employing machine learning techniques to large scale scientific simulations.
