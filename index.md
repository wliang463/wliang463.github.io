## Data Science and Machine Learning Portfolio

Below is a compilation of highlights from my **8 years of data analysis and machine learning** using
<br>
-Lunar GRAIL gravity+topography dataset (17 million data points)
<br>
-Lunar crater catalog (10 million data points)
<br>
-Mars Rover dataset (1000+ 1200x1200 images)

---

### Crater Depth Prediction using Supervised Learning, Apache Spark, and Docker

The Moon has countless (> 1 million) craters whose depths vary significantly. Here, I build machine learning models that
incorporate linear regression, decision trees, random forests, and gradient boosting to predict the depth of a lunar crater
if the diameter, as well as the location of the crater, are known. In this project, I use Apache Spark as the main base from
which machine learning is conducted. After the project is finalized, I used Docker to consolidate the pipeline into a 
distributable application. The model achieved a R^2 of 0.7 as well as a RMSE of 0.4 log(m), which is very reasonable considering the
significant variations in crater depth due to factors such as age and terrain.

<a href="https://github.com/wliang463/crater_depth_prediction">Project Code</a> 
<br>
<a href="https://hub.docker.com/repository/docker/weigangliang/crater_depth_predictions/general">Docker Image</a> 




### Crater Detection using Deep Learning/Neural Networks and AWS (S3, SageMaker)

A study of using deep learning to detect craters within the lunar gravity dataset using the Amazon AWS environment. Transfer learning using the MobileNetV2 learning weights was utilized. The resulting accuracy of crater prediction was 91%, which is an improvement over the A/B algorithm described below by 5%. As only one instance of training was needed, the subsequent crater predictions is much faster than the A/B algorithm, resulting in a further 50% increase in the efficiency of data analysis.

<p align="center">
  <img src="/images/output_9_1.png" style="width: 49%" />
  <img src="/images/output_24_0.png" style="width: 49%" /> 
