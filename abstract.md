# Teaching with IPython/Jupyter Notebooks and JupyterHub

## The Brief Description

*The brief description you fill out below will appear in the online program.*

How does one teach a class of 220 students using the IPython/Jupyter notebook? In this talk, I will describe an answer to this question: by using JupyterHub, a multi-user platform for hosting and running IPython/Jupyter notebooks.

## The Detailed Abstract

*Your placement in the program will be based on reviews of your detailed abstract. This should be a 150-300 word detailed outline of your presentation. This detailed abstract should concisely describe software of interest to the SciPy community, tools or techniques for more effective computing, or how scientific Python was applied to solve a research problem. A traditional background/motivation, methods, results, and conclusion structure is encouraged but not required. Links to project websites, source code repositories, figures, full papers, and evidence of public speaking ability are encouraged.*

### Abstract

The [IPython/Jupyter notebook](http://try.jupyter.org) has become immensely popular as an interactive document for research, as it gives scientists the ability to interleave prose, code, and figures in an editable and executable context. This format also lends itself well to scientific programming assignments: instructions can be interleaved with coding exercises in which students implement a model, plot the data, and then interpret the results. However, ensuring that all students install the same version of the requisite Python libraries poses a logistical problem for instructors, particularly if students are unfamiliar with the command line. One solution is to provide the students access to a server where they can run the notebook, rather than requiring that they install it on their own computers. In particular, [JupyterHub](https://github.com/jupyter/jupyterhub) does just that, providing users a simple browser interface through which they can login and immediately begin executing their own notebooks.

In this talk, I will describe [how we deployed JupyterHub](https://github.com/compmodels/jupyterhub-deploy) for class of 220 students at UC Berkeley during the Spring 2015 semester. First, I will discuss the challenges associated with using the IPython/Jupyter notebook for homework assignments, and how JupyterHub helps to address some of these challenges. I will also briefly mention how JupyterHub can integrate with other tools—such as [nbgrader](https://github.com/jupyter/nbgrader), for grading IPython/Jupyter notebooks—to address the remaining challenges. Then, I will give a live demo of our deployment of JupyterHub, after which I will go into technical details about how everything is set up. I will explain how JupyterHub itself works, how we scaled it to run across multiple servers in order to accomodate all 220 students, and how we ensured that students always had access to the same files regardless of the server they were running on. Finally, I will discuss the strengths and weaknesses of teaching with JupyterHub and the notebook, and how other instructors can use it for their own classes.

### About the speakers

Jess has extensive speaking experience and has presented talks at both academic conferences (e.g., CogSci 2011, MathPsych 2013, CogSci 2014) and technical venues ([PyCon 2014](http://www.pyvideo.org/video/2655/games-for-science-creating-interactive-psycholog), [SF Python Meetup](https://www.youtube.com/watch?v=ZrUIRSVv1gw)).

Min has presented multiple tutorials on IPython at SciPy, EuroSciPy, PyCon, and PyData, and talks at SciPy, PyData, SIAM CSE, and RuPy, as well as various smaller meetings.

Kyle has spoken to audiences consisting of data scientists, developers, security practitioners, and executives at conferences and events such as Strata, PyData, DEF CON, PyTennessee, and PyTexas.