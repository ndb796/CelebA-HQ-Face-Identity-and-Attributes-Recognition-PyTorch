## CelebA HQ Face Identity and Attributes Recognition using PyTorch

> This repository provides a CelebA HQ face identity and attribute recognition model using PyTorch.

* This dataset has been first introduced in the official PyTorch implementations for <b>[Latent-HSJA](https://github.com/ndb796/LatentHSJA)</b>.
  * The work is presented at [ECCV 2022 Workshop on Adversarial Robustness in the Real World](https://eccv22-arow.github.io/).

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

* [Training source code (resolution 256)](/Facial_Identity_Classification_using_Transfer_Learning_with_ResNet18_Resolution_256.ipynb)

#### Face Gender Recognition Dataset

* [Training source code](/Face_Gender_Classification_using_Transfer_Learning_with_ResNet18.ipynb)
* [Testing source code](/Face_Gender_Classification_Test_with_CelebA_HQ.ipynb)
* Test accuracy: <b>98.4003%</b>

<img width="60%" src="https://user-images.githubusercontent.com/16822641/110955992-84687e00-838d-11eb-86dd-c0a4760ac14b.png"/>

* [Training source code (resolution 256)](/Face_Gender_Classification_using_Transfer_Learning_with_ResNet18_Resolution_256.ipynb)


### Citation

If this work can be useful for your research, please cite our paper:

<pre>
@inproceedings{na2022unrestricted,
  title={Unrestricted Black-Box Adversarial Attack Using GAN with Limited Queries},
  author={Na, Dongbin and Ji, Sangwoo and Kim, Jong},
  booktitle={European Conference on Computer Vision},
  pages={467--482},
  year={2022},
  organization={Springer}
}
</pre>
