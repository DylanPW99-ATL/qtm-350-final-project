# Amazon Rekognition Face Detection with Age Difference between Photos  

  In the United States, the Federal Bureau of Investigation reports an estimate of 460,000 children go missing every year. Anywhere from 89 to 92% percent of all missing persons are found either dead or alive. This still leaves many people as still missing, of which several are children uner the age of 18. Someone's missing child could be anywhere out in public, but nobody could know. 
  
__
 
## Project Introduction
  This project will look to see if the Amazon Rekognition machine learning service is effective in matching pictures of children to pictures of their older selves. Can Amazon Rekognition accurately match childhood photos to pictures of the child grown up? How accurate is Amazon Rekognition in matching faces under the obstruction of time and changing appearance?

__

## Hypotheses
  * Amazon Rekognition can detect a grown-up face given childhood photos.
  * Amazon Rekognition has a lower accuracy in face matching under the disruption of age
  * As the age difference between photos increases, the face matching accuracy decreases. 

__

## Using and Navigating this GitHub Repository
  The `Proposal.ipynb` file is a Jupyter notebook used for the project proposal. This file contains all the Python code that was used to run the Amazon Rekognition machine learning service on Amazon Web Services. The first section of this file sets up an S3 bucket and gets Rekognition ready to be used for facial recognition. The second section labeled *Test Set1* is using Rekognition for the images in the `year-images` directory, and the third section labeled *Test Set2* is using Reckognition for the images in the `age-images` directory. The two mentioned images directories can both be found in the `images` directory in the main directory of the repository. The `year-images` directory contains images for three different people for each year from 1991 to 2013. The `age-images` directory contains images for two different people at various ages. 
  
### Project Proposal
  In the main directory of the repo, the Jupyter notebook file that was used for the project proposal can be viewed. This file is listed under `FinalProject-Proposal.ipynb`. This file contains all the code that was used to run the Amazon Rekognition machine learning service on AWS to run the tests of facial recognition on the different images.
  
### Project Architecture
  In the main directory of the repo, a diagram of the project architecture can be viewed. This file is listed under `project-architecture.png`.

### Blog  
  The files associated with the public blog website are contained in the `blog` directory. This contains the Jupyter notebook file used for the blog as well as a separate `images` directory which contains all images that were used in the blog. The website for the blog is listed below.  
https://final-project-blog.s3.amazonaws.com/qtm-350-final-project-blog.html
