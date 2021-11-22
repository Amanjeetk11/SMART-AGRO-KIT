## IVP PROJECT | SMART AGRO KIT
Group No- 14

#### Faculty Name-  Dr. Shiv Ram Dubey

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#built-with">Built With</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#How-to-use">How to use</a></li>
    <li>
      <a href="#model-predictions">Model Predictions</a>
      <ul>
        <li><a href="#when-no-disease-detected-on-plant">When no disease detected on plant</a></li>
        <li><a href="#when-no-disease-detected-on-plant-leafs">When no disease detected on plant leafs</a></li>
        <li><a href="#when-disease-detected-on-plant">When disease detected on plant</a></li>
        <li><a href="#when-disease-detected-on-plant-leafs">When disease detected on plant leafs</a></li>
        <li><a href="#Disease-cure-recommendations">Disease cure recommendations</a></li>
      </ul>
    </li>
     <li><a href="#team-members">Team Members</a></li>
     <li><a href="#Important-Project-Links">Important Project Links</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>


## About The Project

In modern era many of farmers not able to predict right information due to lack of skills,time This is the reason for many crops failure. Unfortunately the farmers award with huge losses and in some case it grow to be committing suicide.In order to make their task a bit easier we have worked on a project and  developed a reliable and easy to use system for use by farmers. So for detection of diseases on crops we have proposed a smart and efficient technique by using image processing and IoT techniques, farmers need to click pictures of their crops and upload that to our webpage then the system will analyse crops and alerts with disease names as well as how to prevent them.


