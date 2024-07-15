#### Things I learned

- For normal models (not deep learning) the process goes as follows 
    - Get the data
    - Preprocess the data (clean, normalize, etc)
        - For values that are non-numerical we need to encode them
            - One hot encoding
            - Label encoding
        - For values that are numerical we need to normalize them
            - MinMaxScaler : scales the data between 0 and 1 (divide by the max value)
            - StandardScaler : scales the data to have a mean of 0 and a standard deviation of 1
            - use log: to make the data less skewed
    - Train the model
    - Test the model
    - Evaluate the model
    - Deploy the model

- For deep learning models the process goes as follows (So far only CNN and RNN) it is similar except we need to create the model architecture
- Relu -> Rectified Linear Unit, max(0, x)
- Sigmoid -> 0 to 1
- we use batch_size to reduce memory usage

#### Blockers
- How to create the model architecture
- Layers and how they work (Conv2D, MaxPooling2D, Flatten, Dense)
- dimensions and shape of tensors
    - how to reshape tensors
    - why we need to reshape tensors
    - how to decide the shape of the input tensor
- what is a tensor?
- tensor functional
- which error function to use and why
- which optimizer to use and why
- softmax
- how to feature engineer 
- what does accuracy, loss, and validation accuracy mean and how to interpret them

