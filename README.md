# TechHelper
A data driven web app which help you to frame better questions online

**Project Details**: 
As developers work on coding or technical projects, they often get stuck at some technical roadblocks. This could be a code bug, installation issue, or a technical challenge. The place where developers look for a possible solution is often online forums like Stack Overflow or other similar sites. 

In this project, I am focusing on data from dsp.stackexchange so that a user can check in advance whether their question will get answered in a reasonable time-frame. It also shows up similar questions which might be tackling the same problem.

This would help them cut short the time they need to spend on online forums and help them overcome the technical challenge faster. The project employes natural language processing and clustering techniques to groups questions of similar nature. When a user submits a question, the machine learning model identifies which cluster it belongs to, and shows the  estimated time to get the question answered and posts of similar nature.

**Pipeline**: 
![Pipeline](https://github.com/cksajil/TechHelper/blob/master/Images/BlockDGMSmall.png)

**Dataset**: 
The project use the dataset **[Stack Exchange Dataset](https://archive.org/details/stackexchange)**. 


**To run the web app locally excecute the following**

```bash

$ cd Deployed/
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
$ python app.py

```


Verify the local version by navigating to your server address in your browser.


[http://127.0.0.1:5000/](http://127.0.0.1:5000/)


## Live web app

A deployed version of the web app can be accessed at [https://tech-helper.herokuapp.com/](https://tech-helper.herokuapp.com/).






