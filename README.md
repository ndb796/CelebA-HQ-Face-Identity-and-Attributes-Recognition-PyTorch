## CelebA HQ Face Identity and Attributes Recognition using PyTorch

> This repository provides a CelebA HQ face identity and attribute recognition model using PyTorch.

### Datasets

#### Facial Identity Recognition Dataset

* There are 307 identities.
    * Each identity has more than 15 images.
* There are 4,263 train images.
* There are 1,215 test images.

<pre>
<b>Dataset/</b>
    <b>train/</b>
        identity 1/
        identity 2/
        ...
    <b>test/</b>
        identity 1/
        identity 2/
        ...
</pre>

#### Face Gender Recognition Dataset

* There are 30,000 gender images.
    * There are 11,057 male images.
    * There are 18,943 female images.
* There are 23,999 train images.
* There are 6,001 test images.

<pre>
<b>Dataset/</b>
    <b>train/</b>
        male/
        female/
    <b>test/</b>
        male/
        female/
</pre>

### Model Training Examples

#### Facial Identity Recognition Model

* [Training source code](/Facial_Identity_Classification_using_Transfer_Learning_with_ResNet18.ipynb)
* [Testing source code](/Facial_Identity_Classification_Test_with_CelebA_HQ.ipynb)
* Test accuracy: <b>86.0082%</b>

<img width="60%" src="https://user-images.githubusercontent.com/16822641/110964369-7703c180-8396-11eb-9d13-bf9783682c1c.png"/>

#### Face Gender Recognition Dataset

* [Training source code](/Face_Gender_Classification_using_Transfer_Learning_with_ResNet18.ipynb)
* [Testing source code](/Face_Gender_Classification_Test_with_CelebA_HQ.ipynb)
* Test accuracy: <b>98.4003%</b>

<img width="60%" src="https://user-images.githubusercontent.com/16822641/110955992-84687e00-838d-11eb-86dd-c0a4760ac14b.png"/>
