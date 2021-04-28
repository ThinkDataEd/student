##***<u>Lesson 18: What’s Your Z-Score?</u>***

###**Objective**
You will understand that a z-score can be used to measure how far away - or how many standard
deviations - an observation is away from the mean. Z-scores will usually range between -3 and +3. For
simulations involving shuffling, if you compute a z-score that lies far away from the mean, then you might
conclude that the outcome was not due to chance. If you see a z-score that lies close to the mean, then
you might conclude it was by chance.


###**Vocabulary**
Empirical Rule, z-score, standardized score

###**Essential Concepts**

!!! note "Lesson 18 Essential Concepts"
    Z-scores offer us a way to measure how extreme a value is, regardless of the units of measurement. Z-scores usually range between -3 and +3, so values that are at or are more extreme than -3 or +3 standard deviations are considered extremely rare.

###**Lesson**
1. Answer the following question in your IDS Journal: 


    <strong style="color: red;">What do you remember about normal distributions? What are some real-life examples of variables that produce normal distributions?</strong>

2. Another characteristic of normal distributions is given in the statement, “All normal distributions are bell-shaped, but not all bell-shaped distributions are normal.” Normal distributions have special properties.

3. Some of those special properties are stated by the **Empirical Rule**:

    • Approximately 68% of the observations in a normal distribution fall within one standard
    deviation of the mean

    • Approximately 95% of the observations in a normal distribution fall within 2 standard
    deviations of the mean

    • Approximately 99.7% of the observations in a normal distribution fall within 3 standard
    deviations of the mean


    <strong style="color: blue;"> Insert image to illustrate the Empirical Rule. </strong>

4. Open RStudio and load the cdc data. Use the codes provided to do the following:  

    100. Create a new variable and call it <strong style="color: purple;">height_in</strong>: 
        
    
        **> cdc <- mutate(cdc, height_in = height * 39.3701)**


    100. Subset the data for the males:
        

        **> males <- filter(cdc, gender == “Male”)**


    100. Create a histogram for the new variable, <strong style="color: purple;">height_in</strong>:
        

        **> histogram(~height_in, data = males, nint = 30)**

5. Answer the following questions in your IDS Journal:

    100. <strong style="color: red;">Does the distribution of teenage male heights look approximately normal? Explain.</strong>
    
        
    100. <strong style="color: red;">What do you approximate the mean height of the distribution to be? Standard deviation?</strong>
    

6. Use RStudio to calculate:


    100. The mean:


        **> mean(~height_in, data = males)**


    100. The standard deviation:
    

        **> sd(~height_in, data = males)**


    Compare your approximations from 5b to the actual values.

7. In your IDS Journal, draw a number line with seven equally spaced intervals and label it *Teen male
height in inches*. Make sure you leave about 5 centimeters of space above the number line to draw a normal curve. Label the middle tick mark with the mean male height (round to the nearest tenth of an inch=69 inches). See the example below:


    <strong style="color: blue;"> Insert number line example. </strong> 


    Then answer the following questions in your IDS Journal:


    100. <strong style="color: red;">What height is one standard deviation above the mean? To obtain your answer, add the standard deviation value to the mean value.</strong>

    100. <strong style="color: red;">What height is one standard deviation below the mean? To obtain your answer, subtract the standard deviation value to the mean value.</strong> 

    
    Label your number line with these values.

8. Continue filling your number line with the corresponding heights that are 2 and 3 standard deviations from the mean. 

9. According to the Empirical Rule, if the distribution of male heights is approximately normal, about 68% of males should be between 65.6 inches and 72.4 inches tall.

10. Use RStudio to confirm whether or not the distribution of male heights is approximately normal. The following code will subset the males whose height is between 65.6 inches and 72.4 inches tall:

    **> one_sd_males <- filter(males, height_in > 65.6, height_in < 72.4)**

    There are ________ males in this sample of 7749 males whose heights are one standard deviation from the mean, so ________/7749 = ______. This means that around _____% of males’ heights in this sample fall within one standard deviation from the mean male height. This is close to 68%, so it seems that the distribution of male heights is approximately normally distributed.

