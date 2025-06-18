# Handwritten_Digit_Recognition

This work uses the PyTorch library to build a BPNN consisting of 4 layers:
- Input layer: 28x28=784 neurons, one for each pixel
- 1st Hidden Layer: 128 neurons with RuLU activation
- 2nd Hidden Layer: 64 neurons with RuLU activation
- Output Layer: 10 neurons for 10 possible digits (0-9) with logSoftmax activation


This neural network aims to recognize handwritten digits. The datasets used to train and test the model come from the MNIST database. The Stochastic Gradient Decent (SGD) optimizer is used to train the model, with Negative Log Likelihood loss (NLLloss) as the training metric. The model is set to be trained for 60 epochs with an early stop option. As an early stop, it is chosen that if the loss is not improved by 0.5 compared to the previous loss, then stop training to avoid overfitting. The model reached an accuracy of 97.68%. 

## Repository Content

2. **`handwritten_digit_recognition.ipynb`**  
   A Jupyter Notebook containing the implementation, training, and validation of the model in recognizing handwritten digits.
