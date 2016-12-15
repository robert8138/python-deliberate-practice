# Python Deliberate Practice

First of all, don't be afraid, read [Plateau of Productivity]. More importantly, be patient, a good read from Peter Norvig, titled [Teach Yourself Programming in 10 years].

## Motivation

[Language war] between Python and R is one of the most frequently discussed topics among the Data Scientists, and there doesn't seem to be a consensus on which one is better. Personally, I used both R and Python, but for very different purposes. I mainly use tidyverse packages (dplyr + ggplot2) to carry out data analyses and data visualization, while using Python for web scraping, task automations, and building [basic web applications in Flask]. 

By now, I have a pretty good working knowledge of the R language. There are obviously many more things that I can learn - in particular building and maintaining R packages as well as more [advanced R materials]. Yet, the appeal of Python has always been there for me for a few reasons: 

* It's a general purpose programming language, so presumably it is a lot easier to learn good software engineering principles. (What are they though?)
* Many of the [data stacks] are built using the tools in the Python ecosystem (ETL using Airflow, Front-end using Flask with RESTful API supports, Machine Learning using scikit-learn) - being able to use the same language for different parts of the data stack will bring prototypes closer to production.

To me, the appeal of Python is not necessarily the Data Analysis part, R is already doing a great job on this. Rather, the appeal of using Python for data work is that you have a higher chance to see how data plays a role within the whole integrated technology stack. Knowing Python is likely to make me a better **end-to-end** Data Scientist and better Software Engineer.

Here is a great [reddit answer] that explains the intersection and disjoint union of the two languages beautifully.

## Deliberate Practice

I am a huge believer in learning by doing, and there are a lot of opportunities on the job where I can hone my Python skills through Deliberate Practice:

* **Identify the Top Performers**: I think there are quite a few people at Work (e.g. Dan F.) who can really be a role model for me to follow. Understand what they've been through to get to where they are today. What is their mental representation that I do not have about Python.

* **Build Practice Plans**: Ideally, based on the rough understanding of that mental representation:

    * Define clear goals and select learning materials
    * Create deadline and milestones for the project
    * Estimate time required and come up weekly schedules

  Augment these insights with your current level of mental representation of Python to improve your understanding.

* **Targeted Practice**: If I force myself to switch over to Python for Data Analysis, Data visualization, Modeling, or contribute to our internal Python Data Analysis packages, I can maximize my time practicing this skill, which is high leverage.

* **Immediate Feedbacks**: We have a culture of code reviews, both for IC work as well as internal package work. The former is harder because most DS on our team are in the R camp. There's also the weekly Python office hours that should be very useful. Find constant opportunities to get feedback as much as you can.

## Performance Goals

* **[Immediate]** Learn to write pythonic code
* **[Shorter term, easiest to practice]** Write re-usable, modular, tested code for my data work and knowledge posts
* **[Medium term, harder to practice]** Achieve efficiency and feature parity on Data Analysis using Python compared to R
* **[Longer term, hardest to practice]** Write tools. Being able to work on projects that span the entire data stack using Python, apply good software engineering principles to these projects

## Project Goals

* **Outcome**: I want to move my data stack to Python completely. This means my day-to-day data analysis work will be done in Python instead of R, make my code as pythonic as possible. Become a Contributor to Airpy / tools, and take on one bigger Python project (ML, Data Viz ...etc).

* **Curriculum**: I want do everything that I can to go through all the basic materials in Pandas/Matplotlib combo. Expose myself to functional programming, OOP, testing in Python, or even making command tools. Get feedbacks from Airpy team members.

* **Timeframe**: Efficiency parity by end of October. One contribution to Airpy by Mid November. One ongoing big project touching different stacks in Python by the end of 2016.

## Project Milestones

