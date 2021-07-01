
[![](https://tokei.rs/b1/github/decile-team/spear?category=code)](https://github.com/decile-team/spear)
![PyPI](https://img.shields.io/pypi/v/spear)
[![docs](https://readthedocs.org/projects/spear-decile/badge)](https://spear-decile.readthedocs.io/)
[![license](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![website](https://img.shields.io/badge/website-online-green)](https://decile.org/)

<p align="center">
    <br>
        &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
        <img src="https://github.com/decile-team/spear/blob/main/SPEAR Logo.png" width="600" height="150" border="30"/>
    </br>
</p>

# SPEAR by DECILE

<p align="center">
    <br>
        &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
        <img src="https://github.com/decile-team/spear/blob/main/spear_pipeline.svg" width="1000" height="300" />
    </br>
</p>

## Semi-Supervised Data Programming for Data Efficient Machine Learning
SPEAR is a library for data programming with semi-supervision. The package implements several recent data programming approaches including facility to programmatically label and build training data.

### SPEAR provides functionality such as 
* development of LFs/rules/heuristics for quick labeling
* automatic generation of LFs
* compare against several data programming approaches
* compare against semi-supervised data programming approaches
* use subset selection to reduce annotation effort

## Installation

SPEAR requires Python 3.6 or later. To install SPEAR, we recommend using `pip`:

```git clone https://github.com/decile-team/spear.git```  
```cd spear```  
```pip install -r requirements/requirements.txt```  

## Labelling Functions (LFs)
* discrete LFs - Users can define LFs that return discrete labels
* continuous LFs - return continuous scores/confidence to the labels assigned

## Approaches Implemented
You can read [this paper](https://arxiv.org/pdf/2008.09887.pdf) to know about below approaches
* Only-L 
* Learning to Reweight
* Posterior Regularization
* Imply Loss
* CAGE
* Joint Learning

## Quick Links
* [SPEAR tutorials](https://github.com/decile-team/spear/tree/main/notebooks)
* [DECILE website](https://decile.org)
* [SPEAR documentation](https://spear-decile.readthedocs.io/)
* [SubModLib - Summarize massive datasets using submodular optimization](https://github.com/decile-team/submodlib)
* [DISTIL- Deep Diversified Interactive Learning](https://github.com/decile-team/distil)
* [CORDS- COResets and Data Subset Selection](https://github.com/decile-team/cords)

## Acknowledgment
SPEAR takes inspiration, builds upon, and uses pieces of code from several open source codebases. These include [Snorkel](https://github.com/snorkel-team/snorkel), [Snuba](https://github.com/HazyResearch/reef)  & [Imply Loss](https://github.com/awasthiabhijeet/Learning-From-Rules). Also, SPEAR uses [Apricot](https://github.com/jmschrei/apricot) for subset selection.

## Team
SPEAR is created and maintained by [Ayush](https://www.cse.iitb.ac.in/~ayusham), [Abhishek]( https://www.cse.iitb.ac.in/~gsaiabhishek/), [Vineeth](https://www.cse.iitb.ac.in/~vineethdorna/), [Harshad](https://www.cse.iitb.ac.in/~harshadingole/), [Parth](https://www.cse.iitb.ac.in/~parthlaturia/), [Pankaj](https://www.linkedin.com/in/pankaj-singh-b000894a/), [Rishabh Iyer](https://www.rishiyer.com), and [Ganesh Ramakrishnan](https://www.cse.iitb.ac.in/~ganesh/). We look forward to have SPEAR more community driven. Please use it and contribute to it for your research, and feel free to use it for your commercial projects. We will add the major contributors here.

## Publications

[1] Maheshwari, Ayush, et al. [Data Programming using Semi-Supervision and Subset Selection](https://arxiv.org/abs/2008.09887), In Findings of ACL (Long Paper) 2021.

[2] Chatterjee, Oishik, Ganesh Ramakrishnan, and Sunita Sarawagi. [Data Programming using Continuous and Quality-Guided Labeling Functions](https://arxiv.org/abs/1911.09860), In AAAI 2020.

[3] Sahay, Atul, et al. [Rule augmented unsupervised constituency parsing](https://arxiv.org/abs/2105.10193), In Findings of ACL (Short Paper) 2021.
