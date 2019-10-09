#Assignment 1B



## What are Channels and Kernels

###Kernel

kernel refers to matrix with say some lamda values. hovered over entire usecase image to produce some output image.

kernel as feature extractor,  value lamda selected such that to select/extract a particular set of value/property in original image (say black color in b/w image, or vertical edge in image)

### Channels

each kernel gives one output channel.

channel can be understood as class/set/group (of pixels/object..)  sharing similar type of properties/feature



##Why should we only (well mostly) use 3x3 Kernels?

using lower size kernels, means lower number of parameter's

but 2x2 kernel is not used at it is an even number, thus no median point

so obvious choice was smaller odd kernel that is 3X3 kernel.

thus gpu manufacturing companies accelerated 3x3 kernels operation, thus further increase in use of 3x3 kernels 



#How many times do we need to perform 3x3 convolution operation to reach 1x1 from 199x199 (show calculations)

100 operations

| 199  | x    | 199  |
| ---- | ---- | ---- |
| 197  | x    | 197  |
| 195  | x    | 195  |
| 193  | x    | 193  |
| 191  | x    | 191  |
| 189  | x    | 189  |
| 187  | x    | 187  |
| 185  | x    | 185  |
| 183  | x    | 183  |
| 181  | x    | 181  |
| 179  | x    | 179  |
| 177  | x    | 177  |
| 175  | x    | 175  |
| 173  | x    | 173  |
| 171  | x    | 171  |
| 169  | x    | 169  |
| 167  | x    | 167  |
| 165  | x    | 165  |
| 163  | x    | 163  |
| 161  | x    | 161  |
| 159  | x    | 159  |
| 157  | x    | 157  |
| 155  | x    | 155  |
| 153  | x    | 153  |
| 151  | x    | 151  |
| 149  | x    | 149  |
| 147  | x    | 147  |
| 145  | x    | 145  |
| 143  | x    | 143  |
| 141  | x    | 141  |
| 139  | x    | 139  |
| 137  | x    | 137  |
| 135  | x    | 135  |
| 133  | x    | 133  |
| 131  | x    | 131  |
| 129  | x    | 129  |
| 127  | x    | 127  |
| 125  | x    | 125  |
| 123  | x    | 123  |
| 121  | x    | 121  |
| 119  | x    | 119  |
| 117  | x    | 117  |
| 115  | x    | 115  |
| 113  | x    | 113  |
| 111  | x    | 111  |
| 109  | x    | 109  |
| 107  | x    | 107  |
| 105  | x    | 105  |
| 103  | x    | 103  |
| 101  | x    | 101  |
| 99   | x    | 99   |
| 97   | x    | 97   |
| 95   | x    | 95   |
| 93   | x    | 93   |
| 91   | x    | 91   |
| 89   | x    | 89   |
| 87   | x    | 87   |
| 85   | x    | 85   |
| 83   | x    | 83   |
| 81   | x    | 81   |
| 79   | x    | 79   |
| 77   | x    | 77   |
| 75   | x    | 75   |
| 73   | x    | 73   |
| 71   | x    | 71   |
| 69   | x    | 69   |
| 67   | x    | 67   |
| 65   | x    | 65   |
| 63   | x    | 63   |
| 61   | x    | 61   |
| 59   | x    | 59   |
| 57   | x    | 57   |
| 55   | x    | 55   |
| 53   | x    | 53   |
| 51   | x    | 51   |
| 49   | x    | 49   |
| 47   | x    | 47   |
| 45   | x    | 45   |
| 43   | x    | 43   |
| 41   | x    | 41   |
| 39   | x    | 39   |
| 37   | x    | 37   |
| 35   | x    | 35   |
| 33   | x    | 33   |
| 31   | x    | 31   |
| 29   | x    | 29   |
| 27   | x    | 27   |
| 25   | x    | 25   |
| 23   | x    | 23   |
| 21   | x    | 21   |
| 19   | x    | 19   |
| 17   | x    | 17   |
| 15   | x    | 15   |
| 13   | x    | 13   |
| 11   | x    | 11   |
| 9    | x    | 9    |
| 7    | x    | 7    |
| 5    | x    | 5    |
| 3    | x    | 3    |
| 1    | x    | 1    |





 

