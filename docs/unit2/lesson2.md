##***<u>Lesson 2: What Does Mean Mean?</u>***

###**Objective:**
You will learn that values that gather around the center of a distribution show the typical value. This
value is also referred to as the mean, or average.



###**Vocabulary:**
measures of central tendency (or center), typical, measures of variability (or spread), mean, average,
balancing point

###**Essential Concepts:**

!!!note "Essential Concepts: "
    The center of a distribution is the 'typical' value. One way of measuring the center is
    with the mean, which finds the balancing point of the distribution. The mean gives us the typical value, but
    does not tell the whole story. We need a way to measure the variability to understand how observations
    might differ from the typical value.

###**Lesson:**
 1. <strong style="color: red;">Read the following definitions of Measures of Central Tendency and Measures of Variability then in your DS journal, paraphrase the definition as if you were explaining it to a 5th grader:</strong>


     100. Measures of central tendency. A value that shows the tendency of quantitative data
    to gather around a central, or ***typical***, value. Also known as measures of ***center***.
    
     101. Measures of variability. Values that show how much the quantitative data varies.
    Also known as measures of ***spread***. 

2. <strong style="color: red;">Refer to the image below, these are students' definitions of the two terms. Choose one that you strongly agree or disagree with and write your answer in your DS journal.</strong>

<strong style="color: blue;"> Insert visualization here showing different definitions of students about Measures of Center and Measures of Variability</strong>

3. You will be learning more about these measures and what they
tell us about data as we progress through this unit.

4. Do you still remember how to compute the **mean**, or **average**? 

5. <strong style="color: red;">In your journal, write a sentence or two explaining how to compute the **mean**, or **average**.</strong>

6. Another way to find the mean is to find the **balancing point** of a distribution. You will learn about
the balancing point via the activity in Steps 7 & 8.

7. You will need your handout for this activity *Pennies on a Ruler*  ([LMR_2.2](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.2_Pennies on a Ruler.pdf)) along with a marker, ruler, tape, and 6
pennies. 


<div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://curriculum.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.2_Pennies on a Ruler.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_2.2](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.2_Pennies on a Ruler.pdf)</div>


8. <strong style="color: red;">Follow the direction in your handout and you write your findings throughout the
activity in your DS journal. </strong>It is very important  to understand that the idea that <u>the mean of a distribution can be identified by finding
its balancing point. </u>

9. Consider the visualization below showing the results of a survey done in one class about their  **Personality Color**. Note what are your predominant and secondary colors when you yourself did the survey.

<strong style="color: blue;"> Insert 4 visualizations here showing different dot plots in 4 different colors </strong>

10. Find the dotplot <span style="color:blue">***Blue***</span> (whether or not that was your predominant color) when you took the survey. Refer to the picture to amswer the following questions: 

     a. <strong style="color: red;"> What do you think the typical <span style="color:blue">***Blue***</span> score is(predicted balancing point)? </strong>

     b. <strong style="color: red;"> Are the data roughly symmetric? Where is the balancing point of this distribution? </strong> Once a value is chosen, describe the location of the point in the dot plot in your journal.
    

11. <strong style="color: red;">Compute the mean <span style="color:blue">***Blue***</span> score for the entire class and compare this value to the your own prediction of the balancing point. </strong>You may not remember exactly how to
compute the mean, so be reminded of the general algorithm or refer back to the 
responses from Step 5 above.

12. The formula for calculating the mean:
<center><img src="https://latex.codecogs.com/gif.latex?\bar{x}=\frac{&space;\sum_{x=1}^{n}&space;x_i}{n}" title="\bar{x}=\frac{ \sum_{x=1}^{n} x_i}{n}" /></center>

13. Now that you have calculated the mean for the <span style="color:blue">***Blue***</span> score, <strong style="color: red;">copy the formula in your DS journal and label each symbol in
the formula with a step in their algorithm for finding the mean, and write the meaning of the
symbols in the formula in your journal.</strong> For example: ***x<sub>i</sub> represents each individual data point and n
represents the total number of observations.

14. <strong style="color: red;">Sketch the dot plot <span style="color:blue">***Blue***</span> in your journal. Indicate the location of the calculated mean on your sketch by drawing a vertical line at the value
on the x-axis.</strong> Notice how close the mean value is to your predicted balancing point.

15. <strong style="color: red;">Using the visualization of *Personality Color* survey data from Step 9, compute the mean score for each of the other three personality colors.</strong>

16. During the [next lesson](lesson3.md), you will learn about another method that can be
used for measuring the center of a distribution.

17. There is an even easier method of calculating the mean – using
RStudio! The command RStudio uses to calculate the mean incorporates the
algorithm of summing up all the data and dividing by the total number of observations. You will be able to use this command for quick calculations now.

    **<u>Note:</u>** If you have already “*Exported*, *Downloaded*, *Imported*” the class’s Personality
    Color campaign data, you can simply use the exact command below to calculate the
    mean <span style="color:blue">***Blue***</span> score:

    &nbsp;&nbsp;&nbsp;&nbsp;**> mean(~blue, data = colors)**

    In general, the function can be denoted as follows:

    &nbsp;&nbsp;&nbsp;&nbsp;**> mean(~variable, data = datafile)**

   
18. <strong style="color: red;">Write short answer entry in your journal how the mean value of a group of data could be
used to easily describe complicated things.</strong> For example, instead of giving someone the entire
class’s <span style="color:blue">***Blue***</span> scores, we could just tell him/her the mean score and he/she would have a general
idea about the class.



###<p style="background: black; color: white; text-align: center;">**Homework**</p>
Complete the *Mr. Jones Mile Rule Times* handout ([LMR_2.3](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.3_Mr. Jones Run Times.pdf)) for homework. You
can practice finding the mean of distributions by determining a balancing point for the data.  The mean values in part (3) do NOT need to be exact.
<div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://curriculum.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.3_Mr. Jones Run Times.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_2.3](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.3_Mr. Jones Run Times.pdf)</div>


1. <strong style="color:red">What kind of plots did Mr. Jones create for his classes? </strong>

2. <strong style="color:red">Where does each distribution balance? Find and label the balancing point of each distribution.</strong>


3. <strong style="color:red">Based on the balancing points you found, what would you say the mean mile run time is for
each class?</strong>

    i. Period 1: <u><span style="color:grey">***&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***</span></u>

    ii. Period 2: <u><span style="color:grey">***&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***</span></u>
    
    iii. Period 3: <u><span style="color:grey">***&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***</span></u>
    
    iv. Period 4: <u><span style="color:grey">***&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***</span></u>