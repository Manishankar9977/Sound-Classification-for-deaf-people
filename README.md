<h1 align="center">  Sound Classification for the deaf </h1><img align='right' src = "https://media3.giphy.com/media/jridUrt4aYAbOee6Oz/giphy.gif?cid=ecf05e473en9t753zuf21ealg0qoslr1o5izeqf3g73qid3f&rid=giphy.gif&ct=s"  height="120" alt="Jahnavi Darbhamulla">

<br/>



  [![UI ](https://img.shields.io/badge/Colab%20Interface-Link-orange?style=flat-square&logo=appveyor)](https://colab.research.google.com/drive/1MIc0iEUjqN0FRKv1DSeqLECkfMZeOF_S?usp=sharing)
 
## Abstract



## Dataset
**ESC-50** Dataset for Environmental Sound Classification is a tagged collection of 2000 recordings of environmental sound that is appropriate for benchmarking environmental sound categorization techniques.

<p>
<img src ="https://datasets.activeloop.ai/wp-content/uploads/2022/09/image-1.png" height=350 width=500>
</p>

It contains 50 semantic classes with 40 examples each and 5 major categories:
- Animals
- Natural soundscapes & water sounds
- Human, non-speech sounds
- Interior/domestic sounds
- Exterior/urban noises

This dataset can be downloaded as a .zip file: [ESC-50 dataset](https://github.com/karoldvl/ESC-50/archive/master.zip)

## Methodology

### Feature Extraction - MFCC
To perform Audio classification, we first preprocess the data to extract the audio signal's relevant features using **MFCC** and then pass those important features through the deep neural network for the audio classification. The **Mel Frequency Cepstral Coefficients** (MFCCs) are short term spectral features of a signal which concisely describe the overall shape of a spectral envelope.
Few MFCCs extracted from ESC-50 dataset: 
**Ariplane:** <br>
![image](https://user-images.githubusercontent.com/91772980/202910882-c143855e-c31c-45ae-95c1-baf898a5a68e.png)<br>
**Dog:**<br>
![image](https://user-images.githubusercontent.com/91772980/202910924-2df34941-9d88-4ac6-905b-d4223e54271c.png)

### CNN
![image](https://user-images.githubusercontent.com/91772980/202911090-57ef2c4a-591c-4206-8f80-c7a3b1da618a.png)

### RNN
![image](https://user-images.githubusercontent.com/91772980/202911103-84ab80c7-98f0-46da-882f-743c19ab9141.png)




## Contributors
<a href="https://github.com/gautam-j/gautam-j/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=gautam-j/gautam-j" />
</a>
<a href="https://github.com/Manishankar9977/Manishankar9977/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Manishankar9977/Manishankar9977" />
</a>
<a href="https://github.com/JahnaviDarbhamulla/JahnaviDarbhamulla/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=JahnaviDarbhamulla/JahnaviDarbhamulla" />
</a>


  
## License
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

<p align="center">
	Made with :coffee: and :heart:
</p>

