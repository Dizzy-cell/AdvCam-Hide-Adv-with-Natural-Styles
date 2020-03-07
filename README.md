# AdvCam-Hide-Adv-with-Natural-Styles

Code for "Adversarial Camouflage: Hiding Physical-World Attacks with Natural Styles"

![](header.png)

## Installation
We highly recommend using conda environnment [Anaconda](https://www.anaconda.com/distribution/).
Install Anaconda from xxx, then 

```sh
conda create -n advcam_env python=3.6
conda activate advcam_env
```
After activating virtual environment:
```sh
git clone https://github.com/RjDuan/AdvCam-Hide-Adv-with-Natural-Styles
cd xxx
pip install requirement.txt
```


## Usage
#### Quick Start
Running our given example:
```sh
sh run.sh
```
#### Basic Usage
1. Path to images
Put target image, style image, and their segmentations in folders. We set the name of target/style image and their segmentation are same by default. 
Modify run.sh and advcam_main.py if you change the path to images.
** todo (color region)
2. Parameters
Parameters can be speicified in either run.sh or advcam_main.py.
3. Run the follow scipt
```sh
sh run.sh
```
## Usage example

A few motivating and useful examples of how AdvCam can be used. 
#### Target Image
Target image (predicted as "Street sign" with 0.904 confidence)
![Target image](https://github.com/RjDuan/AdvCam-Hide-Adv-with-Natural-Styles/blob/master/results/ori_stop_sign.png)
#### Adv Images
Three adverarial images generated by AdvCam with natural adversarial perturbation.
![Adv image](https://github.com/RjDuan/AdvCam-Hide-Adv-with-Natural-Styles/blob/master/results/adv_group.png)
#### Physical Test
![Physical test](https://github.com/RjDuan/AdvCam-Hide-Adv-with-Natural-Styles/blob/master/results/AdvCam-gif2.gif)
More generation and test details can be found in [AdvCam](https://www.youtube.com/watch?v=gk3NHY_gpvg)

## Acknowledgments
We use Yang's code for style transfer part[Yang](https://github.com/LouieYang/deep-photo-styletransfer-tf).


## Citation



