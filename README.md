# Gender-Recognition-and-Age-Estimator

#To run this we have to download weights.18-4.06 .hdf5 file which is trained url ,either it would show error if we don't download the file#

#then put these two given file in the folder pretrained_models in the same folder 

1.weights.18-4.06.hdf5 file

2.haarcascade_frontalface_alt.xml file

I propose an implement a general
convolutional neural network (CNN) building framework for
designing real-time CNNs. We validate our models by creating
a real-time vision system which accomplishes the tasks of
face detection, gender classification and emotion classification
simultaneously in one blended step using our proposed CNN
architecture.

Models were designed with the idea of creating the best accuracy
over number of parameters ratio. Reducing the number of
parameters help us overcoming two important problems. First,
the use of small CNNs alleviate us from slow performances
in hardware-constrained systems such robot platforms. And
second, the reduction of parameters provides a better generalization.

I have proposed and tested a general building designs
for creating real-time CNNs. My proposed architectures have
been systematically built in order to reduce the amount of
parameters. We began by eliminating completely the fully
connected layers and by reducing the amount of parameters
in the remaining convolutional layers via depth-wise separable
convolutions. I have shown that our proposed models can
be stacked for multi-class classifications while maintaining
real-time inferences. Specifically, we have developed a vision
system that performs face detection, gender classification
and emotion classification in a single integrated module. We
have achieved human-level performance in our classifications
tasks using a single CNN that leverages modern architecture
constructs.

                      #REFERENCES#

Franc¸ois Chollet. Xception: Deep learning with depthwise separable
convolutions. CoRR, abs/1610.02357, 2016.


Andrew G. Howard et al. Mobilenets: Efficient convolutional neural
networks for mobile vision applications. CoRR, abs/1704.04861, 2017.


Dario Amodei et al. Deep speech 2: End-to-end speech recognition in
english and mandarin. CoRR, abs/1512.02595, 2015.