* **Learning Python & Best Practices**
    * [Build On Top of the Basics: Python Progression]
    * [Drastically Improve Your Understanding: Jeff Knupp: Python's Execution Mode]
    * [Nate Batchelder: Loop like a native]
    * [Columbia Data Scientist Style Guide]

* **Writing Pythonic Code**
    * Guidelines For Writing Pythonic Code
        * Function: Use *args and **kwargs to accept arbitrary arguments in function definition
        * Tuples: effective unpacking, use _ for placeholder, swap values without tmp variables
        * List/Dict/Set: list comprehension, dict comprehension. dict.get, set comprehension
        * Strings: use .format, use .join
        * Classes: use __ __ in function and variable name to mark private variables
        * Generator: use generator to lazily load a infinite sequence
        * Modules: writing modules for encapsulation
        * Formatting: pep8 standards
        * Executable script: __name__ = __main__
        * Import: The right way to do imports
    * [Writing Idiomatic Python - Jeff Knupp]
    * [Stanford CS 41: Idiomatic Python]
    * [Another Tutorial On How To Write Pythonic Code]

* **iPython Notebook**
    
    * [BIDS: Python Bootcamp: IPython Notebook]
    * [Jupyter Notebook tips, tricks and shortcuts]
    * [iPython Notebook Keybinding]

* **Pandas For Data Analysis**

    * Introduction to Numpy
        * [BIDS: Python Bootcamp: Intro to Numpy]
        * [Stanford ICME 193: Scientific Python]
    
    * Introduction to Pandas
        * [Dplyr/pandas Vignette Comparison]
        * [Data School Pandas Tutorials]
            * [Data School Pandas Github iPython notebook]
            * [More Pandas Questions Answered]
            * [Other Resources]
        * [Brandon Rhode's Pandas From The Groud Up]
        * [Tom Augspurgur: Pandas]
        * [BIDS: Python Bootcamp: Scipy Pandas]
        * [Coursera: Introduction to Data Science in Python]
        * [Chris Albon's notes]

* **Data Visualization**

    * [BIDS: Python Bootcamp: Intro to Matplotlib]: The 800 pound gorilla, everything is customizable, but very low level
    * [Seaborn]: Good for statistical visualization. I still find it a bit limited on the type of simple plots it can do
    * [Bokeh]: Interactive, web browser base data visualization
    * [A Dramatic Tour through Python’s Data Visualization Landscape (including ggplot and Altair)]

* **Writing Object Oriented Programming Python Code**
    
    * [Computational Biology: OOP For Scientist]
    * [Improve Your Python: Jeff Knupp: OOP]
    * [BIDS: Python Bootcamp: OOP]
    * Simeon Franklin's Twitter University Class (not available to the public)

* **Writing Functional Programming Python Code**
    
    * [Simeon Franklin's higher order function]
    * [BIDS: Python Bootcamp: Higher order functions]
    * [Improve Your Python: Jeff Knupp: Yield & Generator Explained]
    * [Improve Your Python: Jeff Knupp: Decorator Explained]
    * [Improve Your Python: Jeff Knupp: Context Manager]
    
* **Machine Learning In Python** 
    * [Scikit-learn Machine Learning Library]
    * [Scikit-learn metrics]
    * [Scikit-learn Pipeline]

* **Testing In Python**
    
    * [Computational Biology: Four Tools For Testing Your Python Code]
    * [Computational Biology: Testing For Scientist]
    * [Improve Your Python: Jeff Knupp: Understanding Unit Testing]
    * [BIDS: Python Bootcamp: Test Driven Development]
    * [Software Carpentry: Testing]

## Next Steps / Level In 2017

Once mastered all the above, the next natural step is to create public work that other people can use so you can democratize your useful tool to others. A great introduction to how to get started is from Tim Hopper's talk, titled [Sharing Your Side Projects].

* **Logging In Python (Next Year?)**
    * [Basic Python Logging - Code Session]
    * [Logging HOWTO]
    * [Become A Logging Expert In 30 Minutes]

* **Writing Command-Line Tool (Next Year?)**
    * [Click Documentation]
    * [Writing A Command-Line Tool In Python]

* **Building Packages In Python (Next Year?)**
    * [Computational Biology: Using Cookiecutter To Set Up A Project]
    * [Computational Biology: Creating A Clean Pytyon Development Environment]
    * [Computational Biology: How To Generate Beautiful Technical Documentation]
    * [Computational Biology: Five Steps To Add The Bling Factor Your Python Package]


## Reference

* [Python Tutor Visualizer]
* [Python For Data Analysis]
* [Stanford CS 41: Python]
* [Berkeley CS 88: Python Data Structure]
* [Harvard CS 109: Data Science]
* [Berkeley BIDS Python bootcamp]
* [Josh Bloom's Python Computing For Data Science]
* [Writing Idiomatic Python - Jeff Knupp]
* [Another Tutorial On How To Write Pythonic Code]
* [Pandas Cookbook]
* [Udemy course]

[Teach Yourself Programming in 10 years]:http://norvig.com/21-days.html
[Plateau of Productivity]:http://pbpython.com/plateau-of-productivity.html

[reddit answer]:https://www.reddit.com/r/Python/comments/2tkkxd/considering_putting_my_efforts_into_python/
[Language war]:http://www.dataschool.io/python-or-r-for-data-science/
[advanced R materials]:http://adv-r.had.co.nz/
[basic web applications in Flask]:https://github.com/robert8138/flask-google-calendar-api-project
[data stacks]:https://lab.getbase.com/productive-data-science-python/

[Build On Top of the Basics: Python Progression]:http://stackoverflow.com/questions/2573135/python-progression-path-from-apprentice-to-guru
[Drastically Improve Your Understanding: Jeff Knupp: Python's Execution Mode]:https://www.jeffknupp.com/blog/2013/02/14/drastically-improve-your-python-understanding-pythons-execution-model/
[Nate Batchelder: Loop like a native]:https://www.youtube.com/watch?time_continue=14&v=EnSu9hHGq5o
[Columbia Data Scientist Style Guide]:http://columbia-applied-data-science.github.io/pages/lowclass-python-style-guide.html

[Writing Idiomatic Python - Jeff Knupp]:https://jeffknupp.com/writing-idiomatic-python-ebook/
[Stanford CS 41: Idiomatic Python]:https://drive.google.com/file/d/0B-eHIhYpHrGDNGZCYUN6SVB1OGc/view
[Another Tutorial On How To Write Pythonic Code]:http://safehammad.com/downloads/python-idioms-2014-01-16.pdf

[BIDS: Python Bootcamp: IPython Notebook]:https://www.youtube.com/watch?v=HrylK8I1ALs&index=3&list=PLKW2Azk23ZtSeBcvJi0JnL7PapedOvwz9
[Jupyter Notebook tips, tricks and shortcuts]:https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/
[iPython Notebook Keybinding]:https://www.webucator.com/blog/wp-content/uploads/2015/07/IPython-Notebook-Shortcuts.pdf

[BIDS: Python Bootcamp: Intro to Numpy]:https://www.youtube.com/watch?v=PDOsOcG0m-Q
[Stanford ICME 193: Scientific Python]:http://stanford.edu/~arbenson/cme193.html
[Dplyr/pandas Vignette Comparison]:http://nbviewer.jupyter.org/gist/TomAugspurger/6e052140eaa5fdb6e8c0
[Data School Pandas Tutorials]:http://www.dataschool.io/easier-data-analysis-with-pandas/
[Data School Pandas Github iPython notebook]:https://github.com/justmarkham/pandas-videos
[More Pandas Questions Answered]:https://www.youtube.com/watch?v=CWRKgBtZN18&list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y&index=31
[Other Resources]:http://www.dataschool.io/best-python-pandas-resources/
[Brandon Rhode's Pandas From The Groud Up]:https://www.youtube.com/watch?v=5JnMutdy6Fw
[Tom Augspurgur: Pandas]:https://www.youtube.com/watch?v=otCriSKVV_8
[BIDS: Python Bootcamp: Scipy Pandas]:https://www.youtube.com/watch?v=bgIZAeNpL1U
[Coursera: Introduction to Data Science in Python]:https://www.coursera.org/learn/python-data-analysis/home/welcome
[Chris Albon's notes]:http://chrisalbon.com/

[BIDS: Python Bootcamp: Intro to Matplotlib]:https://www.youtube.com/watch?v=j5P822TSCKs
[Seaborn]:https://stanford.edu/~mwaskom/software/seaborn/
[Bokeh]:http://bokeh.pydata.org/en/latest/
[A Dramatic Tour through Python’s Data Visualization Landscape (including ggplot and Altair)]:https://dansaber.wordpress.com/2016/10/02/a-dramatic-tour-through-pythons-data-visualization-landscape-including-ggplot-and-altair/

[Computational Biology: OOP For Scientist]:http://tjelvarolsson.com/blog/object-oriented-programming-for-scientists/
[Improve Your Python: Jeff Knupp: OOP]:https://jeffknupp.com/blog/2014/06/18/improve-your-python-python-classes-and-object-oriented-programming/
[BIDS: Python Bootcamp: OOP]:https://www.youtube.com/watch?v=HQ0q6oMpOEs

[Simeon Franklin's higher order function]:http://simeonfranklin.com/blog/2013/jun/17/higher-order-functions-python/
[BIDS: Python Bootcamp: Higher order functions]:https://www.youtube.com/watch?v=ob797BA49ZQ
[Improve Your Python: Jeff Knupp: Yield & Generator Explained]:https://jeffknupp.com/blog/2013/04/07/improve-your-python-yield-and-generators-explained/
[Improve Your Python: Jeff Knupp: Decorator Explained]:https://jeffknupp.com/blog/2013/11/29/improve-your-python-decorators-explained/
[Improve Your Python: Jeff Knupp: Context Manager]:https://jeffknupp.com/blog/2016/03/07/improve-your-python-the-with-statement-and-context-managers/

[Scikit-learn Machine Learning Library]:http://www.dataschool.io/machine-learning-with-scikit-learn/
[Scikit-learn metrics]:http://scikit-learn.org/stable/modules/classes.html#module-sklearn.metrics
[Scikit-learn Pipeline]:http://scikit-learn.org/stable/modules/classes.html#module-sklearn.pipeline

[Computational Biology: Four Tools For Testing Your Python Code]:http://tjelvarolsson.com/blog/four-tools-for-testing-your-python-code/
[Computational Biology: Testing For Scientist]:http://tjelvarolsson.com/blog/test-driven-develpment-for-scientists/
[Improve Your Python: Jeff Knupp: Understanding Unit Testing]:https://jeffknupp.com/blog/2013/12/09/improve-your-python-understanding-unit-testing/
[BIDS: Python Bootcamp: Test Driven Development]:https://www.youtube.com/watch?v=hrj8Wo34nvw
[Software Carpentry: Testing]:http://katyhuff.github.io/python-testing/

[Sharing Your Side Projects]:https://www.youtube.com/watch?v=uRul8QdYvqQ

[Basic Python Logging - Code Session]:https://www.youtube.com/watch?v=PX_xd2YjrsU
[Logging HOWTO]:https://docs.python.org/2/howto/logging.html
[Become A Logging Expert In 30 Minutes]:https://www.youtube.com/watch?v=24_4WWkSmNo

[Click Documentation]:http://click.pocoo.org/5/quickstart/
[Writing A Command-Line Tool In Python]:http://nvie.com/posts/writing-a-cli-in-python-in-under-60-seconds/

[Computational Biology: Using Cookiecutter To Set Up A Project]:http://tjelvarolsson.com/blog/using-cookiecutter-a-passive-code-generator/
[Computational Biology: Creating A Clean Pytyon Development Environment]:http://tjelvarolsson.com/blog/begginers-guide-creating-clean-python-development-environments/
[Computational Biology: How To Generate Beautiful Technical Documentation]:http://tjelvarolsson.com/blog/how-to-generate-beautiful-technical-documentation/
[Computational Biology: Five Steps To Add The Bling Factor Your Python Package]:http://tjelvarolsson.com/blog/five-steps-to-add-the-bling-factor-to-your-python-package/


[Python Tutor Visualizer]:http://www.pythontutor.com/visualize.html#mode=edit
[Python For Data Analysis]:http://www3.canisius.edu/~yany/python/Python4DataAnalysis.pdf
[Stanford CS 41: Python]:http://stanfordpython.com/
[Berkeley CS 88: Python Data Structure]:http://cs88-website.github.io/
[Harvard CS 109: Data Science]:http://cs109.github.io/2015/
[Berkeley BIDS Python bootcamp]:https://bids.berkeley.edu/news/python-boot-camp-fall-2016-training-videos-available-online
[Josh Bloom's Python Computing For Data Science]:https://github.com/profjsb/python-seminar
[Pandas Cookbook]:http://pandas.pydata.org/pandas-docs/stable/cookbook.html
[Udemy course]:https://www.udemy.com/learning-python-for-data-analysis-and-visualization/?ccManual=&couponCode=DEAL19