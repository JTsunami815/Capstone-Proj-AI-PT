# Capstone-AI-PT
___
___
## Author
___
* Johnny Tseng
___
___
## Contents:
___
* [Executive Summary](#Executive-Summary)
* [Context & Background](#Context-&-Background)
* [Problem Statement](#Problem-Statement)
* [Resources](#Resources)
* [Conclusion](#Conclusion)
___
___
## Executive Summary
___
These notebooks will consist of 3 main phases with side builds to ensure the project is done cleanly. The recording, the side builds and processing, and the modeling.  Each will do a particular job that will lead to the next stage of the process.  

Using the OpenCV, images were captured via online video resource, personal recorded resource (first and third party), and live recording from the laptop's webcam.  With the captured images, MediaPipe were applied to indiciate where each joint points are located as well as their markings.  These markings provides the X, Y, Z and Visibility of each landmarks.  After marking are placed, the information are extracted and exported as a CSV file so it can be used later as data.

In the EDA process, there were not a lot of cleaning as majority of the recorded data have no missing values.  This makes the exploration easier also prevented any unexpected errors when doing a Train-Test Split.  In the machine learning stage, both supervise and unsupervised models where used to assist on finding the best model to use to when building the AI PT.  The four models there were used are Logistic, Ridge, Random and Gradiant.  After running the data through the model pipeline, **Random Forrest** and **Gradient Boosting** provided the best scores as the difference between the two are one thousandth to ten thousandths. 
___
___
## Context and Background
___
In Singapore, the HDB (House Development Board) areas have designated workout areas called Fitness corners. Although it does not comprise all the workout equipment a person can use, it still functions as a basic tool for people who want to get there for this done with body weights or a bit of resistance from the hydraulic system.

Each Fitness corner does provide a workout board that illustrates the basic movements of using the equipment but there have been cases of people misusing them and getting injured. To better make use of these tools in the public vicinity or within the home, I believe an application like this can be very beneficial to anybody who wants to stay fit within their limitations.
___
## Problem Statement
___
For this project, I'll be challenging the idea of creating an artificial intelligence personal training tool. This will combine python, machine learning, Scikit Learn, and MediaPipe. The reason to challenge myself on this project comes from the idea of not being able to go to a gym due to covid. I also hear stories of people not being able to do the same thing because of work from home or space limitation, as well as not being able to use proper form when working out by him or herself.
___
___
## Resources
___
* [YouTube]('www.youtube.com')
* MediaPipe('https://google.github.io/mediapipe/solutions/solutions.html')
* 1st party recording
* 3rd party recording
___
___
## Conclusion
___
As of now it is a on going progress where there are a lot of improvements to be made.  Each individual workout notebook does work as it intends but what will really stand out and set apart is combining all into one where the machine is able to detect which workout the end user is doing without too much guess works and faster response time.  This will take more data collection as well as more sample of videos, locations, angles, camera and other hardware factors to be able to consider this a finished product.  But as for now, with the limited timeframe, it is in a pretty good place and will become better as time pass.
