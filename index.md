## Data Science Portfolio

Below is a compilation of highlights from **8 years of data analysis** using
<br>
-Lunar GRAIL gravity+topography dataset (17 million data points)
<br>
-Mars Rover dataset (1000+ 1200x1200 images)

---

### MCMC Analysis of Anomalies in Lunar Gravity Data

Analysis of the lunar gravity dataset reveals anomalous structures likely from subsurface Grand Canyon-sized features. I use Markov chain Monte Carlo to constrain the depth, thickness, and widths of the structures.

<img src="/images/moon_gravity_map.png" style="width: 99%" />
<img src="/images/mcmc_error.png" style="width: 85%" /> 

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy)
![matplotlib](https://img.shields.io/badge/matplotlib-8CAAE6?style=flat-square&logo=matplotlib)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=Jupyter)
![Markov Chain Monte Carlo](https://img.shields.io/badge/MCMC-68b030?style=flat-square)
![Time-Series Analysis](https://img.shields.io/badge/Time--Series_Analysis-ff69b4?style=flat-square)

<a href="https://wliang463.github.io/lunar_data_analysis/Analysis_of_Lunar_Gravity_Dataset.html">Demo Jupyter Notebook</a> 
<br>
<a href="https://www.sciencedirect.com/science/article/abs/pii/S0019103522000951">Publication</a> 
<br>
<a href="https://github.com/wliang463/lunar_data_analysis">Github Repository</a> 


---

### Automated Pattern Recognition Algorithm for Lunar Gravity Data

The traditional way of identifying meteor impact sites (craters) is to count them by hand. I designed
and implemented an algorithm that identifies crater patterns in lunar gravity maps, enabling a 500% increase
in efficiency.

<img src="/images/topo_comp_csfd_demo2.png" style="width: 99%" />

![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=Mathworks)
[![Algorithm Development](https://img.shields.io/badge/Algorithm_Development-blue.svg)]()
[![Pattern Recognition](https://img.shields.io/badge/Pattern_Recognition-green.svg)]()
[![Feature Engineering](https://img.shields.io/badge/Feature_Engineering-red.svg)]()
![Automated Detection](https://img.shields.io/badge/Automated_Detection-orange.svg)

<a href="https://www.hou.usra.edu/meetings/lpsc2022/pdf/1611.pdf">Conference; Paper under submission</a> 
<br>
<a href="https://github.com/wliang463/missing_craters_rings">Github Repository</a> 

---

### Photometric Analysis of Mars Rover Image Data

Some minerals (for example diamond vs rust) are more/less bright than other minerals when you shine a light on it. 
We analyzed how the martian surface reflected different amounts of light using images of the surface taken at 
different times in day (for example 9am vs 5pm). With this, we are able to determine the physical properties of the surface,
and constrain what minerals are present.

<p align="center">
  <img src="/images/mars_surface.jpg" style="width: 49%" />
  <img src="/images/sso_plot.png" style="width: 49%" /> 
</p>


![MATLAB](https://img.shields.io/badge/MATLAB-%23017ACC?style=flat-square&logo=Mathworks&logoColor=white)
![Perl](https://img.shields.io/badge/Perl-%2349457E?style=flat-square&logo=Perl&logoColor=white)
![Model Validation](https://img.shields.io/badge/Model%20Validation-%2331B8FF?style=flat-square&logo=Checkmarx&logoColor=white)
![Algorithm Development](https://img.shields.io/badge/Algorithm%20Development-%2303569B?style=flat-square&logo=Algorithms&logoColor=white)
![Data Pipeline Design](https://img.shields.io/badge/Data%20Pipeline%20Design-%23FF7C37?style=flat-square&logo=ApacheAirflow&logoColor=white)
![Cross-functional Collaboration](https://img.shields.io/badge/Cross--functional%20Collaboration-%230082C6?style=flat-square&logo=MicrosoftTeams&logoColor=white)

<a href="https://www.sciencedirect.com/science/article/abs/pii/S0019103518305396">Publication 1</a> 
<br>
<a href="https://www.sciencedirect.com/science/article/pii/S0032063322001490">Publication 2</a> 
<br>
<a href="https://www.sciencedirect.com/science/article/pii/S0019103520305844">Publication 3</a> 
<br>
<a href="https://www.sciencedirect.com/science/article/abs/pii/S0019103518305396">Unfortunately, the code has not yet been cleared for public release.</a> 

---

### Graphical User Interface (GUI) Development to Analyze Mars Rover Data

I was tasked to develop a new GUI software "new_cv24" that would allow a user to load in Photometry QUBs, an extensive data file comprised of ~50 Mars rover images along with coordinate maps.  The GUI enables users to overlay different images in the QUB, select regions of interest on the images, and extract information from all 50 images within the QUB into an ASCII file for further data analysis.

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
to the farside highlands as hypothetical processes that could have resulted in the deficit.

<img src="/images/new_cv24.png" style="width: 99%" />

![Problem Solving](https://img.shields.io/badge/Problem_Solving-%2300599C?style=flat-square&logoColor=white)
![Mathematical Modeling](https://img.shields.io/badge/Mathematical_Modeling-%23FCA121?style=flat-square&logoColor=white)
![Data Manipulation](https://img.shields.io/badge/Data_Manipulation-%23A30000?style=flat-square&logoColor=white)

<a href="https://www.hou.usra.edu/meetings/lpsc2022/pdf/1611.pdf">Conference; Paper under submission</a> 
<br>
<a href="https://github.com/wliang463/missing_craters_rings">Github Repository</a> 
