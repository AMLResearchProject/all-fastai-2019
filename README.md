# Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research Project

## Acute Lymphoblastic Leukemia Detection System 2020

![Peter Moss Acute Myeloid / Lymphoblastic Leukemia AI Research Project](https://www.PeterMossAmlAllResearch.com/media/images/banner.png)

This project is made up of a collection of classifiers written in FastAi Library. 

&nbsp;

# Getting Started 

To get started there are some things you need to collect:

## Hardware

These tutorials were run on Google Colab.

## Software

In this project I used Python 3, FastAI.

## Clone the repository

First of all you should clone the [ALL-FastAI-2019](https://github.com/AMLResearchProject/ALL-FastAI-2019 "ALL-FastAI-2019") repository from the [Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research Project](hhttps://github.com/AMLResearchProject "Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research Project") Github Organization. 

To do this, make sure you have Git installed, navigate to the location you want to clone the repository to on your device using terminal/commandline, and then use the following command:

```
  $ git clone https://github.com/AMLResearchProject/ALL-FastAI-2019.git
```

Once you have used the command above you will see a directory called **ALL-FastAI-2019** in the location you chose to clone to. In terminal, navigate to the **ALL-FastAI-2019** directory, this is your project root directory.

## ALL-IDB

You need to be granted access to use the Acute Lymphoblastic Leukemia Image Database for Image Processing dataset. You can find the application form and information about getting access to the dataset on [this page](https://homes.di.unimi.it/scotti/all/#download) as well as information on how to contribute back to the project [here](https://homes.di.unimi.it/scotti/all/results.php). If you are not able to obtain a copy of the dataset please feel free to try this tutorial on your own dataset, we would be very happy to find additional AML & ALL datasets.

### ALL_IDB1 

In this project, [ALL-IDB1](https://homes.di.unimi.it/scotti/all/#datasets) is used, one of the datsets from the Acute Lymphoblastic Leukemia Image Database for Image Processing dataset. We will use data augmentation to increase the amount of training and testing data we have.

"The ALL_IDB1 version 1.0 can be used both for testing segmentation capability of algorithms, as well as the classification systems and image preprocessing methods. This dataset is composed of 108 images collected during September, 2005. It contains about 39000 blood elements, where the lymphocytes has been labeled by expert oncologists. The images are taken with different magnifications of the microscope ranging from 300 to 500."  

&nbsp;

# FastAI Classifier Projects

| Model  | Project                                                                                                                                                                                     | Description                           | Status  | Author                                                                                                                                                                                     |
| ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------- | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Resnet | [FastAI Resnet18 Classifier](https://github.com/AMLResearchProject/ALL-FastAI-2019/blob/master/Colab-notebooks/ALL_FastAI_Resnet_18.ipynb "FastAI Resnet18 Classifier")         | A FastAI model trained using Resnet18 | Ongoing | [Salvatore Raieli](https://github.com/salvatorera "Salvatore Raieli") / [Adam Milton-Barker](https://www.petermossamlallresearch.com/team/adam-milton-barker/profile "Adam Milton-Barker") |
                 
&nbsp;

# Contributing

The Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research project encourages and welcomes code contributions, bug fixes and enhancements from the Github.

Please read the [CONTRIBUTING](https://github.com/AMLResearchProject/ALL-FastAI-2019/blob/master/CONTRIBUTING.md "CONTRIBUTING") document for a full guide to forking our repositories and submitting your pull requests. You will also find information about our code of conduct on this page.

## Contributors

- [Salvatore Raieli](https://github.com/salvatorera "Salvatore Raieli") - [Peter Moss Leukemia AI Research](https://www.leukemiaresearchassociation.ai "Peter Moss Leukemia AI Research") & Biogenera, Bologna, Italy

&nbsp;

# Versioning

We use SemVer for versioning. For the versions available, see [Releases](https://github.com/AMLResearchProject/ALL-FastAI-2019/releases "Releases").

# License

This project is licensed under the **MIT License** - see the [LICENSE](https://github.com/AMLResearchProject/ALL-FastAI-2019/blob/master/LICENSE "LICENSE") file for details.

# Bugs/Issues

We use the [repo issues](https://github.com/AMLResearchProject/ALL-FastAI-2019/issues "repo issues") to track bugs and general requests related to using this project. See [CONTRIBUTING](https://github.com/AMLResearchProject/ALL-FastAI-2019/blob/master/CONTRIBUTING.md "CONTRIBUTING") for more info on how to submit bugs, feature requests and proposals.