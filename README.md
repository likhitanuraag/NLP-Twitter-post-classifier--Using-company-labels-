# Twitter post classifier (Using company labels)
NLP - Multi class prediction model using Keras [twitter-post-classifier.ipynb]

This code is to predict the name of the company based on the inbound text from customers. For this problem, I am going with multi-class text classification using tensorflow.Keras.

For the datset, check out the links in Dataset_links.txt file.
The dataset contains 91 classes and around 2,811,774 customer post text rows. It also contains seven columns including the mentioned. 

For compability I ran this code on these versions > 
tensorflow==2.4.0
Cuda==10.0.1
CuDnn==11.0
Python==3.7.10

And, also prepare paging virtual RAM of around 170Gb. I only used 1/10th of the data in this model. To use all the data, you need around 2.4Tb of RAM. 
To increase your RAM capacity, goto system properties by typing "Edit the system environment variables" in the search bar. Once you are in the system properties window, choose performance settings and click Advanced section. Once in, choose change in virtual memory and add your pre-selected harddisk as virtual RAM. Thats it.

Have fun building models!



By the way, my pre-trained model is also included in the folder, in saved_model.zip. Check it out if needed. Cheers!
