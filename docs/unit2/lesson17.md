##***<u>Lesson 17: A Normal Measure of Spread</u>***

###**Objective:**
You will learn that standard deviation is another way to measure variability.

###**Vocabulary:**
standard deviation (SD)

###**Essential Concepts:**

!!! note "Essential Concepts: "
    The standard deviation is another measure of spread. This is commonly used by
    statisticians because of its role in common models and distributions, such as the Normal Model.

###**Lesson:**
1. In your DS journals, <strong style="color: red;">create a two-column table and label the left-column as
*Measures of Center (Central Tendency)* and the right column as *Measures of Spread
(Dispersion)*.</strong>

2. Review the information below about methods you have learned so far for measuring center and
measuring spread in distributions. Place those measures in the corresponding column in your table.
 
A measure of center tells us the value that is typical, or in the center. A
    measure of spread tells us how variable, or how spread apart, the data are.
    Measures of Center: ***mean (average or typical value), median***
Measures of Spread: ***mean absolute deviation (MAD), interquartile range (IQR)***

3. Observe a student's response when asked to place terms in the correct column. Do you agree or disagree.  <strong style="color: blue;"> Insert a sample response </strong>

4. A measure of center or a measure of spread depicts one value for a distribution.
Answer the following question in your DS journal:

    100.  <strong style="color: red;">What does the value of each measure tell us about the data in the distribution? </strong>


5. Add the term **standard deviation (SD)** to your *Measures of Spread* column.

6. The standard deviation of a distribution is another way to measure spread, or
variability. The standard deviation is similar to the mean absolute deviation (MAD).

7. Recall the formula for calculating the MAD:

    <center><img src="https://latex.codecogs.com/gif.latex?MAD=\frac{\sum_{i=1}^{n}&space;|x_i-\bar{x}|}{n}" title="MAD=\frac{\sum_{i=1}^{n} |x_i-\bar{x}|}{n}" /></center>

8. While the MAD measures the absolute distance of each data point from the mean, the standard
deviation squares the distances of each data point from the mean. Both methods result in positive
measurements because distance is always positive.

9. Recall that you calculated MAD values in the *How Far Apart?* handout ([LMR_2.6](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.6_How Far Apart.pdf))
during [Lesson 4](lesson4.md) of this unit. You will need LMR_2.6 in step 12. 

10. Observe the formula for calculating the standard deviation of a data set:

    <center><img src="https://latex.codecogs.com/gif.latex?MAD=\sqrt{\frac{\sum_{i=1}^{n}&space;(x_i-\bar{x})^2}{n}}" title="MAD=\sqrt{\frac{\sum_{i=1}^{n} (x_i-\bar{x})^2}{n}}" /></center>


11. You will now complete the *How Far Apart? (with standard deviation -- SD)* handout 
([LMR_2.16].(../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.16_How Far Apart SD.pdf)) You will calculate standard deviations of the dotplots using the formula listed above. Follow the directions on the handout. When you get to part iii, compute the sd for plot (a) as you follow along the steps in the video.  Then compute the sd for plot (c) on your own.
<div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://curriculum.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.16_How Far Apart SD.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_2.16](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.16_How Far Apart SD.pdf)</div>
<strong style="color: blue;"> Include a video showing step by step calculation of sd for plot (a) </strong>

12. Compare and contrast the standard deviations that you just calculated with the MAD
values that you obtained in LMR _2.6 from lesson 4. 

13. Answer the following in your SD journal. <strong style="color: red;">Why do you think the SD takes the square root of the average of the squares.</strong>

14. To reinforce your conceptual understanding of standard deviation, you will
estimate the standard deviation for a few numerical distributions and explain the reasoning for
your estimate. You will use RStudio for the next activity. Load and view the atus data, then run the following functions one by one:

    **> histogram(~sleep, data=atus, breaks=seq(0,1500,by=100),**

    **&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;main = “Distribution of sleep in minutes”)**

    **> sleep_mean<-mean(~sleep, data=atus)**

    **> add_line(vline=sleep_mean)**

   

15. Observe the visual obtained and estimate the
standard deviation. In your DS journal, report your estimate using the
following sentence frame:

<strong style="color: red;">    “The time spent sleeping (in minutes) typically varies from the mean by <u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u>minutes.”</strong> 
<strong style="color: red;"> How did you come up with your estimate? </strong>

16. Obtain the actual standard deviation by running the function:

    **> sd(~sleep, data=atus)**

17. Compare your estimate to the actual standard deviation. 

18. Repeat this process with the following numerical variables: Household size and Socializing. Functions are provided below.

    Household size
    
    **> histogram(~household_size, data=atus, nint=13)**
    
    **> household_mean<-mean(~household_size, data=atus)**
    
    **> add_line(vline=household_mean)**

 <strong style="color: red;">   “Household sizes typically vary from the mean by <u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u>people.” </strong>

Socializing
    
    **> histogram(~socializing, data=atus, breaks=seq(0,2000,by=100))**
    
    **> social_mean<-mean(~socializing, data=atus)**
    
    **> add_line(vline=social_mean)**

 <strong style="color: red;">  “The time spent socializing (in minutes) typically varies from the mean by
    <u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u><u>&nbsp;&nbsp;&nbsp;&nbsp;</u>minutes.” </strong>
    
    **> sd(~socializing, data=atus)**

