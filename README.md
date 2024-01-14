**Human Activity Recognition using ConvLSTM and LRCN**

Some Details about **ConvLSTM** and **CNN-LSTM**

ConvLSTM is a variant of LSTM (Long Short-Term Memory) containing a convolution operation inside the LSTM cell. Both the models are a special kind of RNN, capable of learning long-term dependencies.

ConvLSTM replaces matrix multiplication with convolution operation at each gate in the LSTM cell. By doing so, it captures underlying spatial features by convolution operations in multiple-dimensional data.

The main difference between ConvLSTM and LSTM is the number of input dimensions. As LSTM input data is one-dimensional, it is not suitable for spatial sequence data such as video, satellite, radar image data set. ConvLSTM is designed for 3-D data as its input.

A CNN-LSTM is an integration of a CNN (Convolutional layers) with an LSTM. First, the CNN part of the model process the data and one-dimensional result feed an LSTM model.

**Dataset:** Provided by University of Central Florida

I have used **UCF50 – Action Recognition Dataset**, Provided by **University of Central Florida** which consist of realistic videos taken from youtube which differentiates this data set from most of the other available action recognition data sets as they are not realistic and are staged by actors. The Dataset contains:

**50** Action Categories<br>
**25** Groups of Videos per Action Category<br>
**133** Average Videos per Action Category<br>
**199** Average Number of Frames per Video<br>
**320** Average Frames Width per Video<br>
**240** Average Frames Height per Video<br>
**26** Average Frames Per Seconds per Video<br>

More about Dataset: https://www.crcv.ucf.edu/data/UCF50.php<br>
Direct Download: https://www.crcv.ucf.edu/data/UCF50.rar

References: 
<a href="https://arxiv.org/abs/1411.4389?source=post_page---------------------------">Long-term Recurrent Convolutional Networks for Visual Recognition and Description</a><br>
https://www.quora.com/What-is-the-difference-between-ConvLSTM-and-CNN-LSTM<br>
<a href="https://bleedaiacademy.com/human-activity-recognition-using-tensorflow-cnn-lstm/">ConvLSTM and LRCN</a>

