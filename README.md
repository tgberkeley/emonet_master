
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#project-results">Project Results</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#Data-and-Models">Data and Models</a></li>
        <li><a href="#Running-the-Scripts">Running the Scripts</a></li>
      </ul>
    </li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![Product Name Screen Shot][product-screenshot]


This project covers emotion recognition from facial visual signals using valence and arousal, a multi-dimensional emotion representation. The main contributions of this project are:

* We propose the novel EmoFAN-VR algorithm for emotion detection, trained to solve the partial face problem 
* We design and record EmoVR, a novel dataset of participants displaying spontaneous emotion expressions in response to videos watched in a virtual reality environment




<!-- PROJECT RESULTS -->
## Project Results

We further trained the EmoFAN algorithm (citation) on the AffectNet dataset (citation), with virtual reality occlusions applied around the eye region. 

<img src="images/EmoFAN-VR_AffectNet.png" width="800" height="420">

We then further tested our algorithm on the AFEW-VA dataset (citation), with virtual reality occlusions applied around the eye region.

<img src="images/EmoFAN-VR_AFEW-VA.png" width="800" height="420">

The EmoFAN-VR algorithm outperforms the EmoFAN algorithm, on the AFEW-VA dataset with virtual reality occlusions, by a very large margin on all metrics. This result is a new baseline for the AFEW-VA dataset with VR occlusions applied. What makes this result even more remarkable and exciting is that the EmoFAN-VR algorithm was not fine-tuned on the AFEW-VA dataset. This shows that the **EmoFAN-VR algorithm generalises well to new unseen data**.

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

The code requires the following Python packages

```sh
numpy version==1.19.0
PIL version==7.2.0
json version==2.0.9
imutils version==0.5.4
face_alignment version==1.3.4
torch version==1.7.1
torchvision version==0.8.2
cv2 version==4.5.2
skimage version==0.16.2
matplotlib version==3.2.2
seaborn version==0.10.1
```


### Data and Models

1. There are two models we can run, the original EmoFAN model 'emonet_8.pth' and the new algorithm created in this work 'EmoFAN-VR.pth'
2. affectnet data
3. afew_va data
4. 
5. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```JS
   const API_KEY = 'ENTER YOUR API';
   ```


### Running the Scripts






<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)
* [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* [Sticky Kit](http://leafo.net/sticky-kit)
* [JVectorMap](http://jvectormap.com)
* [Font Awesome](https://fontawesome.com)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/Image_VR_project.png
[EmoFAN-VR-AffectNet]: images/EmoFAN-VR_AffectNet.png
