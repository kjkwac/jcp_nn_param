# jcp_nn_param: optimized parameters for DEA and neural networks

dea_params.dat
    Coefficients of the polynomial functions optimized by the differential evolution algorithm.
    Each row consists of 'sequantial number', 'order', 'NMA sites C1(1), C(2), O(3), N(4), H(5), C2(6))', 'water sites (O(1), H(2))', 'optimized coefficient'.

The following is the weight parameters of neural networks. 
The files should be read in by using the load_weights() method. For example,
after defining the architecture of the network 'model', invoke
model.load_weights('weights_20_20_1_relu_s1_ACSF_I.h5')

weights_20_20_1_relu_s1_ACSF_I.h5
    FFNN parameters
    Interaction sites on NMA = Carbonyl C 
    Interaction sites on water = O 
    Descriptor = ACSF-I symmetry functions
    Network architecture = 20-20-1
    Activation function = ReLU

weights_16_16_1_relu_s1_ACSF_II.h5
    FFNN parameters
    Interaction sites on NMA = Carbonyl C 
    Interaction sites on water = O 
    Descriptor = ACSF-II symmetry functions
    Network architecture = 16-16-1
    Activation function = ReLU

weights_50_50_1_relu_oh_ACSF_I.h5
    FFNN parameters
    Interaction sites on NMA = Carbonyl C 
    Interaction sites on water = O, H 
    Descriptor = ACSF-I symmetry functions
    Network architecture = 50-50-1
    Activation function = ReLU

weights_100_100_1_relu_oh2s_ACSF_I.h5
    FFNN parameters
    Interaction sites on NMA = Carbonyl C, O
    Interaction sites on water = O, H 
    Descriptor = ACSF-I symmetry functions
    Network architecture = 100-100-1
    Activation function = ReLU

weights_200_200_1_relu_oh4s_ACSF_I.h5
    FFNN parameters
    Interaction sites on NMA = C, O, N, H
    Interaction sites on water = O, H 
    Descriptor = ACSF-I symmetry functions
    Network architecture = 200-200-1
    Activation function = ReLU

weights_300_300_1_relu_oh6s_ACSF_I.h5
    FFNN parameters
    Interaction sites on NMA = C1, C, O, N, H, C2
    Interaction sites on water = O, H 
    Descriptor = ACSF-I symmetry functions
    Network architecture = 300-300-1
    Activation function = ReLU

weights_40_40_1_relu_oh_ACSF_II.h5
    FFNN parameters
    Interaction sites on NMA = Carbonyl C
    Interaction sites on water = O, H 
    Descriptor = ACSF-I symmetry functions
    Network architecture = 40-40-1
    Activation function = ReLU

weights_80_80_1_relu_oh2s_ACSF_II.h5
    FFNN parameters
    Interaction sites on NMA = Carbonyl C, O
    Interaction sites on water = O, H 
    Descriptor = ACSF-I symmetry functions
    Network architecture = 80-80-1
    Activation function = ReLU

weights_160_160_1_relu_oh4s_ACSF_II.h5
    FFNN parameters
    Interaction sites on NMA = C, O, N, H
    Interaction sites on water = O, H 
    Descriptor = ACSF-I symmetry functions
    Network architecture = 160-160-1
    Activation function = ReLU

weights_240_240_1_relu_oh6s_ACSF_II.h5
    FFNN parameters
    Interaction sites on NMA = C1, C, O, N, H, C2
    Interaction sites on water = O, H 
    Descriptor = ACSF-I symmetry functions
    Network architecture = 240-240-1
    Activation function = ReLU

ghts_best.h5 weights_168_168_1_relu_poly.h5
    FFNN parameters
    Interaction sites on NMA = C1, C, O, N, H, C2
    Interaction sites on water = O, H 
    Descriptor = terms of 14-order polynomial function
    Network architecture = 168-168-1
    Activation function = ReLU

weights_conv.h5
    CNN parameters
    Interaction sites on NMA = C1, C, O, N, H, C2
    Interaction sites on water = O, H 
    Descriptor = terms of 14-order polynomial function
    CNN architecture = Conv2D(32,(3,3)), MaxPooling2D((2,2)), Conv2D(64,(3,3))
    FFNN architecture = 768-64-1
    Activation function = ReLU







