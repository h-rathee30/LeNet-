# LeNet-
One of the oldest CNN architecture.
Structure:-

Conv2D - filter(6), kernel_size(5,5)
MaxPool2D(2,2)
Conv2D - filters(16), kernel_size(5,5)
MaxPool2D(2,2)
Conv2D - filters(120), kernel_size(5,5)

this last layer output_size is 84
so we use 2 Dense Layer

Dense- units(84)
Dense- units(43) {output layer}
