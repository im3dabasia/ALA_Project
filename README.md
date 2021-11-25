## Title: Predicting traffic flow problems at circles using Gauss Jordan elimination and markov chains

##### Group Number:18
##### Group Name:Drifters
##### Student Roll Number/Name:
- Khushi Mandavia AU2020245
- Eshaan Dabasiya AU2020048
- Nand Patel AU2040183
- Helly Thakkar AU2020130

---

## Abstract:
#### Keywords - Analyse, Gauss Jordan elimination, linear algebra, linear equations, Markov chains, predict, traffic flow.
The primary goal of our project is to predict traffic flow patterns using concepts of linear algebra such as the Gauss Jordan elimination method and linear equations. Later, the use of Markov chains will aid us to anticipate potential patterns in the traffic flow. It will be straightforward to obtain the number of cars that were unknown number by using linear equations and assuming that the number of vehicles entering and leaving remains unchanged. Taking n variables for n roads is a sensible way to proceed. The Ghana study demonstrates the effectiveness of the proposed idea of applying linear algebra to traffic flow [1].

## I. INTRODUCTION

Linear algebra is an omnipresent branch of mathematics, and its applications range from machine learning, mechanics, and even Google’s page rank algorithm uses concepts of applied linear algebra. Apart from that, our everyday lives are a concoction of decisions based on future predictions like the weather or stock market decisions or recommendations on Netflix or which road should one take at what time to avoid maximum traffic and much more. This project aims to use the concepts of linear algebra to predict traffic flow problems at circles using Gauss Jordan elimination and Markov chains. The Gauss Jordan Elimination algorithm solves a system of linear equations by representing them as an augmented matrix to find its reduced row-echelon form, which gives the values of the variables. A Markov chain is a series of events where the probability of the preceding event solely determines the likelihood of each event. With rapid urbanization, traffic flow concerns are increasing, and hence we plan to analyse traffic flow problems to help people get an idea about traffic situations in circles.

## II. BACKGROUND

Making our lives easier, the concepts of linear algebra are a great gem to us. Our primary focus is to analyse the traffic flow problem using those concepts. Using raw data where we know the number of incoming and outgoing vehicles, we can construct a system of linear equations, which, when solved, gives all the information we need to understand the situation of traffic. It is possible to develop a model that forecasts traffic patterns by repeating the experiment multiple times. As mentioned earlier, the key reason for this project is the increasing traffic in certain areas and its downside. The desired outcome for the project is to get a model that efficiently forecasts/analyses traffic patterns in a given area.

## III. MOTIVATION

With the increase in population growth and rapid urbanization in the Indian economy, concerns regarding traffic congestion have risen. These have been of great interest to the government because of their negative impacts causing disturbance to the human society and environment. It is also a concern for people who need to commute from home to work every day because traffic congestion is time-consuming. Therefore, we intend to build a mathematical model that can help analyse the existing traffic situation and achieve optimum traffic management in the city.

## Results:
## Markov chains 
The idea here is very simple. As the definition of Markov chains says that the output of the next state can be predicted from the current state and not the previous States. This the absolute principle we have applied in our calculations.

We made a 4*4 matrix let's call this Matrix A for simplicity. In which we have data that consists of monthly cars at each crossroad. The months are JAN, FEB, MAR, APR. 

The basic property is that the column vectors should add up to the maximum probability that is 1. For it to be considered a markov matrix. Then we made a 4*1 probability matrix. Let's call this X. This is the prediction cum probability matrix that is computed from the current state ie. April month. Now we will multiply these two matrices.

AX = X1

(4*4) * (4*1) = (4*1)

Then we multiplied the result X1 with the same old constant matrix A. To obtain the number of cars passing through the 4 crossroads.

Our results are very convincing and are almost/ close to similar. We used Markov chains property to predict distant future values.
## References:
##### 1.Paper on Markov Chains helped in:
Exploration of interesting probability theories for the achievement of twin goals of maximization of traffic flow efficiency and minimization of congestion
Link: https://scholar.rose-hulman.edu/cgi/viewcontent.cgi?article=1187&context=rhumj
##### 2. Application of System of Linear Equations to Traffic Flow for a Network of Four One-Way Streets in Kumasi, Ghana is a very similar study as we wish to conduct. This paper helped us in:
•	Critical Analysis of the case study on the causes, and potential solutions of traffic congestion on the streets in Kumasi 
•	Mathematical motivation to achieve desired, targeted results for our project.
Link: http://www.m-hikari.com/ijcms/ijcms-2014/13-16-2014/aduIJCMS13-16-2014.pdf
##### 3. Some of the additional resources consulted are mentioned as follows. They enhanced our perspectives and understanding of the topic.
Links:
•	https://metrocouncil.org/Transportation/Planning-2/Reports/Highways-Roads/Mobility-Needs-Analysis/The-Negative-Effects-of-Traffic-Congestion.aspx
•	https://applicationanthologys16.wordpress.com/2016/04/21/linear-algebra-and-traffic-flow/
##### Link to the Uploaded YouTube Video

