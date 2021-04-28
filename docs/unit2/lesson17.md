##***<u>Lesson 17: A Normal Measure of Spread</u>***

###**Objective**
You will learn that standard deviation is another way to measure variability.

###**Vocabulary**
standard deviation (SD)

###**Essential Concepts**

!!! note "Lesson 17 Essential Concepts"
    The standard deviation is another measure of spread. This is commonly used by statisticians because of its role in common models and distributions, such as the normal model.

###**Lesson**
1. In your IDS Journal, create a two-column table and label the left column *Measures of Center (Central Tendency)* and the right column *Measures of Spread (Dispersion)*.

2. Review the information below about methods you have learned so far for measuring center and measuring spread in distributions. Place each of those measures in the correct column in your table.
 
3. A measure of center tells us the value that is typical, or in the center. A measure of spread tells us how variable, or how spread apart, the data are.


    Measures of Center: ***mean (average or typical value), median***
    
    Measures of Spread: ***mean absolute deviation (MAD), interquartile range (IQR)***

4. Below is another student's response to question #2 above. Do you agree or disagree?  


    <strong style="color: blue;"> Insert a sample student response. </strong>


5. A measure of center or a measure of spread depicts one value for a distribution. In your IDS Journal, write down what you think the value of each measure tells you about the data in the distribution.

6. Add the term **standard deviation (SD)** to your *Measures of Spread* column.

7. The standard deviation of a distribution is another way to measure spread, or variability. The standard deviation is similar to the mean absolute deviation (MAD).

8. Recall the formula for calculating the MAD:

    <center><img src="https://latex.codecogs.com/gif.latex?MAD=\frac{\sum_{i=1}^{n}&space;|x_i-\bar{x}|}{n}" title="MAD=\frac{\sum_{i=1}^{n} |x_i-\bar{x}|}{n}" /></center>

9. While the MAD measures the absolute distance of each data point from the mean, the standard
deviation *squares* the distances of each data point from the mean. Both methods result in positive
measurements because distance is always positive.

10. Observe the formula for calculating the standard deviation of a data set:

    <center><img src="https://latex.codecogs.com/gif.latex?MAD=\sqrt{\frac{\sum_{i=1}^{n}&space;(x_i-\bar{x})^2}{n}}" title="MAD=\sqrt{\frac{\sum_{i=1}^{n} (x_i-\bar{x})^2}{n}}" /></center>


11. Now you will calculate standard deviations of the dotplots using the formula in #10 above by using the 
*How Far Apart? (with standard deviation -- SD)* handout. 


    Follow the directions on the handout. When you get to part iii, compute the SD for plot (a) as you follow along the steps in the video.  Then compute the SD for plot (c) on your own.


    <strong style="color: black;"> To download a fillable copy of the [*How Far Apart? (with standard deviation -- SD)* handout (LMR_2.16)](https://ucla.box.com/s/9e6hkmoivhh1va85jlm5t5v47kwj686u) click on the document name</strong>. 

    
    <div align="center"><iframe src="https://app.box.com/embed/s/9e6hkmoivhh1va85jlm5t5v47kwj686u?sortColumn=date&view=list" width="500" height="400" frameborder="0" allowfullscreen webkitallowfullscreen msallowfullscreen></iframe>


    <strong style="color: blue;"> Insert a video showing step-by-step calculations of SD for plot (a). </strong>


12. Remember that you calculated MAD values in the *How Far Apart?* handout during [Lesson 4](lesson4.md) of this unit. Download a fillable copy of the [*How Far Apart?* handout (LMR_2.6)](https://ucla.box.com/s/8srlpc52picc5s4rtak9qbl4lkx4rnpy) <strong style="color: black;"> by clicking on the document name</strong>.


    <div align="center"><iframe src="https://ucla.app.box.com/embed/s/8srlpc52picc5s4rtak9qbl4lkx4rnpy?sortColumn=date&view=list" width="500" height="400" frameborder="0" allowfullscreen webkitallowfullscreen msallowfullscreen></iframe>


13. Compare and contrast the standard deviations that you just calculated with the MAD values that you obtained in LMR _2.6 from Lesson 4. 

14. In your IDS Journal, write down why you think the SD takes the square root of the average of the squares.

15. Using RStudio, you will now estimate the standard deviation for a few numerical distributions and explain the reasoning for your estimate. Load and view the atus data, then run the following functions one by one:

    **> histogram(~sleep, data=atus, breaks=seq(0,1500,by=100),**

    **> main = “Distribution of sleep in minutes”)**

    **> sleep_mean<-mean(~sleep, data=atus)**

    **> add_line(vline=sleep_mean)**


16. Observe the visual obtained and estimate the standard deviation. In your IDS Journal, report your estimate using the following sentence frame:

    <strong style="color: red;">“The time spent sleeping (in minutes) typically varies from the mean by <u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u>minutes.”</strong> 
    
17. <strong style="color: red;"> How did you come up with your estimate?</strong>

18. Obtain the actual standard deviation by running the function:

    **> sd(~sleep, data=atus)**

19. Compare your estimate to the actual standard deviation. 

20. Repeat this process with the following numerical variables: <strong style="color: purple;">Household Size</strong> and <strong style="color: purple;">Socializing</strong>. Refer to the functions below and report your estimate using the sentence frames provided:

    <strong style="color: purple;">Household Size:</strong>
    
    **> histogram(~household_size, data=atus, nint=13)**
    
    **> household_mean<-mean(~household_size, data=atus)**
    
    **> add_line(vline=household_mean)**

    <strong style="color: red;">“Household sizes typically vary from the mean by <u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u>people.” </strong>
    
    <strong style="color: purple;">Socializing:</strong>

    **> histogram(~socializing, data=atus, breaks=seq(0,2000,by=100))**
    
    **> social_mean<-mean(~socializing, data=atus)**
    
    **> add_line(vline=social_mean)**

    <strong style="color: red;">  “The time spent socializing (in minutes) typically varies from the mean by<u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u>minutes.” </strong> 

    **> sd(~socializing, data=atus)**


###**Reflection**
<strong style="color: red;">What are the essential learnings you are taking away from this lesson?</strong> 