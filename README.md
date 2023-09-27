# athleticchatbot
Created a hypthetical chatbot for retail website Athletic Greens.
Process flow for the project is as follows. 
1. Create a virtual environment, install all libraries. 
2. Create a Intents JSON file. 
3. PyTorch Model and implement the training pipeline. 
4. Save the model and load it. 
Created classes for Neural Net with 2 hidden layers. Defined loss 
function and optimizer for gradient descent. For the computation of 
mean squared error between the input and the target cross entropy 
loss function was used and Adam as optimizer.step() function. 
Activation function used is reLu and softmax last activation function 
to normalize the output of network to a probability distribution.
Since one epoch usually is too big to fed to model at once, hence it 
was divided into 8 batches. 
After the training was complete the final loss was 0.0007.
The chatbot was then upgraded into a GUI for a more challenging and better 
experience.
