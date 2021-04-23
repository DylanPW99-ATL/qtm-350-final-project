# Amazon Rekognition Face Detection with Age Difference between Photos  

  Kidnappings and missing children are serious problems within our society. According to statistics from the Federal Bureau of Investigation (FBI), in 2020, 365,348 missing children cases were registered, and in 2019, there were 421,394 ("Key Facts", 2021). Anywhere from 89 to 92% percent of all missing persons are found either dead or alive. This still leaves many people as still missing, of which several are children uner the age of 18. Someone's missing child could be anywhere out in public, but nobody could know. Services such as the child abduction alert system and missing people website may help parents find their missing children, yet there is the possibility that some of the kids cannot be found. However, after many years, it might be very hard to recognize a person. To find if there is any possibility to alleviate this worldwide problem with the aid of AWS Rekognition, we designed our project, which explores to what extent that this tool can figure out the similarities between the images of the same person as a child and after turning into an adult.  
  
  The website for the project blog is listed at the bottom of the page. This blog reports everything performed in the project and all the findings.
  
__
 
## Project Introduction
  This project will look to see if the Amazon Rekognition machine learning service is effective in matching pictures of children to pictures of their older selves. Can Amazon Rekognition accurately match childhood photos to pictures of the child grown up? How accurate is Amazon Rekognition in matching faces under the obstruction of time and changing appearance?
  This project also further explores the age detect function within Amazon Rekognition. This will test for age in images to help explain any findings in the project.

__

## Hypotheses
  * Amazon Rekognition can detect a grown-up face given childhood photos.
  * Amazon Rekognition has a lower accuracy in face matching under the disruption of age
  * As the age difference between photos increases, the face matching accuracy decreases. 

__

## Reproducing this Project
  The goal of this GitHub repository is to supply all code, documentation, and data that was used in the project so that someone may reproduce the project. If someone wanted to reproduce this project, start by downloading this repository to get all the files that were used in this project. The `images` directory contains all the images used for facial recognition testing. Using AWS, one can create a new Amazon Sagemaker notebook instance. Inside this new notebook, one can upload the file in this repository called `FinalProject-Proposal.ipynb` as well as the images from the `images` directory. This Jupyter notebook file contains the code to use the Amazon Rekognition machine learning service and will also use the AWS S3 service. The code runs the facial recognition and age detection tests on the two sets of images in the `images` directory. The output of this code produces the data that is supplied in the `data` directory of this repository. If you would like to know more about using and navigating this GitHub repository, information is given below.
  
__

## Using and Navigating this GitHub Repository
  The following sections show what all the files and directories in this repository are used for in the project as well as how to navigate through all of them. This repository contains all the images that were tested on with Amazon Rekognition, and it also contains the code and the data that it produced. You can also find the diagram for the project architecture. Lastly, this repository also contains the files used for the blog that discusses the project. The link for the public blog website can be found at the bottom of the `README.md` file.
  
### Project Proposal
  In the main directory of the repo, the Jupyter notebook file that was used for the project proposal can be viewed. This file is listed under `FinalProject-Proposal.ipynb`. This file contains all the code that was used to run the Amazon Rekognition machine learning service on AWS to run the tests of facial recognition on the different images.
  
### Project Architecture
  In the main directory of the repo, a diagram of the project architecture can be viewed. This file is listed under `project-architecture.png`.
  
### Data
  All of the data that was produced and collected from running the tests can be found in the `data` directory. All the images that the Amazon Rekognition facial recognition tests were run on can be found in the `images` directory of the repo. In this directory, there are two separate directories: `age-images` and `year-images`. The `age-images` directory contains images for two different people at various ages. The `year-images` directory contains images for three different people for each year from 1991-2013. 

### Blog  
  The files associated with the public blog website are contained in the `blog` directory. This contains the Jupyter notebook file used for the blog labeled `Blog.ipynb` as well as a separate `images` directory which contains all images that were used in the blog. The blog contains everything about the project that was produced, such as introduction, motivation, code, findings, project architecture, and references. The website for the blog is listed below.  
  
https://final-project-blog.s3.amazonaws.com/qtm-350-final-project-blog.html
