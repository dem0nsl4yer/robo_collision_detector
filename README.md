# robo_collision_detector
Robot collision detector built on pygame with CNN Pytorch implementation 

This project involves training a robot using a feed-forward neural network for action conditioning. The training process includes data loading, model training, and result visualization.

## Dependencies

- `Data_Loaders`: Provides data loaders for training and testing the robot model.
- `Networks`: Contains the implementation of the action-conditioned feed-forward neural network.
- `torch`: PyTorch library for neural network training and evaluation.
- `torch.nn`: Provides various neural network modules and loss functions.
- `matplotlib.pyplot`: Plotting library for visualizations.
- `torch.optim`: Optimization algorithms for updating model parameters.
- `numpy`: Numerical computing library.

## Training the Model

The `train_model` function trains the robot model. It takes the number of epochs as an input parameter and performs the following steps:

1. Initialize data loaders, model, optimizer, and loss function.
2. Iterate over the specified number of epochs and perform model training.
3. Calculate the training loss for each epoch and store it in `training_losses`.
4. Print the test loss and accuracy for every 10th epoch.
5. Save the trained model to a file.
6. Plot the training and test loss curves.

## Main Execution

The `train_model` function is called from the `__main__` block, where the number of epochs is specified. This block serves as the entry point for executing the training process.

To run the project, ensure that all dependencies are installed and execute the script. Adjust the number of epochs as needed.
    
    
[![pythonbadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
