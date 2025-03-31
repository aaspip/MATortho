**MATortho**
======

## Description
**MATortho** is a Matlab package for the local orthogonalization method and the local similarity measurement (for detecting signal leakage) introduced in Chen and Fomel (2015). 

**NOTE**: If you use this package to calculate local orthogonalization weight and local similarity, please show courtesy to cite the reference below. Using local similarity to calculate the signal leakage was first ever used in the work by Chen and Fomel (2015), please show courtesy if you use it for the same purpose.


## Reference
    Chen, Y. and Fomel, S., 2015, Random noise attenuation using local signal-and-noise orthogonalization, Geophysics, WD1-WD9.
    
BibTeX:

	@article{localortho,
	  title={Random noise attenuation using local signal-and-noise orthogonalization},
	  author={Yangkang Chen and Sergey Fomel},
	  journal={Geophysics},
	  volume={80},
	  number={6},
	  issue={6},
	  pages={WD1-WD9},
	  year={2015},
	  publisher={Society of Exploration Geophysicists}
	}

-----------
## Copyright
    MATortho developing team, 2013-present
-----------

## License
    MIT License  

-----------

## Install
Using the latest version

    git clone https://github.com/aaspip/MATortho
    cd MATortho
    addpath(genpath('./')); #in Matlab command line
    
-----------
## Examples
    The "demo" directory contains all runable scripts to demonstrate different applications of MATortho. 

-----------
## Dependence Packages
* Matlab 2015 and later versions

-----------
## Development
    The development team welcomes voluntary contributions from any open-source enthusiast. 
    If you want to make contribution to this project, feel free to contact the development team. 

-----------
## Contact
    Regarding any questions, bugs, developments, collaborations, please contact  
    Yangkang Chen
    chenyk2016@gmail.com

-----------
## Gallery
The gallery figures of the MATortho package can be found at
    https://github.com/chenyk1990/gallery/tree/main/matortho
Each figure in the gallery directory corresponds to a DEMO script in the "demo" directory with the exactly the same file name.

The following figure shows a 2D denoising example using the MATortho package. Generated by [demos/test_localortho.m](https://github.com/aaspip/MATortho/tree/main/demos/test_localortho.m)
<img src='https://github.com/chenyk1990/gallery/blob/main/matortho/test_localortho2d.png' alt='comp' width=960/>

The following figure shows a 3D denoising example using the MATortho package. Generated by [demos/test_localortho3d.m](https://github.com/aaspip/MATortho/tree/main/demos/test_localortho3d.m)
<img src='https://github.com/chenyk1990/gallery/blob/main/matortho/test_localortho3d.png' alt='comp' width=960/>