<!-- ## Team Members
|   Enrollment No.  |   Name   | Github ID |
|   --------------  |   ----   | -------- |
|    IIT2019239  |  Mrityunjaya Tiwari  | [Error404m ](https://github.com/Error404m) |
|    IIT2019222  |   Rauank Singh Rathore  | [Error404r ](https://github.com/Error404r) |
|    IIB2019006  |   Amanjeet Kumar |  [Amanjeetk11 ](https://github.com/Amanjeetk11) |
|    IIT2019202  |   JYOTI VERMA | [Jyo123-verma ](https://github.com/Jyo123-verma) |
|    IIT2019236  |  Noonsavath Sravana Samyukta | [samyukta9500 ](https://github.com/samyukta9500) | 
|    IIT2019200  |   Raj chandra  | [RAJCHANDRA ](https://github.com/RAJCHANDRA) | -->


## Built With
<ul>
   <li>Flask</li>
   <li>Python</li>
   <li>IoT</li>
  <li>HTML</li>
  <li>CSS</li>
  <li>Javascript</li>
  <li>python</li>
</ul>


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
  * Create the Virtual Environment
  ```sh
  $ python3 -m venv venv
  ```
  
  * Activate the virtual environment
  ```sh
  $ source venv/bin/activate
  ```
  
  * Install Falsk
  ```sh
  $ pip3 install Flask
  ```
  
  * Install NumPy
  ```sh
  $ python -m pip install numpy
  ```
  
  * Install Pandas
  ```sh
  $ python -m pip install pandas
  ```
  
  * Install Matplotlib
  ```sh
  $ python -m pip install matplotlib
  ```
  
  * Install OpenCV
  ```sh
  $ python -m pip install opencv-python
  ```
  
  * Install Keras
  ```sh
  $ python -m pip install keras
  ```
  
  * Install TensorFlow
  ```sh
  $ python -m pip install tensorflow
  ```
  
 ### Installation


1. Clone the repo
   ```sh
   git clone https://github.com/Amanjeetk11/ivp.git
   ```
2. Change directory to main file
   ```sh
   cd model_codes
   ```
3. Install requirements.txt
   ```sh
   pip install requirements.txt 
   ```
4. Set the FLASK_APP system variable
   ```sh
   $ export FLASK_APP=app.py
   ```
5. Run Flask
   ```sh
   $ flask run
   ```
Visit http://127.0.0.1:5000 to see your app in action 

<!-- Usage -->
## How to use
1.Go through webpage link http://127.0.0.1:5000 
<br> <img src="ss/landing_page.png"  height="370" />

2. Tap on choose file.
3. Upload or click picture of crops.
4. Click on predict

Now system will auto show status of crops ,if disease detected it will shoe name and their cure.


<!-- Usage -->
## Model Predictions

 > ### When no disease detected on plant
  
 <br> <img src="ss/healthy_plant.png"  height="370" /> <br>
  
 > ### When no disease detected on plant leafs
<br>  <img src="ss/healthy_plant_leaf.png"  height="370" /> <br>
  
 > ### When disease detected on plant
 <br> <img src="ss/dis_palnt.png"  height="370" /> <br>
  
 > ### When disease detected on plant leafs
 <br> <img src="ss/dis_plant_leaf.png"  height="370" /> <br>
 
 > ###    Disease cure recommendations
 <br> <img src="ss/dis_rec.png"  height="370" /> <br>
 
<!-- Acknowledgements -->
## Team Members  
   
| Profile | Name | Enrollment Number | 
| :-------------: | :-------------: | ------------- |
| <img src='https://dbms.redixolabs.in/img/jprmbt1.jpeg' width='55' height='55'> | Mrityunjaya Tiwari| IIT2019239 
| <img src='https://dbms.redixolabs.in/img/RAUNAK.jpeg' width='55' height='55'> | Raunak Singh Rathore| IIT2019222
| <img src='https://dbms.redixolabs.in/img/20210429_210617.jpg' width='55' height='55'>| Amanjeet Kumar| IIB2019006  
| <img src='https://dbms.redixolabs.in/img/jyoti.jpeg' width='55' height='55'> | Jyoti Verma| IIT2019202
| <img src='https://scontent.fdel25-1.fna.fbcdn.net/v/t1.6435-9/123683167_3677796225597410_8089109414592651589_n.jpg?_nc_cat=109&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=NACW2ch87egAX8tW791&_nc_ht=scontent.fdel25-1.fna&oh=5af40a611a4e60ef837fa6c8e62ebca3&oe=61C1F0E2' width='55' height='55'> | N Samyukta| IIT2019236 
| <img src='https://scontent.fdel25-1.fna.fbcdn.net/v/t1.6435-9/80791218_160732211948308_2247008756191723520_n.jpg?_nc_cat=102&ccb=1-5&_nc_sid=174925&_nc_ohc=ByuUq-ZuQU4AX_cvGqP&_nc_oc=AQllDoRT49nK6mqZHB2yVdezF36vwdvu9i_jCMqK_u6HS12zxgt5pLrH2SeQ5VLx07s&_nc_ht=scontent.fdel25-1.fna&oh=5da05a1c68565ccb6de9dfcf1aee906c&oe=61C22BEB' width='55' height='55'>| Raj Chandra | IIT2019200  

<!-- Important Project Links -->
## Important Project Links
* [Website Frontend (only for demo) ](https://amanjeetk11.github.io/ivp/Web%20part/index.html)
* [Google colab Link](https://colab.research.google.com/drive/1s0LwOQbv54WbKTxh9PvEtcFiVrercUxK?usp=sharing)
* [Report Docs](https://docs.google.com/document/d/1KTymgQa6YGZmuw8pNrisI0JCPPe5htt6/edit#)
* [PPT Presentation](https://towardsdatascim/build-your-first-machine-learning-model-using-tensorflow-d61b9b2b7d5e)



<!-- Acknowledgements -->
## Acknowledgements
* [Deploy flask app ](https://www.freecodecamp.org/news/how-to-build-a-web-application-using-flask-and-deploy-it-to-the-cloud-3551c985e492/)
* [Flask App tutorial](https://www.digitalocean.com/community/tutorials/how-to-make-a-web-application-using-flask-in-python-3)
* [Training model with Tensorflow](https://towardsdatascience.com/build-your-first-machine-learning-model-using-tensorflow-d61b9b2b7d5e)
* [deploy model using Keras](https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/)


