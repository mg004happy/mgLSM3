This code implements a fully connected feedforward neural network from scratch in NumPy for binary classification using the sigmoid activation at the output layer and ReLU activations in hidden layers. Here's a short description:

🔍 Summary
Dataset: Synthetic classification data using make_classification() (assumed).

Preprocessing:

Standardizes input features (zero mean, unit variance).

Reshapes target (y_train) to match output shape.

Architecture:

3 layers: Input → Hidden1 → Hidden2 → Output

Hidden layers: ReLU

Output layer: Sigmoid (for binary classification)

Loss Function: Binary Cross-Entropy

Training:

Forward pass to compute predictions.

Backward pass for gradient calculation.

Gradient descent for weight updates.

Evaluation: Calculates training accuracy.

Visualization: Plots the training loss over epochs.

⚙️ Key Hyperparameters
Hidden layer sizes: 50

Learning rate: 0.1

Epochs: 50000 (a large number for good convergence)

Output layer: 1 neuron with Sigmoid

📈 Output
Final training loss and accuracy printed.

Training loss curve plotted using matplotlib.
