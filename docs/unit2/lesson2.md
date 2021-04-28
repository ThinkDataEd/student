##***<u>Lesson 2: What Does Mean Mean?</u>***

###**Objective**
You will learn that values that gather around the center of a distribution show the typical value. This
value is also referred to as the mean, or average.



###**Vocabulary**
measures of central tendency (or center), measures of variability (or spread), typical, mean, average,
balancing point

###**Essential Concepts**

!!!note "Lesson 2 Essential Concepts"
    The center of a distribution is the "typical" value. One way of measuring the center is
    with the mean, which finds the balancing point of the distribution. The mean gives us the typical value, but does not tell the whole story. We need a way to measure the variability to understand how observations might differ from the typical value.

###**Lesson**
 1. Read the following definitions for measures of central tendency and measures of variability. 

     100. **Measures of central tendency**. A value that shows the tendency of quantitative data
    to gather around a central, or **typical**, value. Also known as measures of **center**.
    
     101. **Measures of variability**. Values that show how much the quantitative data varies.
    Also known as measures of **spread**. 

2. Then in your IDS Journal, paraphrase the definition as if you were explaining it to a 5th-grader:

3. You will be learning more about these measures and what they tell us about data as we progress through this unit.

4. Do you still remember how to compute the **mean**, or **average**? 

5. In your IDS Journal, write a sentence or two explaining how to compute the mean, or average.

6. Another way to find the mean is to find the **balancing point** of a distribution. You will learn about
the balancing point via the activity in Steps 7 & 8.

7. Using the [IDS Balancing Point app](https://www.idsucla.org/wp-content/uploads/mean.html), answer the questions in the *Balancing Point* handout.  


    <strong style="color: black;">Click on the document name to download a fillable copy of the </strong>[*Balancing Point* handout (LMR_2.2b)](https://ucla.box.com/s/ck7j7t1427lj4x32584tg32g111q13ip)</strong>.


    <iframe src="https://app.box.com/embed/s/ck7j7t1427lj4x32584tg32g111q13ip?sortColumn=date&view=list" width="500" height="400" frameborder="0" allowfullscreen webkitallowfullscreen msallowfullscreen></iframe>


8. As you answer the questions in the  in the *Balancing Point* handout, write any additional wonderings or thoughts you may have in your IDS Journal. It is very important to understand the idea that <u>the mean of a distribution can be identified by finding its balancing point. </u>

9. Consider the visualization below showing the results from the *Personality Color* survey from another class. Recall your own predominant and secondary colors from when you completed the survey.


    <iframe src="https://drive.google.com/file/d/1uQhG7arlBTQzwh-lnKeye-Cgc7C_blhQ/preview" width="640" height="480"></iframe>


10. Find the dotplot <span style="color:blue">***Blue***</span> (whether or not that was your predominant color when you took the survey). Refer to the picture to answer the following questions: 

     a. <strong style="color: red;"> What do you think the typical <span style="color:blue">***Blue***</span> score is (predicted balancing point)? </strong>

     b. <strong style="color: red;"> Are the data roughly symmetric? Where is the balancing point of this distribution? Once a value is chosen, describe the location of the point in the dotplot in your IDS Journal. </strong> 
    

11.  Compute the mean <span style="color:blue">***Blue***</span> score for the entire class and compare this value to the your own prediction of the balancing point. Blue scores: 8, 7, 12, 18, 12, 19, 12, 14, 16, 10, 8, 14, 14, 13, 15, 14, 8, 5, 8, 9, 10, 14, 12, 10, 11.

    You may not remember exactly how to compute the mean, so try to remember the general algorithm, or refer back to the responses from Step 5 above.

12. The formula for calculating the mean:
<center><img src="https://latex.codecogs.com/gif.latex?\bar{x}=\frac{&space;\sum_{x=1}^{n}&space;x_i}{n}" title="\bar{x}=\frac{ \sum_{x=1}^{n} x_i}{n}" /></center>

13. Now that you have calculated the mean for the <span style="color:blue">***Blue***</span> score, copy the formula in your IDS Journal. Label each symbol in the formula with a step in your algorithm for finding the mean, and write the meaning of the symbols in the formula in your IDS Journal.

    For example, ***x<sub>i</sub>*** represents each individual data point and ***n*** represents the total number of observations.

14. Sketch the dotplot <span style="color:blue">***Blue***</span> in your IDS Journal. Indicate the location of the calculated mean on your sketch by drawing a vertical line at the value on the x-axis. Notice how close the mean value is to your predicted balancing point.

15. Your teacher may ask you to compute the mean score for your actual class's blue scores or another one of the personality colors.

16. During the [next lesson](lesson3.md), you will learn about another method that can be
used for measuring the center of a distribution.

17. There is an even easier method of calculating the mean – using RStudio! The command RStudio uses to calculate the mean incorporates the algorithm of summing up all the data and dividing by the total number of observations. You will be able to use this command for quick calculations now.
    

    If you have already "*Exported, Downloaded, Imported*" the class's *Personality Color* campaign data, you can simply use the exact command below to calculate the mean <span style="color:blue">***Blue***</span> score: 


    &nbsp;&nbsp;&nbsp;&nbsp;**> mean(~blue, data = colors)**

    In general, the function can be denoted as follows:

    &nbsp;&nbsp;&nbsp;&nbsp;**> mean(~variable, data = datafile)**

   
18. Write a short answer entry in your IDS Journal about how the mean value of a group of data could be used to easily describe complicated things. For example, instead of giving someone the entire class’s <span style="color:blue">***Blue***</span> scores, we could just tell him/her the mean score and he/she would have a general idea about the class.


###**Reflection**
<strong style="color: red;">What are the essential learnings you are taking away from this lesson?</strong> 


###<p style="background: black; color: white; text-align: center;">**Homework**</p>
Complete the *Mr. Jones's Mile Run Times* handout and answer the questions below in your IDS Journal. You can practice finding the mean of distributions by determining a balancing point for the data.  The mean values in #3 on the handout do NOT need to be exact.


1. <strong style="color:red">What kind of plots did Mr. Jones create for his classes? </strong>

2. <strong style="color:red">Where does each distribution balance? Find and label the balancing point of each distribution.</strong>

3. <strong style="color:red">Based on the balancing points you found, what would you say the mean mile run time is for
each class?</strong>

    i. Period 1: <u><span style="color:grey">***&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***</span></u>

    ii. Period 2: <u><span style="color:grey">***&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***</span></u>
    
    iii. Period 3: <u><span style="color:grey">***&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***</span></u>
    
    iv. Period 4: <u><span style="color:grey">***&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***</span></u>


    <strong style="color: black;">Click on the document name to download a fillable copy of the </strong>[*Mr. Jones's Mile Rule Times* handout (LMR_2.3)](https://ucla.box.com/s/iet07d2irc48b6gofvauydv0bjxri5r4)</strong>.


    <iframe src="https://app.box.com/embed/s/iet07d2irc48b6gofvauydv0bjxri5r4?sortColumn=date&view=list" width="500" height="400" frameborder="0" allowfullscreen webkitallowfullscreen msallowfullscreen></iframe>