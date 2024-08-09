# Defining Data Science



## What is Data?
In our everyday life, we are constantly surrounded by data. The text you are reading now is data.  The list of phone numbers of your friends in your smartphone is data, as well as the current time displayed on your watch. As human beings, we naturally operate with data by counting the money we have or by writing letters to our friends.


## What is Data Science?

In [Wikipedia](https://en.wikipedia.org/wiki/Data_science), **Data Science** is defined as *a scientific field that uses scientific methods to extract knowledge and insights from structured and unstructured data, and apply knowledge and actionable insights from data across a broad range of application domains*.

This definition highlights the following important aspects of data science:

* The main goal of data science is to **extract knowledge** from data, in other words - to **understand** data, find some hidden relationships and build a **model**.
* Data science uses **scientific methods**, such as probability and statistics.  In fact, when the term *data science* was first introduced, some people argued that data science was just a new fancy name for statistics.  Nowadays it has become evident that the field is much broader.    
* Obtained knowledge should be applied to produce some **actionable insights**, i.e. practical insights that you can apply to real business situations.
* We should be able to operate on both **structured** and **unstructured** data.  We will come back to discuss different types of data later in the course.
* **Application domain** is an important concept, and data scientists often need at least some degree of expertise in the problem domain, for example: finance, medicine, marketing, etc. 

Since data is pervasive, data science itself is also a broad field, touching many other disciplines.

<dl>
<dt>Databases</dt>
<dd>
A critical consideration is **how to store** the data, i.e. how to structure it in a way that allows faster processing.  There are different types of databases that store structured and unstructured data, which <a href="../../2-Working-With-Data/README.md">we will consider in our course</a>.
</dd>
<dt>Big Data</dt>
<dd>
Often we need to store and process very large quantities of data with a relatively simple structure.  There are special approaches and tools to store that data in a distributed manner on a computer cluster, and process it efficiently.
</dd>
<dt>Machine Learning</dt>
<dd>
One way to understand data is to **build a model** that will be able to predict a desired outcome.  Developing models from data is called **machine learning**. You may want to have a look at our <a href="https://aka.ms/ml-beginners">Machine Learning for Beginners</a> Curriculum to learn more about it.
</dd>
<dt>Artificial Intelligence</dt>
<dd>
An area of machine learning known as artificial intelligence (AI) also relies on data, and it involves building high complexity models that mimic human thought processes.  AI methods often allow us to turn unstructured data (e.g. natural language) into structured insights. 
</dd>
<dt>Visualization</dt>
<dd>
Vast amounts of data are incomprehensible for a human being, but once we create useful visualizations using that data, we can make more sense of the data, and draw some conclusions. Thus, it is important to know many ways to visualize information - something that we will cover in <a href="../../3-Data-Visualization/README.md">Section 3</a> of our course. Related fields also include **Infographics**, and **Human-Computer Interaction** in general. 
</dd>
</dl>
## Types of Data

As we have already mentioned, data is everywhere.  We just need to capture it in the right way!  It is useful to distinguish between **structured** and **unstructured** data. The former is typically represented in some well-structured form, often as a table or number of tables, while the latter is just a collection of files.  Sometimes we can also talk about **semi-structured** data, that have some sort of a structure that may vary greatly.

| Structured                                                                   | Semi-structured                                                                                | Unstructured                            |
| ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | --------------------------------------- |
| List of people with their phone numbers                                      | Wikipedia pages with links                                                                     | Text of Encyclopedia Britannica        |
| Temperature in all rooms of a building at every minute for the last 20 years | Collection of scientific papers in JSON format with authors, data of publication, and abstract | File share with corporate documents     |
| Data for age and gender of all people entering the building                  | Internet pages                                                                                 | Raw video feed from surveillance camera |

## Where to get Data

There are many possible sources of data, and it will be impossible to list all of them! However, let's mention some of the typical places where you can get data:

* **Structured**
  - **Internet of Things** (IoT), including data from different sensors, such as temperature or pressure sensors, provides a lot of useful data.  For example, if an office building is equipped with IoT sensors, we can automatically control heating and lighting in order to minimize costs. 
  - **Surveys** that we ask users to complete after a purchase, or after visiting a web site.
  - **Analysis of behavior** can, for example, help us understand how deeply a user goes into a site, and what is the typical reason for leaving the site.
* **Unstructured**
  - **Texts** can be a rich source of insights, such as an overall **sentiment score**, or extracting keywords and semantic meaning.
  - **Images** or **Video**. A video from a surveillance camera can be used to estimate traffic on the road, and inform people about potential traffic jams.
  - Web server **Logs** can be used to understand which pages of our site are most often visited, and for how long.
* Semi-structured
  - **Social Network** graphs can be great sources of data about user personalities and potential effectiveness in spreading information around.
  - When we have a bunch of photographs from a party, we can try to extract **Group Dynamics** data by building a graph of people taking pictures with each other.

By knowing different possible sources of data, you can try to think about different scenarios where data science techniques can be applied to know the situation better, and to improve business processes. 