</p>

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=Amazon-AWS&logoColor=white)
![Deep Learning](https://img.shields.io/badge/Deep_Learning-006400?style=flat-square&logoColor=white)
![Neural Networks](https://img.shields.io/badge/Neural_Networks-8A2BE2?style=flat-square&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=Amazon-S3&logoColor=white)
![SageMaker](https://img.shields.io/badge/SageMaker-FF9900?style=flat-square&logo=Amazon-SageMaker&logoColor=white)
![Transfer Learning](https://img.shields.io/badge/Transfer_Learning-DC143C?style=flat-square&logoColor=white)
![Convolutional Neural Network (CNN)](https://img.shields.io/badge/Convolutional_Neural_Network_(CNN)-00008B?style=flat-square&logoColor=white)



<a href="https://github.com/wliang463/crater_detection/blob/main/crater_detection.md">Markdown Code</a> 

### MCMC Analysis of Anomalies in Lunar Gravity Data

Analysis of the lunar gravity dataset reveals anomalous signal originating from subsurface Grand Canyon-sized structures. I used machine learning (nonlinear regression), Bayesian statistics (Markov chain Monte Carlo), and time-series analysis to constrain the depth, thickness, and widths of the structures. Our analysis resulted in an increase of 60% in model precision and peer-reviewed publications in high-impact journals.

<img src="/images/moon_gravity_map.png" style="width: 99%" />
<img src="/images/earth_gravity.png" style="width: 99%" /> 
<img src="/images/mcmc_error.png" style="width: 85%" /> 

![Machine Learning](https://img.shields.io/badge/Machine_Learning-ff5722?style=flat-square&logoColor=white)
![Nonlinear Regression](https://img.shields.io/badge/Nonlinear_Regression-3f51b5?style=flat-square&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![matplotlib](https://img.shields.io/badge/matplotlib-8CAAE6?style=flat-square&logo=matplotlib&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=Jupyter&logoColor=white)
![Markov Chain Monte Carlo](https://img.shields.io/badge/MCMC-68b030?style=flat-square&logoColor=white)
![Time-Series Analysis](https://img.shields.io/badge/Time--Series_Analysis-ff69b4?style=flat-square&logoColor=white)



<a href="https://wliang463.github.io/lunar_data_analysis/Analysis_of_Lunar_Gravity_Dataset.html">Demo Jupyter Notebook</a> 
<br>
<a href="https://www.sciencedirect.com/science/article/abs/pii/S0019103522000951">Publication</a> 
<br>
<a href="https://github.com/wliang463/lunar_data_analysis">Github Repository</a> 


---

### Automated Pattern Recognition Algorithm for Lunar Gravity Data

The traditional way of identifying meteor impact sites (craters) is to count them by hand. I designed, implemented, and optimized an algorithm using A/B testing that automatically identifies craters in lunar gravity maps, enabling an over 50% increase
in the efficiency of data analysis.

<img src="/images/topo_comp_csfd_demo2.png" style="width: 99%" />

[![A/B Testing](https://img.shields.io/badge/A%2FB%20Testing-purple.svg)]()
[![Algorithm Development](https://img.shields.io/badge/Algorithm_Development-blue.svg)]()
[![Pattern Recognition](https://img.shields.io/badge/Pattern_Recognition-green.svg)]()
[![Feature Engineering](https://img.shields.io/badge/Feature_Engineering-red.svg)]()
[![Automated Detection](https://img.shields.io/badge/Automated_Detection-orange.svg)]()
[![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=Mathworks)]()


<a href="https://www.hou.usra.edu/meetings/lpsc2022/pdf/1611.pdf">Conference; Paper under submission</a> 
<br>
<a href="https://github.com/wliang463/missing_craters_rings">Github Repository</a> 

---

### Photometric Analysis of Mars Rover Image Data

I significantly (five-fold) enhanced an ETL multi-platform data/image processing pipeline as part a NASA collaboration, using a variety of software languages. This pipeline, capable of parallelized image alignment and sophisticated processing of raw images to generate terrain and solar angle maps, facilitates the analysis of martian rover images spanning multiple martian years. The results of our analysis, using nonlinear regression methods, greatly constrained the mineral composition of the martian surface. This pipeline has consistently served NASA's data processing needs, remaining in active use for over 7 years.

<p align="center">
  <img src="/images/mars_surface.jpg" style="width: 49%" />
  <img src="/images/sso_plot.png" style="width: 49%" /> 
</p>

![ETL](https://img.shields.io/badge/ETL-4CAF50?style=flat-square&logo=ApacheKafka&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-ff5722?style=flat-square&logo=LightGBM&logoColor=white)
![Nonlinear Regression](https://img.shields.io/badge/Nonlinear_Regression-3f51b5?style=flat-square&logo=Graphana&logoColor=white)
![Model Validation](https://img.shields.io/badge/Model_Validation-31B8FF?style=flat-square&logo=Checkmarx&logoColor=white)
![Data Pipeline Design](https://img.shields.io/badge/Data_Pipeline_Design-FF7C37?style=flat-square&logo=ApacheAirflow&logoColor=white)
![Cross-functional Collaboration](https://img.shields.io/badge/Cross--functional_Collaboration-0082C6?style=flat-square&logo=MicrosoftTeams&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-017ACC?style=flat-square&logo=Mathworks&logoColor=white)
![Perl](https://img.shields.io/badge/Perl-49457E?style=flat-square&logo=Perl&logoColor=white)



<a href="https://www.sciencedirect.com/science/article/abs/pii/S0019103518305396">Publication 1</a> 
<br>
<a href="https://www.sciencedirect.com/science/article/pii/S0032063322001490">Publication 2</a> 
<br>
<a href="https://www.sciencedirect.com/science/article/pii/S0019103520305844">Publication 3</a> 
<br>
<a href="https://www.sciencedirect.com/science/article/abs/pii/S0019103518305396">Unfortunately, the code has not yet been cleared for public release.</a> 

---

### Graphical User Interface (GUI) Development to Analyze Mars Rover Data

As part of a NASA collaboration, I designed and developed "new_cv24," a novel GUI software capable of loading and processing Photometry QUBs – extensive data files consisting of ~60 Mars rover images. The software empowers users to overlay images, select regions of interest, and assemble information from all images into an ASCII file, greatly enhancing data analysis capabilities. This not only expedited various data analysis subroutines into a singular, streamlined interface, but also significantly improved user operational efficiency.

<img src="/images/new_cv24.png" style="width: 99%" />

![Data Visualization](https://img.shields.io/badge/Data%20Visualization-%230077B5.svg?&style=flat-square&logoColor=white)
![GUI Design](https://img.shields.io/badge/GUI%20Design-%23F37626.svg?&style=flat-square&logoColor=white)
![Image Processing](https://img.shields.io/badge/Image%20Processing-%23B7B5E4.svg?&style=flat-square&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-%23FF7C00.svg?&style=flat-square&logoColor=white)
![Data Extraction and Manipulation](https://img.shields.io/badge/Data%20Extraction%20and%20Manipulation-%2382C366.svg?&style=flat-square&logoColor=white)

<a href="https://www.sciencedirect.com/science/article/abs/pii/S0019103518305396">Used in the photometric analysis publications</a> 
<br>
<a href="https://www.sciencedirect.com/science/article/abs/pii/S0019103518305396">Unfortunately, the code has not yet been cleared for public release.</a> 

---

### Numerical Modeling of Heat and Topographical Diffusion on the Moon

Analysis of the lunar gravity data shows a lack of craters in the nearside. We model heat and topographical diffusion
to the farside highlands as hypothetical processes that could have resulted in the deficit. The results reveals the potential thermal erasure of a structure at an scale (500 km width x 3 km height) that is the largest of its kind in the entire Solar System.

<img src="/images/thermal_annealing.png" style="width: 99%" />

![Problem Solving](https://img.shields.io/badge/Problem_Solving-%2300599C?style=flat-square&logoColor=white)
![Numerical Modeling](https://img.shields.io/badge/Numerical_Modeling-%235012B1?style=flat-square&logoColor=white)
![Data Manipulation](https://img.shields.io/badge/Data_Manipulation-%23A30000?style=flat-square&logoColor=white)

<a href="https://www.hou.usra.edu/meetings/lpsc2022/pdf/1611.pdf">Conference; Paper under submission</a> 
<br>
<a href="https://github.com/wliang463/missing_craters_rings">Github Repository</a> 