11. Now that you have verified that a normal distribution is an appropriate model for this distribution,
draw a normal curve above the number line from step 7. Below is a suggested method for obtaining a decent
normal curve:

    • Step 1: Draw a dot 4 centimeters above the mean height

    • Step 2: Draw dots 2.4 cm above the heights that are 1 standard deviation from the mean
    
    • Step 3: Draw dots 0.36 cm above the heights that are 2 standard deviations from the
    mean

    • Step 4: Draw dots right above the number line for the heights that are 3 standard
    deviations from the mean

    • Step 5: Connect the dots with a smooth curve

12. You're using this normal curve as a model to represent the distribution of all teenage male heights. This will allow you to make comparisons, draw conclusions, and make predictions about male heights. Answer the following questions in your IDS Journal:

    100. <strong style="color: red;">What proportion of teenage males are shorter than 69 inches? Explain.</strong>
    
    100. <strong style="color: red;">What proportion of teenage males are between 69 and 72.4 inches tall?</strong> 
    
    100. <strong style="color: red;">What proportion of males are taller than 72.4 inches?</strong> 

13. You will now investigate the distribution of teenage female heights. Use RStudio to run
each of the following functions. Once you've run the second function, check if the distribution of teen female heights looks approximately normal. The approach you'll take to verify whether it is or not is to overlay the histogram with a normal curve. That can be done by running the third function.

    **> females <- filter(cdc, gender == “Female”)**

    **> histogram(~height_in, data = females)**

    **> histogram(~height_in, data = females, fit = “normal”)**
    
    **> mean(~height_in, data = females)**

    **> sd(~height_in, data = females)**

14. Repeat steps 7, 8, and 11 with the distribution of teenage female heights.

15. Statisticians use something called a **z-score** to compare values. A z-score tells us how many standard deviations above or below the mean an observation is. Another name for z-score is a **standardized score**.

16. Observe the formula below for calculating a z-score, where *z* represents the z-score, *x* represents the value of an observation, *bar{x}* represents the mean of the observations, and *s* represents the standard deviation.

    <center><img src="https://latex.codecogs.com/gif.latex?z=\frac{x-\bar{x}}{s}" title="z=\frac{x-\bar{x}}{s}" /></center>
    

    The following examples demonstrate how to find the z-score for a female height and a male height:


    <strong style="color: blue;"> Insert examples how to find the z-score for a female height and a male height. </strong>

17. Z-scores answer the question, "How typical is x?" If x is the same as the typical value (the mean), then z = 0. If x is one standard deviation away from the mean, then z = -1 if it is below, or +1 if it is above. Recall from the normal curve that as you move farther from the center (or the mean), there are fewer observations. Therefore, a large z-score is considered an unusual value.

18. Calculate your z-score and record it in your IDS Journal. Then answer the following:

    100. <strong style="color: red;"> What does a negative z-score mean? A negative z-score means the x value is _______ the mean. This means that the height is ________ average.</strong>

    100. <strong style="color: red;">What does a positive z-score mean? </strong> 

    100. <strong style="color: red;"> What is the most negative z-score you think we will find? What is the most positive z-score?</strong>
    

19. Where do you fall within the distribution of height for your gender? Find your height (in inches) on the x-axis of the normal curve corresponding to your gender, then draw a vertical line from the x-axis until it intersects the normal curve. Shade the area under the curve to the left of the vertical line.

20. The shaded area represents your percentile in the distribution. A percentile is the exact value in which the desired proportion of observations lie below the specific value in a distribution. For example, with regard to people’s heights, the 70<sup>th</sup> percentile would be the height that is taller than exactly 70% of the observations. 

    Now use RStudio to find the percentile for the height for a teen male who is 70 inches tall.

    **> pnorm(70, mean = 69, sd = 3.4) = 0.615666**

    Use the following sentence frame to interpret the percentile:


    *This male student is at the ________ percentile in the distribution of teen male heights. That means that he is taller than _________ of all teen males, but shorter than ________ of all teen males.*
    
21. Calculate and interpret your percentile in the distribution of height for your gender. You will be using RStudio during the next few days to practice using normal models. 


###**Reflection**
<strong style="color: red;">What are the essential learnings you are taking away from this lesson?</strong> 


###<p style="background: black; color: white; text-align: center;">**Next 2 Days**</p>
[<u>***LAB 2H: Eyeballing Normal***</u>](lab2h.md)

[<u>***LAB 2I: R’s Normal Distribution Alphabet***</u>](lab2i.md)

Complete [Labs 2H](lab2h.md) and [2I](lab2i.md) prior to the [End of Unit Project](end.md).