The task is to identify whether or not a given 256X256 image provided is Human. I have scraped data from google consisting of 2 
2 sets of image (Monkey and Human). I have used a CNN approach as it is the  best techniques when we come across image 
classification. Multiple parts of a specific image would be feeded into the convolution layer for further calculation. The pooling layer
was used for feature engineering and reducing the size as well. Image cannot have negative pixels , when pooling layer calculates the
metrix there might be negative values so in order to cap them to 0 we use a RELU. Once this part is done then a fully connected neural 
network was used for the final prediction. 