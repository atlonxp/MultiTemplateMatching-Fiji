# Introduction
Template matching is an algorithm that can be used for object-detections in images.  
The algorithm computes the probability to find one (or several) template images provided by the user into a larger image.  
For more theoretical details, see the section [Template Matching : How does it work ?](https://github.com/multi-template-matching/MultiTemplateMatching-Fiji/wiki/Template-Matching%2C-How-does-it-work).  

You can find a similar implementation in KNIME in this [repo](https://github.com/multi-template-matching/MultipleTemplateMatching-KNIME).



## Citation
If you use this implementation for your research, please cite:
  
_Multi-Template Matching: a versatile tool for object-localization in microscopy images;_  
_Laurent SV Thomas, Jochen Gehrig_  
_bioRxiv 619338; doi: https://doi.org/10.1101/619338_

## Related resources
### IJ-OpenCV
This plugin is using OpenCV in Fiji thanks to [IJ-OpenCV](https://github.com/joheras/IJ-OpenCV).

see also:  
_Domínguez, César, Jónathan Heras, and Vico Pascual. "IJ-OpenCV: Combining ImageJ and OpenCV for processing images in biomedicine." Computers in biology and medicine 84 (2017): 189-194._

### Multi-Template-Matching as a python package
We also distribute a python package available on [PyPI](https://pypi.org/project/Multi-Template-Matching/).    

## Licence
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />The content of this wiki (including illustrations and videos) is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

As a derived work of IJ-OpenCV, the source codes are licensed under GPL-3.

## Origin of the work
This work has been part of the PhD project of **Laurent Thomas** under supervision of **Dr. Jochen Gehrig** at:  
  
ACQUIFER a division of DITABIS AG  
Digital Biomedical Imaging Systems AG  
Freiburger Str. 3  
75179 Pforzheim  

<img src="https://github.com/multi-template-matching/MultiTemplateMatching-Fiji/blob/master/Images/Acquifer_Logo_60k_cmyk_300dpi.png" alt="Fish" width="400" height="80">     

## Funding
This project has received funding from the European Union’s Horizon 2020 research and innovation program under the Marie Sklodowska-Curie grant agreement No 721537 ImageInLife.  

<p float="left">
<img src="https://github.com/multi-template-matching/MultiTemplateMatching-Fiji/blob/master/Images/ImageInlife.png" alt="ImageInLife" width="130" height="100">
<img src="https://github.com/multi-template-matching/MultiTemplateMatching-Fiji/blob/master/Images/MarieCurie.jpg" alt="MarieCurie" width="130" height="130">
</p>


## Examples

### Zebrafish head detection
<img src="https://github.com/multi-template-matching/MultiTemplateMatching-Fiji/blob/master/Images/FishRoi.JPG" alt="Fish" width="300" height="300"> 
<img src="https://github.com/multi-template-matching/MultiTemplateMatching-Fiji/blob/master/Images/Montage_Head.png" alt="MontageHead" width="500" height="300">

Dataset available on Zenodo  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2650162.svg)](https://doi.org/10.5281/zenodo.2650162)


### Medaka larvae detections
<img src="https://github.com/multi-template-matching/MultiTemplateMatching-Fiji/blob/master/Images/EggDetected.png" alt="MedakaEgg" width="250" height="250">
<img src="https://github.com/multi-template-matching/MultiTemplateMatching-Fiji/blob/master/Images/MontageEgg.png" alt="MontageEgg" width="650" height="250">  

Image courtesy Jakob Gierten (COS, Heidelberg)  
Dataset available on Zenodo    
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2650147.svg)](https://doi.org/10.5281/zenodo.2650147)
