# GA-NLP-Projects
Submitted projects from the Great Learning Generative AI &amp; Natural Language Processing class
## Overview

This repository contains Jupyter notebooks I created for project assignments submitted during my [Generative AI for Natural Language Processing](https://www.mygreatlearning.com/generative-ai-for-nlp). The class is offered by the University of Texas at Austin [McCombs School of Business](https://onlineexeced.mccombs.utexas.edu/), and spans a total of 4 graded modules in 12 weeks focusing on Generative AI and NLP. There are two submitted and evaluated projects with this course.

As these are class assignments, you'll see the progression of my skills throughout the program. Each of these projects is specifically designed and bounded to focus on the topic introduced in the module, so none of these are entirely suitable for real-world applications. They are simplified examples to learn specific concepts.

The data sets for these assignments are usually publically available from sites like Kaggle; I've included links to the versions of the data I used to complete the assignment.

I was able to execute all of these notebooks in practical timeframes on a local desktop computer with a consumer - albeit upscale - GPU card. YMMV.

## Contents
### Mid-term Project: Generative AI powered Support Ticket Categorization
_Prompt Engineering and Generative AI_

__Objective:__ Develop a Generative AI application using a Large Language Model to automate the classification and processing of support tickets. The application will aim to predict ticket categories, assign priority, suggest estimated resolution times, generate responses based on sentiment analysis, and store the results in a structured DataFrame.

Specific skills include retrieving models from Huggingface, loading them and configuring them with Llama, constructing a detailed system message with instructions to complete the assignment, as well as working with the JSON output. Developing a set of observations and recommendations are also an important component of this project.

* Notebook: [Support Ticket Categorization](https://github.com/jreves/GA-NLP-Projects)
* Dataset:[ Support Ticket Text.csv](https://github.com/jreves/GA-NLP-Projects)

### Final Project: Data Science Assistant
_Generative AI Applications with LangChain_

__Objective:__ The objective of this project is to develop a Generative AI solution using the LangChain framework and a Large Language Model to automate tasks pertaining to Data Analysis, Data Science, Database Querying and Retrieval-Augmented Generation. This will be broken down into several sub-tasks, each of which will automatically be performed by our Large Language Model purely by prompting it in the right direction.

Skills include using the OpenAI API interface, creating agents for EDA including plot generation, hypothesis testing, and classification with a variety of ML models. We define an agent for SQL database queries with math skills, and finally implement a RAG solution with a vector database, loading additional local content and enabling our agent to make web queries through the google search API.

* Notebook: [Data Science Assistant](https://github.com/jreves/GA-NLP-Projects)
* Dataset: [SAHeart.csv](https://github.com/jreves/GA-NLP-Projects)
* Dataset: [sample.db](https://github.com/jreves/GA-NLP-Projects)
* Dataset: [cpu-intro.pdf](https://github.com/jreves/GA-NLP-Projects)
