# Day 1
## Topics Covered
1. **Touch Typing**
     * Touch typing allowed me to type without looking at the keyboard, significantly improving typing speed and efficiency
     * By using all fingers and adopting proper hand positioning, touch typing helped me reduce strain on the hands

2. **Linkedin profile updation**
     * Learned about the importance of a well-built Linkedin profile.
     * Important points on job hunting.

3. **GitHub and Github Pages**
     * Learned how to make a repository and to add a readme.md file.
     * GitHub pages helps to make websites where we can showcase projects
       
3. **Overleaf**
     * Helped me to make a professional resume.
 4. **Visual Studio Code**
     * helps to generate real time output while coding.      
   



# Day 2
1. **JIRA**



# Day 3
## Topics Covered
1. **History of AI**
     * Learned about the different periods of AI like winter of Ai and the boom of AI.
     * Learned about different founders and years relevent in the history of AI.

2. **Alan Turning and Turing Test**
     * Founder of AI.
     * Turing Test - If a human is interacting with a computer and another human unaware of which is which and cannot tell the difference between them, then we have achived true artificial intelligence .

3. **Neural Networks and Neuroplasticity**
     * perceptron- Single layer of neuron model.
     * Neural Network - brain like structure.
     * Applications of perceptron.
       
3. **Machine Learning**
     * Field of AI giving computers the ability to learn like humans.
       
4. **Learning models**
     * Supervised Learning- with labels  - Classsification, Regression.
     * Unsupervised learning - without labels -  Association,Clustering.

5. **Programming Languages**
     * Compiled Language.
     * Interpreted Language.

6. **Python**
     * Learned about different ibraries like numPy and pandas.
       

7. **Data Science life cycle**
     * Learned about different processes in Data Science .
  
# Day 4
## Topics Covered
**Measures of central tendency**
*Mean* - average
*Median*- middle value
*Mode* - most repeated value
*Percentile* - median is the 50th percentile 
*Quartiles* -
 Q1- 25th percentile
Q2- 50th percentile
Q3- 75th percentile

IQR = Q3-Q1
LB = Q1-1.5*IQR
UB = Q3+1.5*IQR

Interquartile range
Min
Max

**Finding outliers using Quartiles** 

Measures of dispersion
Range
Standard deviation
Variance & Standard deviation  (x-)2N
Z score -    x- 
Confidence interval


**Correlation coefficient(-1 to 1)**
*Pearson correlation coefficient*
*Sphearman’s rank correlation*

**Scatter plot**
Visually inspecting correlation b/w two variables


**Distribution Curve , Histogram**
frequency / relative frequency

**Probability density function**
Cumulative distribution function
Advance compared to pdf 


**Boxplot**
Shows median(Q2),Q1,Q3,lowerbound,upperbound,
Outliers 


# Day 5
## Topics Covered
The probability of getting heads or tails in a coin toss is 0.5 because the cumulative sum will reach a value which is near to 0.5.

Gaussian distribution - mean value can be anywhere. Not necessarily zero centred.
Nomal distribution - special case of gaussian distribution. Zero centred mean value.

Sampling 

Population - entire set
Sample - a portion of the set

**Central limit theorm** - https://onlinestatbook.com/stat_sim/sampling_dist/
Sampling distribution 

Null hypothesis - operations does not have effect
Alternate hypothesis - operations have effect

Significance level - even a small p has significance.

Z = x -   /N
 x  sample mean
   population 
  population of SD

t =  x -     s/N
 s sample’s SD

https://datatab.net/tutorial/hypothesis

# SQL NOTES 
## Topics Covered
Why databases
Alternatives: CSV, txt,xlsx
DB makes life simpler. easier and faster
Done without much programming background
Backup data at multiple places
Oracle, MySQL,SQLServer

Relational and non-relational databases
Relational - stores data in structured tables with rows and columns using a predefined schema
Non-relational MongoDB offers more flexibility by storing data in various formats, such as doc, key-value pairs, or graphs—less structured and more dynamic.
Relational datasets are ideal for highly structured data
Non-relational excels in handling large volumes of diverse data with rapid scalability

Tables
Movie_id,movie_name,actor_id,actor_name,gender
1	Spiderman,2009,aid_1, name, Male
2	Spiderman,2009,aid_2, name, Male
Here only some parts of the data changes, other parts are copied.

Table1 : movie_id,movie_name,year
Table2 : movie_id,actor_id,actor_name,gender
Table3 : movie_id,actor_id
Here movie_id and actor_id are unique

There is a primary key associated with each table

Why SQL
Structured Query Language
Begin - 1970 - IBM
Create
Read
Update
Delete


Not a general-purpose programming language, is domain specific.
general-purpose programming language - create web apps,games,OS etc.
Python C++ are procedural programming language,step by step instruction provided.
Declarative programming language

Execution
Parser,compiler
Parser: understand query
Compiler: optimizer (optimaal way to generate) & generated code.

IMDB dataset
Website owned by amazon.com : has data on movies
388,269 movies
817,718 actors
86,880 directors
Tables
Schema: all tables and relationship

Logical operators
AND,OR,NOT,ALL,ANY,,BETWEEN,EXIST,,IN,LIKE,SOME


# Day 20
## Topics Covered
Datatypes
Continuous 
Discrete
Classification and Regression

Visualization
Matplotlob
Figures
Axis labels
Sub figures
Ticks
Seaborn 

Types of plot
Line plot
Bar chart
Pie charts
Histogram
CDF plot
KDE plot
Scatter plot
With colour
Heat maps
Box plots
    



Numeric - int, float - any number types are called continuous.
                                If it is a defined set of variables it is called discrete.
Categorical - fixed values.
Input columns are called features and predicted columns are called labels.

Feature Extraction and Transformation

Features and Labels
Text data
BoW
TFIDF
Feature Engineering
Feature orthogonality - different info - combining adds value. Better for training.
Cosine similarity - u.v/ |u|.|v|

Feature colinearity - f1 , f2 = 1.5f1, f3   - f1 and f2 are colinear. 
Feature slicing - (height, weight,hair colour, eye colour, country)-> features. There are only two countries. Not equally distributed. If this is given as training data,accuracy will decrease for single model. Dataset can be divided into D1 And D2. separate models are built for two different datasets. 

 Indicator variable
Feature binning - adds a new column using certain XOR conditions.  This is called indicator variable. When this is done on a multiclass, called feature binning.

Mathematical transforms
Logarithms
FFT&STFT












