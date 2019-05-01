# Malaria-Detection-with-Deep-Learning

The motivation of this notebook comes from a PyImageSearch tutorial [Deep Learning and Medical Image Analysis with Keras](https://www.pyimagesearch.com/2018/12/03/deep-learning-and-medical-image-analysis-with-keras/). In that tutorial, [Adrian Rosebrock ](https://www.pyimagesearch.com/author/adrian/) of PyImageSearch briefed about medical tests condicted for testing malaria and how he was able to achieve SOTA score over the work as discussed in [Pre-trained convolutional neural networks as feature extractors toward improved parasite detection in thin blood smear images](https://lhncbc.nlm.nih.gov/system/files/pub9752.pdf) by Rajaraman et al. Adrian's model was able to yield an accuracy score of **97%** with a training time of about **54 minutes** on Titan X GPU, whereas the model discussed in the paper took **almost a day** to train and generated an accuracy score of **95.9%**. 

So, I decided to challenge **myself** to see if I could apply the modern deep learning practices (as taught by [Jeremy Howard](https://www.linkedin.com/in/howardjeremy) in the course[ Practical Deep Learning for Coders v3](https://course.fast.ai)) with the help of the `fastai` library. The good news is *I did*. 

**Note**: Be sure to check out the PyImageSearch tutorial if you interested in a more in-depth analysis of the problem.
