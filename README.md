# Analysis of deep learning based pose estimation techniques towards artworks classification

This respository contains the main codebase for our paper: *Analysis of deep learning based pose estimation techniques towards artworks classification*


## Contents

 * [1. Getting Started](#getting-started)
 * [2. Directory Structure](#directory-structure)
 * [3. Citing](#citing)
 * [4. Contact](#contact)
 <!-- * [4. Reproduce Results](#reproduce-results) -->


## Getting Started

### Prerequisites

The notebooks uses MMPose toolbox. MMPose is an open-source toolbox for pose estimation based on PyTorch.
It is a part of the [OpenMMLab project](https://github.com/open-mmlab).

To get it ready, follow installation instruction on https://github.com/open-mmlab/mmpose

## Preparing paintings

To start experiments, you have to download historical paintings. 

For our experiments, we have used the [National Gallery of Art](https://www.nga.gov/collection-search-result.html) collection. The works are cataloged and it's easy to set a filter for the selected era. Thanks to the [open access policy](https://www.nga.gov/notices/open-access-policy.html), the collection can be used in your own research.

We have downloaded 6 collections and named them accordingly: 'gothic','renaissance','baroque','rococo','classicism','romantic'. The images of each collection have been saved to the correct subdirectory in data/paintings/

## Directory Structure

 - **src/**: The jupyter notebook code. You can find detailed description inside notebook in markdown cells.
 - **data/**: 
    - **json/**: Calculated body proportion for each architecture. 
    - **paintings/**: Directiry where historical paintings should by downloaded.


## Citing

Please consider citing if you find our findings or our repository helpful.

<!-- ```
@article{madhu2020enhancing,
  title={Enhancing human pose estimation in ancient vase paintings via perceptually-grounded style transfer learning},
  author={Madhu, Prathmesh and Villar-Corrales, Angel and Kosti, Ronak and Bendschus, Torsten and Reinhardt, Corinna and Bell, Peter and Maier, Andreas and Christlein, Vincent},
  journal={Journal on Computing and Cultural Heritage (JOCCH)},
  year={2022}
}
```
-->
<!--
## Acknowledgement

Several files and functions from our codebase are inspired by the following repositories:

-->
## Contact

This work has been developed by [Marcin Kutrzyński](https://wa.pwr.edu.pl/pracownicy/marcin-kutrzynski).
In case of any questions or problems regarding the project or repository, do not hesitate to contact me.