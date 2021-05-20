# Training Tutorial

- The training data should be the stacked raw RF channel data, the size of input training data cube should be: 

  **N×R×S×D**

  Where **N** is the amount of training data, **R** is the number of active receiving elements, **S** is the number of scanlines, **D** is the number of samples in depth dimension.

For example, if you are traning the network with **N=1000** RF channel data, collected from transducer with **R=128** receiving elements and **S=64** scanlines, the size of input training data cube should be: **1000×128×64×256**, as the depth dimension is always resized to **D=256** samples.

<br>

- The target label data should be the corresponding stacked B-mode images, the size of target data cube should be: 

  **N×1×S×D**

  Same as the training data, **N** is the amount of training data, **S** is the number of scanlines, **D** is the number of samples in depth dimension.

For example, for the training data mentioned above, the size of target data cube should be: **1000×1×64×256**.

<br>

- Then you can replace the `data` and `target` variables in the codes with your training and target data to train the networks.


