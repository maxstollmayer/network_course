![Alt text](images/Chuetter_VRshot.png)


# Course in Network Science - online material

This repo contains jupyter notebooks and datasets to support 
the course 
### 'Introduction to complex network analysis' 
by Prof. Jörg Menche assisted by Dr. Felix Müller from the University of Vienna. 

The content is based on the online material from
https://github.com/CambridgeUniversityPress/FirstCourseNetworkScience/


## Howto run Jupyter Notebooks

Our tutorials use Python 3 and NetworkX (2.4 or later).  

You can run Python locally on your laptop by installing Jupyter/IPython on your machine, we recommend installing the [Anaconda](https://www.anaconda.com/distribution/) Python distribution with Python 3. This option requires that you are comfortable with managing software packages (i.e., using `pip` or `conda`). 

Make a folder on your machine and clone this repo into it by changing into your folder running the following command in your terminal

> git clone git@github.com:menchelab/network_course.git

In order to work with the notebooks and have your modification personalized you need to make your own branch:

> git branch --branchname--

The name of your branch should be a identifiable shortcut of your name. You can switch to your branch with

> git checkout  --branchname--

Now you can upload your modified notebook to your branch with

> git add --yourfile--
> git commit -m "yourmessage"
> git push origin --branchname--

There will be changes in the main branch by us on a regular basis. Make sure that you have the latest version of the current notebooks by downloading them to your local machine:

> git pull origin main
> git push origin --branchname--

To make sure that your personal notebooks doesn't get replaced rename them after you have received the files from the main branch (e.g. Tutorial1.ipynb into Tutorial1_JohnnyDepp.ipynb) 

## Additional Resources 

* [Dataset files](https://github.com/CambridgeUniversityPress/FirstCourseNetworkScience/tree/master/datasets)

* [Solutions to selected exercises](https://github.com/CambridgeUniversityPress/FirstCourseNetworkScience/blob/master/sample/Selected_Exercise_Solutions.pdf) (solutions to **all** exercises can be found on the [textbook website for registered instructors](https://www.cambridge.org/academic/subjects/physics/statistical-physics/first-course-network-science#resources))

* [Sample slides](https://github.com/CambridgeUniversityPress/FirstCourseNetworkScience/tree/master/sample/slides) (lecture slide decks for **all** chapters can be found on the [textbook website for registered instructors](https://www.cambridge.org/academic/subjects/physics/statistical-physics/first-course-network-science#resources))

* [Errata](https://github.com/CambridgeUniversityPress/FirstCourseNetworkScience/issues) (submit an issue to flag errors in the book)

Note: To access the resources on the CUP textbook website for instructors, one has to request an instructor account by registering and verifying their faculty status.
=======
# network_course
