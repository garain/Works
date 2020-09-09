## Welcome to my Works
```
   ____   _                     _        _     _                            __        __         _            _                                  _                         _                              _     _                                    _   _   _ 
  / ___| | |__     ___    ___  | | __   | |_  | |__     ___   ___    ___    \ \      / /   ___  | |__        / \     _ __    _ __    ___      __| |   ___  __   __   ___  | |   ___    _ __     ___    __| |   | |__    _   _     _ __ ___     ___  | | | | | |
 | |     | '_ \   / _ \  / __| | |/ /   | __| | '_ \   / _ \ / __|  / _ \    \ \ /\ / /   / _ \ | '_ \      / _ \   | '_ \  | '_ \  / __|    / _` |  / _ \ \ \ / /  / _ \ | |  / _ \  | '_ \   / _ \  / _` |   | '_ \  | | | |   | '_ ` _ \   / _ \ | | | | | |
 | |___  | | | | |  __/ | (__  |   <    | |_  | | | | |  __/ \__ \ |  __/     \ V  V /   |  __/ | |_) |    / ___ \  | |_) | | |_) | \__ \   | (_| | |  __/  \ V /  |  __/ | | | (_) | | |_) | |  __/ | (_| |   | |_) | | |_| |   | | | | | | |  __/ |_| |_| |_|
  \____| |_| |_|  \___|  \___| |_|\_\    \__| |_| |_|  \___| |___/  \___|      \_/\_/     \___| |_.__/    /_/   \_\ | .__/  | .__/  |___/    \__,_|  \___|   \_/    \___| |_|  \___/  | .__/   \___|  \__,_|   |_.__/   \__, |   |_| |_| |_|  \___| (_) (_) (_)
                                                                                                                    |_|     |_|                                                       |_|                               |___/                                  
