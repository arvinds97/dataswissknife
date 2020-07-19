# DataSwissKnife

A Handy Little Tool for your Data Science Operations

<p align="center"> 
   <img src="img/dsk_logo.png" width="400" height="300">
</p>

## About
A productivity tool for data science operations to make doing data science simpler and faster, especially for the non-technical, but domain-erudite audience. Created by [Ramshankar Yadhunath](https://ry05.github.io/) and [Srivenkata Srikanth](). 

## Etymology of the Project's Name
A [Swiss Army Knife](https://en.wikipedia.org/wiki/Swiss_Army_knife) provides multiple utilities and is often a term asociated with the ability to being applicable to any scenario at hand. However, if the task requires a significantly major operation the swiss knife is not a very useful tool. It would be wiser to replace it with something more complex.  

Similarly, the DataSwissKnife(abbreviated as DSK) is quite a useful tool to get your data science project started. It will help you perform a wide range of preliminary operations without having to write code, will guide you through creating an organized structure for your projects and will also help you maintain your results for later use. However, to build sophisticated models using complex feature engineering techniques or to generate complex visualizations is not within the scope of DSK.  

We highly recommend DSK as a tool to use when you first interact with your data. After the initial rounds of preliminary probing of the project at hand, it would be a better choice to use more sohpisticated tools or write explicit code for operations. We believe that the toughest part of a data science project is "to start it". DSK makes this part easy for you. 

## Intended Audience
DSK has been built by specifically keeping 3 kinds of users in mind. 

## Description
*Are you a data science beginner who wishes you had access to a tool that would help you watch data science in action **without writing code**? Or are you someone who understands the importance of data in your business, **but lack the technical grounding to code**? Or are you an expert-level researcher or data scientist who just wishes to do some preliminary analysis or build baseline models **without having to spend time writing code**?* 

If you fall into any of these categories, the DataSwissKnife project(abbreviated as DSK) will be of help to you. DSK is software that has been built with the purpose of aiding anybody who is familiar with necessary domain expertise to do preliminary data science.  

DSK lets users load a raw block of tabular data onto it and by asking relevant questions about the kind of work the user wants to do with the data; DSK performs the operations of **data cleaning**, **pre-processing**, **auto-generating visualizations** and even some **preliminary baseline modelling**. *DSK only makes use of these question-response interactions with the user and thus helps users perform preliminary data science without having to write any code to do so.*

Fig. 1 describes how DSK works. 

<p align="center"> 
   <img src="img/dsk_block_diagram.png">
</p>

<p align="center"> 
    Fig 1. DSK Block Diagram
</p>

### Background - Why is this important?

There is no doubt that data science is one field that has recently seen a surge in the number of people who want to work in it. From school students to experienced professionals, everybody is trying to figure a way to enter this mercurial field born out of the confluence of multiple disciplines. However, it is no secret that like all fields, getting into data science and being able to leverage data science abilities for your business is not an overnight job. It takes time to learn and apply these concepts. This time space might be further extended if individuals lack the technical expertise to readily analyse data. The problem with this extended time space is that it *delays the ability of a person to see how impactful data science can be for his or her work.* 

In fig. 2, the different consumers of data science have been broadly categorized. 

<p align="center"> 
   <img src="img/data_science_consumers.JPG">
</p>

<p align="center"> 
    Fig 2. Consumers of Data Science
</p>

#### Beginners

**Who:** Individuals who are beginners in data science and are only interested in learning. They are not looking to solve a complete problem yet. Can be further classified into students and professionals looking to make a career transition.

**Main Problem:** They need to know too much of theory before being able to start real analysis or develop models.

#### Non-Data Technicals
**Who:** Individuals who do not have a background in technical knowledge for data science, but are eagerly looking forward to using it for improving their businesses or for other purposes. They have the necessary domain knowledge they require.

**Main Problem:** They do not have the expertise to write code and neither do they have a lot of time to spare for learning how to write code.

#### Data Technicals

**Who:** Individuals with complete in-depth understanding of data science. They might be working professionals or working in academia. They know how to write code and are technically sound.

**Main Problem:** Data cleaning, generating preliminary baseline models, creating basic reports etc. becomes time-consuming and rather cumbersome. They will appreciate it if provided with a mechanism to automate these tasks(if not completely, at least partially).

### The Idea of DSK as a Solution

The gravity of the problem statement at hand calls for a new approach to data science. If data science has to be made simpler and easier for quickly generating essential results(without having to write code), full or partial control has to be transferred from the hands of the user to the system itself. In other words, *the system has to be automated.* Therefore, DSK is an attempt at setting the foundations for a system that will work in automated fashion to help users perform preliminary data science operations without writing code. Currently, DSK is prototypical and will be scaled to a full product in the future iterations of this project.  

Read more about the Vision of DSK [here](https://github.com/ry05/dataswissknife/blob/master/VISION.md).  

## The Working of DSK

The explanation of data flow through DSK has been [moved here](https://github.com/ry05/dataswissknife/blob/master/documents/How%20does%20DSK%20work.md). Head over to this link in order to understand how DSK helps an end user. Screenshots of the working have been included.  

If you would prefer seeing a video over reading about the working of DSK, [this video](https://bit.ly/3g36wS2) will help!

## Usage 

### Suggestion
It is recommended you download and run this project within a virtual environment, in order to ensure that the package installs do not tamper with the versions present in your system. The following links will help you learn why and how to use virtual environments in python.  
* http://www.python.education/2017/10/setting-up-virtual-environment-in-python.html (For Windows users)
* https://realpython.com/python-virtual-environments-a-primer/

### Instructions to run the tool

1. Download or clone this repository onto your local system

2. Extract the repository's contents

3. Navigate to the repository via the command line

4. Run the following command to install all necessary dependencies

   ```bash
   pip install -r requirements.txt
   ```

5. Run the following command to start the tool 

   ```bash
   python dataswissknife/main_code.py
   ```

   To avoid warnings being displayed, run with

   ```bash
   python -W ignore dataswissknife/main_code.py
   ```

6. The tool should start in your command line. Follow the prompts.

## Caveat 

While DSK will help with some very basic operations, we do not make a claim that DSK can replace efficient ways of learning and using data science i.e by writing code. Therefore, if you are a data science aspirant, we strongly urge you to continue learning your concepts and use DSK as a tool to help you generate some quick results.

## Support
DSK is a project that our team has worked on as a part of our final year project in our CSE undergraduate degree. Since we are making an attempt to deal with making data science more accessible and easy for everyone, we would strongly encourage the community's support in making DSK better and more user friendly with every future version.

In case of queries, suggestions or concerns, please feel free to reach me at *yadramshankar@gmail.com*

## Collaboration
Thank you for your interest in working on DSK. Unfortunately, we are currently not accepting contributions to the project. We assure you that this is because we have a few more features to add to DSK before we look at the future. As soon as DSK is ready for external collaboration, we will let you know. If you have noticed a bug or would just like to give us some feedback, you could fill up this [feedback form](https://forms.gle/1y8ZWYEj3LiQFVDJ6). If you wish to be notified of DSK's progress, let us know through the form. It's our word, the mails you get will not be spam😄

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) 
