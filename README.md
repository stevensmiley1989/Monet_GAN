# Monet_GAN
Week 5: GANs

## 1 Jupyter Notebook<a class="anchor" id="1"></a>
Links below to visualize the notebooks rendered.

| Notebook | Description |
|--------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Week5_Assignment_r1.ipynb](https://nbviewer.org/github/stevensmiley1989/Monet_GAN/blob/main/Week5_Assignment_r1.ipynb) | Jupyter Notebook |
## 2 Data Inputs <a class="anchor" id="2"></a>
**Data Source**: https://www.kaggle.com/competitions/gan-getting-started/data

**Data Description**: 
* 4 Directories:
    * monet_jpg
        * 300 Monet paintings (256x256, .jpg)
    * monet_tfrec
        * 300 Monet paintings (256x256, TFRecord)
    * photo_jpg
        * 7028 photos (256x256, .jpg)
    * photo_tfrec
        * 7028 photos (256x256, TFRecord)
* There is two formats of data input, .jpg and tfrecord format.  
* The objective of the dataset for the competition is to train a GAN that can generate images in the style of Monet.  
* The generator should be trained using a discriminator.
* The CycleGAN is recommended for this competition. 

### 3 License <a class="anchor" id="6"></a>

This repository contains a variety of content; some developed by Steven Smiley, and some from third-parties.  The third-party content is distributed under the license provided by those parties.

The content developed by Steven Smiley is distributed under the following license:

*I am providing code and resources in this repository to you under an open source license.  Because this is my personal repository, the license you receive to my code and resources is from me and not my employer. 

   Copyright 2024 Steven Smiley

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
   
