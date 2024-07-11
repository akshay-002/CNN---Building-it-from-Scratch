# CNN-Building-it-from-Scratch
![CNN Meme](images/Convolution_schematic.gif)

https://github.com/akshay-002/CNN---Building-it-from-Scratch/blob/main/README.md
This project involves constructing a Convolutional Neural Network (CNN) from the ground up using Python and NumPy. It covers essential operations like convolution, pooling, and their forward and backward passes.

## Implemented Functions

### Padding:
- **zero_pad(X, pad)**: Pads the input images with zeros.

### Convolution Operations:
- **conv_single_step(a_slice_prev, W, b)**: Applies one filter to a single slice of the input.
- **conv_forward(A_prev, W, b, hparameters)**: Forward pass of the convolution layer.

### Pooling Operations:
- **pool_forward(A_prev, hparameters, mode="max")**: Forward pass of the pooling layer.

### Backward Pass:
- **conv_backward(dZ, cache)**: Backward pass for the convolution layer.
- **pool_backward(dA, cache, mode="max")**: Backward pass for the pooling layer.
- **create_mask_from_window(x)**: Creates a mask for max pooling.
- **distribute_value(dz, shape)**: Distributes value across a matrix for average pooling.

![CNN Meme](images/matrix.png)

## Examples

The repository includes example scripts demonstrating the usage of the implemented functions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
