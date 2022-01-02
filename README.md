# Brain-Tumor-Detection-ML
A standard neural network classifier with 6 layers/steps classifying MRI scans depending on the presence of a tumor. Data was additionallu augmented.
Achieves a 98% accuracy on the training set and 90% accuracy on the validation set after 32 epochs with the following parameters of the net:
- Same padding
- Convolved with 32 filters
- Batch Normalized
- Relu Activation
- Max Pooled twice
- Adam optimizer
- Loss defined through binary cross entropy

Train set size: 1445
Validation set size: 310
Test set size: 310

Batch size: 32
Epochs: 32 
