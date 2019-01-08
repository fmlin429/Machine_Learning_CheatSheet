#### Batch Epocod Concepts and Examples:
Sample dataset size = 200
Batch size = 5 (The model weights will be updated after each batch of five samples)
Batch Number = 200/5 = 40 

epochs = 1000
Every epoch will run all 40 batches (40 updates to the model)

With 1,000 epochs, the model will be exposed to or pass through the whole dataset 1,000 times. That is a total of 40,000 batches during the entire training process.

#### Seeding random number generators
Example: np.random.seed(42)

we will explicitly seed the random number generator (usually seeded with a number representing the date/time to avoid repeats) to show that we get the same random numbers. If we choose a different seed, we get totally different random numbers. If you are writing unit tests (which we will describe tomorrow when we do test driven development), it is often useful to seed the random number generator to get reproducible results.
