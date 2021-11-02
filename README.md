# Chest-X-Ray-detection-through-ResNet

Deep Learning has been revolutionizing Healthcare and Medicine. What's happening is that Neural Networks have reached a level of accuracy that for some tasks, like medical imagery, drug research, genome development. They are simply better than humans, even if compared to a team of specialists. For instance, in 2018 The Guardian reported a study that was showing how skin cancer was detected more accurately by Deep Learning than by dermatologists. According to this study, human dermatologists were reaching a 86.6%, while deep learning model's accuracy was 95%.
We have been provided with 133 images belonging to 4 classes: 
<ul>
    <li>Healthy</li>
    <li>Covid-19</li>
    <li>Bacterial Pneumonia</li>
    <li>Viral Pneumonia</li>
</ul>
We will try <em>Convolutional Neural Network</em> models and, specifically, we'll be using <em>ResNet</em> a pretrained model including <em>skip connection</em> features, which are probably the best way to bypass the <em>vanishing gradient problem</em>, an issue affecting recurrent neural networks training, only partially solved by LSTMs.

The dataset we are using is a custome dataset, mixing Kaggle ones. Take a look at:
https://github.com/ieee8023/covid-chestxray-dataset
