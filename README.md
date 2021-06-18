# Image-Captioning
The image captioning problem and its proposed solutions have existed since the
advent of the Internet and its widespread adoption as a medium to share images.
Numerous algorithms and techniques have been put forward by researchers from
different perspectives. Krizhevsky et al.implemented a neural network using
non-saturating neurons and a very efficient a unique method GPU implementation
of the convolution function. By employing a regularization method called dropout,
they succeeded in reducing overfitting. Their neural network consisted of
maxpooling layers and a final 1000-way softmax. Deng et al.introduced a new
database which they called ImageNet, an extensive collection of images built using
the core of the WordNet structure. ImageNet organized the different classes of
images in a densely populated semantic hierarchy. Karpathy and FeiFei made use
of datasets of images and their sentence descriptions to learn about the inner
correspondences visual data and language. Their work described a Multimodal
Recurrent Neural Network architecture that utilises the inferred co-linear
arrangement of features in order to learn how to generate novel descriptions of
images. Yang et al. proposed a system for the automatic generation of a natural
language description of an image, which will help immensely in furthering image
understanding. The proposed multimodel neural network method, consisting of
object detection and localization modules, is very similar to the human visual system
which is able to learns how to describe the content of images automatically. In order
to address the problem of LSTM units being complex and inherently sequential
across time, Aneja et al.proposed a convolutional network model for machine
translation and conditional image generation. Pan et. al experimented extensively
with multiple network architectures on large datasets consisting of varying contentstyles, and proposed a unique model showing noteworthy improvement on
captioning accuracy over the previously proposed models. Vinyals et al.
presented a generative model consisting of a deep recurrent architecture that
leverages machine translation and computer vision, used to generate natural
descriptions of an image by ensuring highest probability of the generated sentence
to accurately describe the target image. Xu et al.  introduced an attention based
model that learned to describe the image regions automatically. The model was
trained using standard backpropagation techniques by maximizing a variable lower
bound. The model was able to automatically learn identify object boundaries while
at the same time generate an accurate descriptive sentence
There are many open source datasets available for this problem, like Flickr
8k (containing8k images), Flickr 30k (containing 30k images), MS COCO
(containing 180k images), etc.
But for the purpose of this, I have used the Flickr 30k dataset.
This dataset contains 30000 images each with 5 captions (as we have
already seen in the Introduction section that an image can have multiple
captions, all being relevant simultaneously).
These images are bifurcated as follows:
• Training Set — 29000 images
• Test Set — 1000 images
• Flickr_30k.devImages.txt
• Flickr_30k.testImages.txt
• Flickr_30k.trainImages.txt
• Flickr30k.lemma.token.txt
• Flickr30k.token.txt

