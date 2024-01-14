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

References:<br> 
<a href="https://arxiv.org/abs/1411.4389?source=post_page---------------------------">Long-term Recurrent Convolutional Networks for Visual Recognition and Description</a><br>
https://www.quora.com/What-is-the-difference-between-ConvLSTM-and-CNN-LSTM<br>
<a href="https://bleedaiacademy.com/human-activity-recognition-using-tensorflow-cnn-lstm/">ConvLSTM and LRCN</a>
<a href="https://medium.com/neuronio/an-introduction-to-convlstm-55c9025563a7#id_token=eyJhbGciOiJSUzI1NiIsImtpZCI6IjkxNDEzY2Y0ZmEwY2I5MmEzYzNmNWEwNTQ1MDkxMzJjNDc2NjA5MzciLCJ0eXAiOiJKV1QifQ.eyJpc3MiOiJodHRwczovL2FjY291bnRzLmdvb2dsZS5jb20iLCJhenAiOiIyMTYyOTYwMzU4MzQtazFrNnFlMDYwczJ0cDJhMmphbTRsamRjbXMwMHN0dGcuYXBwcy5nb29nbGV1c2VyY29udGVudC5jb20iLCJhdWQiOiIyMTYyOTYwMzU4MzQtazFrNnFlMDYwczJ0cDJhMmphbTRsamRjbXMwMHN0dGcuYXBwcy5nb29nbGV1c2VyY29udGVudC5jb20iLCJzdWIiOiIxMTEzMjIxMjY1MDQ2NTkwODE3NjAiLCJlbWFpbCI6ImtpcmFudGVqNDg2QGdtYWlsLmNvbSIsImVtYWlsX3ZlcmlmaWVkIjp0cnVlLCJuYmYiOjE3MDQ3NzAyMTAsIm5hbWUiOiJUZWogS2lyYW4iLCJwaWN0dXJlIjoiaHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EvQUNnOG9jTDRSMWt1TVkwemIxLUs0QlN1QWUyWURtc1NyZkI1WG9qZkJsaGVsVXpVeUd3PXM5Ni1jIiwiZ2l2ZW5fbmFtZSI6IlRlaiIsImZhbWlseV9uYW1lIjoiS2lyYW4iLCJsb2NhbGUiOiJlbiIsImlhdCI6MTcwNDc3MDUxMCwiZXhwIjoxNzA0Nzc0MTEwLCJqdGkiOiIzY2ZiZWVkNGY2NmViMzQ0NmIxMjRiYjcyZTc0NTZkYWFlOWVkZDU1In0.EmJvPPwomtThgeWMBW8F9RbbMtGu0hiPGJmf303QAoiX-ZV_DsmDg5ZTA4AU5mk7cKBQeJYtYVciQp3R5Dpe444RuRjxBjpU10o9qkAQ6xaTdOVR7Uy_-iddbUZ2RsI31PC0RugT6GMLNSY95yf86I0Q5eBoPmRxY3hXIfckkMCOVU83s_3k-VD2B3lWoDwnTvg65Z_UYfNpV4b_GoUqifP6Jj-sa2I0Zmd-XDx3Dm6T-N4T75H4j53-1B1KT-JWwxKKSxv1xqr3XUT7KhoCAoBQMjNuDhpJmXefH1iICGIpGub7Io60UCSgfgzSpJOIO5EjfVQ8j4FXqAQOygg85w">An introduction to ConvLSTM</a> 

