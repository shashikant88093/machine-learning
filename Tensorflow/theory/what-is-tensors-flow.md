# What is tensorflow?

- TensorFlow make easy to create machine learning models that can run on any environment, from mobile devices to large-scale distributed systems.
- It provides a flexible architecture that allows developers to deploy computation across various platforms, such as CPUs, GPUs, and TPUs (Tensor Processing Units).

## Types of Tensors ?
- **Variable Tensors**: These are tensors that can be modified during the execution of a program. They are often used to represent model parameters that need to be updated during training.
- **Constant Tensors**: These tensors have fixed values and cannot be changed. They are typically used for inputs or parameters that do not change during the execution of a program.
- **Placeholder Tensors**: These are used to feed data into a TensorFlow graph. They allow you to define a tensor that will be filled with data later, typically during the execution of a session.
- **Sparse Tensors**: These tensors are used to represent data that is mostly empty or contains a lot of zeros. They are efficient for storing and processing large datasets with many zero values.
- **String Tensors**: These tensors are used to represent text data. They can hold strings of varying lengths and are useful for natural language processing tasks.
- **Ragged Tensors**: These tensors can represent data with varying dimensions, such as lists of lists where each inner list can have a different length. They are useful for handling irregular data structures.
- **Tensor Arrays**: These are dynamic arrays that can hold tensors of varying sizes. They are useful for scenarios where the size of the data is not known beforehand, such as in recurrent neural networks (RNNs).
- **Indexed Tensors**: These tensors allow you to access specific elements or slices of a tensor using indices. They are useful for operations that require selective access to tensor elements.
- **Composite Tensors**: These tensors are made up of multiple tensors combined together. They can represent complex data structures, such as images with multiple channels or sequences of varying lengths.