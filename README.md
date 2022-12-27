<h1 align="center">Passive Microwave Retrieval of Snow Density and VOD using SMAP satellite Observations at L-band</h1>

<p align="center"><strong>Description</strong>
<br> This project is part of an 8000 level, research intensive course, offered by <a href="https://www-users.cse.umn.edu/~kumar001/">Dr. Vipin Kumar</a> from the <a href="https://cse.umn.edu/cs">Dept. of CSE</a>, <a href="https://cse.umn.edu/">College of Sci. & Engg.</a>, <a href="https://twin-cities.umn.edu/">UMN</a> in Fall 2022<br/>

<div align="center"><img width="150" src="https://upload.wikimedia.org/wikipedia/commons/6/6a/University_of_Minnesota_Logo.svg"></div>

<h2>About</h2>
In this study we expand the theoretical and experimental results of retrieving snow density (SD) and vegetation optical depth (VOD) from passive L-band satellite observations from National Aeronautics and Space Administration’s (NASA) Soil Moisture Active Passive (SMAP) satellite.</p>


<h2>Problem and Goal</h2>

Retrieving SD and VOD parameters using the recently developed physical models is not desirable due to the lack of universal parameterization of static variables.
Due to the difficulty of the physical model's lack of parameterization, we propose a data-driven approach using cutting-edge machine learning models to overcome this issue in this work.
We aim for the RMSE accuracy of the snow density to be below `30 kg/m3` and the VOD to be below `0.1` in this investigation.

Our hypothesis that it is possible to extract VOD across heavily snow-covered locations in high northern latitudes where the training data is missing which demonstrates the generalizability of our designed machine learning models.


<h2>Key learnings</h2>

- Data manipulation, cleaning and transforming pixel-wise data
- Ridge Regression 
- Decision Tree Regression
- Random Forest regression
- DNN 
- LSTM
- Scaling and Hyperparameter optimization
- Plotting and visualizations


<h2>Members</h2>
- <a href="https://www.linkedin.com/in/silaskati/">Kati, Silas</a> (MS Data Science, Dept. of CSE, CSE, UMN) | <a href="https://github.com/SilasKati">GitHub</a><br>
- <a href="https://www.linkedin.com/in/divya-kumawat-593a2910b/">Kumawat, Divya</a> (Ph.D. Civil Engineering Department, CEGE, UMN) | <a href="https://github.com/Divak14">GitHub</a><br>
- <a href="https://www.linkedin.com/in/destiny-ziebol/">Ziebol, Destiny</a> (MS Data Science, Dept. of CSE, CSE, UMN) | <a href="https://github.com/ddziebol">GitHub</a><br>


<h2>Future Works</h2>

Convolutional neural networks (CNNs), knowledge-guided machine learning (KGML), exploring feature importance in our models using SHAP or permutation importance, contrasting VOD estimates above 65°N to leaf area index and tree height data, and hyperparameter tuning on our numerous models are some of the techniques we plan to test. 
<br><br>
Convolutional neural networks would be a logical progression for this study and a reasonable expansion for comparison (CNNs). 
While CNNs have been modified to operate with spatial autocorrelation, LSTMs are built to work with temporal autocorrelation. Further studies might even use a more recent hybrid CNN LSTM model since both are present in our data set.

<h2>Dataset</h2>

- SMAP: https://smap.jpl.nasa.gov/

<h2>Copyright</h2>
This project is licensed under the terms of the MIT license.
