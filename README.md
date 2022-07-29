# Astronomy : Machine Learning 
This project deals with applications of Machine Learning techniques in the field of Astronomy and Astrophysics.

Cataloging various types of objects such as pulsars/exoplanets/QSOs etc, through sky surveys, is very important in Astronomy. Now we have many telescopes/sky surveys that generate a huge amount of data everyday. After data processing, astronomers have to classify (or check if the data corresponds to the type of object we are looking for/trying to find) the objects. After the data processing and some analysis, astronomers are left with lakhs of candidates. People sitting and classifying each of them is infeasible and impossible. So we will have to train ML algorithms to do this for us. 

In this project, we first learnt basics of ML and then applied it to one simple astronomical context of classifying the objects into stars/galaxies/QSOs based on their redshifts and magnitudes. We did 3 assignments in this project.

## Details

We did this project in three parts :

**Part 1** : Linear and Logistic Regression \
**Part 2** : Neural Networks \
**Part 3** : Astronomy and Final Application using Decision Trees

### Part 1 
This part was done for about 2-2.5 weeks : 21 April - 5 May.

We read about **linear and logistic regression**. We also followed weeks 1,2 and 3 of lectures on ML by Andrew NG on coursera. Then we learnt how to implement these on python using **sklearn** and also from scratch. 

We were given a 2 part **assignment** for this part :
1.  [Linear Regression](https://github.com/AdarshR-M/SoC-2022-Astro-ML/blob/main/Regression/Linear_Regression.ipynb) : Was on finding life expectancy, given various parameters such as per capita income etc.
2.  [Logistic Regression](https://github.com/AdarshR-M/SoC-2022-Astro-ML/blob/main/Regression/Logistic_Regression.ipynb) : Was on trying to predict whether a passenger on Titanic survived or not (some part was training set and some test data).

### Part 2
This part was done for about 2-3 weeks : 6 May -  20 May (midsems) 6 June - 12 June (for those who couldn't complete).

We were given a book and various resources on **neural nets** and the **keras** package.

One **assignment** on training Neural Net on MNIST data : [MNIST](https://github.com/AdarshR-M/SoC-2022-Astro-ML/blob/main/Neural%20Networks/MNIST.ipynb).

### Part 3
(there was a big gap due to our endsems)
This part was done for about 3 weeks : 2 July - till end!

We were given readings on **Astronomy** and **decision trees**.

We had one final assignment where we had a huge data set of redshifts, maginitudes in various bands (V,B,I etc). We had to classify the objects into Stars, Galaxies and QSOs using **decision trees and random forests** using **sklearn** : [Final Astronomy Application](https://github.com/AdarshR-M/SoC-2022-Astro-ML/blob/main/Astronomy%20Application/Classification_of_AstroObjects.ipynb).

## The way ahead ...
Till here we have learnt the basics of ML and applied it to a simple astronomical context. Astronomy has many more interesting senarios!! For example, trying to identify if a candidate star has a planet orbiting or trying to identify whether an object is a pulsar or FRB or neither, by analysing their light curves.