```
# Machine Learning Metrics Visualizer App

This is a machine learning metrics visualizer tool for binary and multi-class classification of data.
For Binary classification, Confusion Matrix, ROC Curve and Precision Recall curves can be visualized. 
For multi-class classification, only Confusion Matrix can be visualized.

## App link

[Link to app](https://garain.vision/Authentication/mlvisualize)

## Guidelines if facing problems to open site

The app uses one heroku dyno, so it faces loading issues sometimes. Once you go to the site, and it shows connecting, but doesn't open after 15 to 20s, then simply reload the site. Once it shows connecting, open some other pre-opened tab of the browser window. Then come back to the site after 5 to 6 secs. It will open by then.

## Algorithms supported

1. Support Vector Machine (SVM)
2. Logistic Regression
3. Random Forest
4. Nearest Neighbors
5. Decision Tree 
6. Neural Net(MLP)
7. AdaBoost(Decision Tree Classifier kernel) 
8. Naive Bayes
9. Quadratic Discriminant Analysis(QDA)

## Working
1. Upload a .csv file.
2. The 1st column should contain the labels and every column should have a header. 
3. Select any one of the algorithms.
4. Select hyperparameters according to your choice.
5. Select any one metric at a time to display. (Only one at a time)
6. Press classify.
7. The label column should have heading 'type'.

## Raw data
To view your data select "Show Raw data" option.

## Default
By default UCL mushrooms dataset is loaded.



# Clustering Methods
Made a new clustering algorithm based on K-Means algorithm published in Procedia Computer Science Journal named K-RMS Algorithm.
This is the web app created as an implementation of the publication "K-RMS Algorithm" that uses **Flask** and **Gunicorn** for deploying.
If we want to deploy our project to Heroku, we need a **Web Server Gateway Interface** (WSGI) such as **Gunicorn**.

## App link
[Link to app](https://garain.vision/Authentication/clusteringKRMS)

## Usage of the app
By default if any file with wrong file format is provided, the results shown as output are calculated on the Iris dataset.

Specificatons of the file:

1. 1st row should have data headings, i.e., column headings.
2. The last column should contain the corresponding data labels in an ascending order starting from index 1 (N.B. The number of clusters is calculated using this column.
3. File should be strictly in .csv format.
4. File size should be <=600 KB.

## Output
Dictionary with Accuracy and Clusters centroids alongwith a message showing number of iterations and lowest and highest errors.

## Publication details

### DOI
[https://doi.org/10.1016/j.procs.2020.03.188](https://doi.org/10.1016/j.procs.2020.03.188)

### Authors
Avishek Garain, Dipankar Das

### Bibtex

@article{garain2020k,
  title={K-RMS Algorithm},
  author={Garain, Avishek and Das, Dipankar},
  journal={Procedia Computer Science},
  volume={167},
  pages={113--120},
  year={2020},
  publisher={Elsevier}
}

### Harvard-style
Garain, A. and Das, D., 2020. K-RMS Algorithm. Procedia Computer Science, 167, pp.113-120.


# Stock Market Analyser

## Web app link

[Link to app](https://garain.vision/Authentication/stockanalyze)

## About the Project

Entering the appropriate company code and date range will fetch the company stock values.

Use the menus to plot the required plots according to the parameters available.

## Link to download stock codes

[https://investexcel.net/wp-content/uploads/2015/01/Yahoo-Ticker-Symbols-September-2017.zip](https://investexcel.net/wp-content/uploads/2015/01/Yahoo-Ticker-Symbols-September-2017.zip)

# Collision Data Visualizer Tool
This is a collision data visualizer tool for visualizing vehicle collision data in New York City.

## App link
[Link to app](https://garain.vision/Authentication/collisionvisualize)

## Notes
The app takes approx 10 to 15 seconds to load for the first time you open the app. Thereafter whenever you go to the link it runs smoothly and very fast, as the data files get cached in the browser. There is option to clear the cache. The visualization is for 10999 rows of data.

## Raw data
To view your data select "Show Raw data" option.

# Text2Image Converter
This app is capable of generating images from text in 4 formats with various types of customizations for the font with multi-lingual support.

## App Link
[http://www.garain.vision/text2image/](http://www.garain.vision/text2image/)

## Customizations

1. Font style
2. Background color
3. Bold & Italics
4. Font size
5. Height and Width
6. Text alignment in image
7. Shadow
8. Any language
9. Support for mathematical symbols

# Handwritten-and-Printed-Text-Classification-in-Doctors-Prescription [![HitCount](http://hits.dwyl.com/garain/Handwritten-and-Printed-Text-Classification-in-Doctors-Prescription.svg)](http://hits.dwyl.com/garain/Handwritten-and-Printed-Text-Classification-in-Doctors-Prescription)
Localization of Handwritten and Printed Text in doctors' prescription. It consists of two stages, first retrival of possible Text Regions in the prescriptions overcoming the challenges like lines, dotted lines and tables and finally classification of them using Machine Learning.

[Link to app](https://garain.vision/Authentication/prescription)

To run the GUI

First install the utilities:

$ sudo add-apt-repository main

$ sudo apt-get install python3.6

$ pip install Pillow

$ pip install opencv-python

$ pip install numpy

$ pip install pandas

$ pip install sklearn

$ pip install joblib

$ pip install pickle-mixin

$ pip install pdbpp

Then run the script

$ python3 tkinteropen.py

keep the data.joblib in the same directory with the tkinteropen.py

Here is an example.

INPUT IMAGE:

![alt text](https://github.com/djdhar/Handwritten-and-Printed-Text-Classification-in-Doctors-Prescription/blob/master/sample12.jpg)

GUI SNAPSHOT

![alt text](https://github.com/djdhar/Handwritten-and-Printed-Text-Classification-in-Doctors-Prescription/blob/master/dj.png)

OUTPUT IMAGE:

![alt text](https://github.com/djdhar/Handwritten-and-Printed-Text-Classification-in-Doctors-Prescription/blob/master/guguyg.png)



# Contact

<a href="https://www.linkedin.com/in/avishek-garain-2b5369152/"><img src="icon_linkedin.png" width="60"/></a> <a href="https://www.github.com/garain/"><img src="icon_github.png" width="80"/></a> <a href="https://scholar.google.com/citations?user=ESDY-skAAAAJ&hl=en"><img src="icon_google-scholar.png" width="60"/></a> <a href="https://www.facebook.com/avishek.garain.1"><img src="icon_fb.png" width="60"/></a> <a href="https://www.twitter.com/GarainAvishek"><img src="icon_twitter.png" width="60"/></a> <a href="cv_avishek_garain.pdf" download><img src="cv_icon.png" width="60"/></a> 
