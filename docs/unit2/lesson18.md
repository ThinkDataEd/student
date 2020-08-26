##***<u>Lesson 18: What’s Your Z-Score?</u>***

###**Objective:**
You will understand that a z-score can be used to measure how far away - or how many standard
deviations - an observation is away from the mean. Usually, z-scores will range between -3 and +3. For
simulations involving shuffling, if we compute a z-score that lies far away from the mean, then we might
conclude that the outcome was not due to chance. If we see a z-score that lies close to the mean, then
we might conclude it was by chance.


###**Vocabulary:**
z-score, standardized score, Empirical Rule

###**Essential Concepts:**

!!! note "Essential Concepts: "
    z-scores offer us a way to measure how extreme a value is, regardless of the units
    of measurement. Usually, z-scores will range between -3 and +3, so values that are at or are more
    extreme than -3 or +3 standard deviations are considered extremely rare.

###**Lesson:**
1. Answer the following question in your DS journal: <strong style="color: red;">What do you remember about normal distributions? What are some real-life examples of variables that produce normal distributions?</strong>

2. Another characteristic of normal distributions is given in the following statement: “All normal distributions are bell-shaped, but not all bell-shaped distributions are normal.” Normal distributions have special properties.

3. Some of those special properties are stated by The **Empirical Rule**:

    • Approximately 68% of the observations in a normal distribution fall within one standard
    deviation of the mean

    • Approximately 95% of the observations in a normal distribution fall within 2 standard
    deviations of the mean

    • Approximately 99.7% of the observations in a normal distribution fall within 3 standard
    deviations of the mean
<strong style="color: blue;"> Insert image to illustrate the empirical rule </strong>
4. Open RStudio and load the cdc data. Use the codes provided to do the following:  

create a new variable and call it height_in, 
    **> cdc <- mutate(cdc, height_in = height * 39.3701)**

subset the data for the males,
    **> males <- filter(cdc, gender == “Male”)**

create a histogram for the new variable, height_in.
    **> histogram(~height_in, data = males, nint = 30)**

5. Answer the following questions in your DS Journal:

    100. <strong style="color: red;">Does the distribution of teenage male heights look approximately normal? Explain.</strong>
    
        
    100. <strong style="color: red;">What do you approximate the mean height of the distribution to be? standard deviation?</strong>
    

6. Use RStudio to calculate the mean

    **> mean(~height_in, data = males)**

Use RStudio to calculate the standard deviation
    **> sd(~height_in, data = males)**

Compare your approximations from 5b to the actual values.

7. In your DS journal, draw a number line with seven equally spaced intervals and label it “Teen male
height in inches.” Make sure you leave about 5 centimeters of space above the number line
to draw a normal curve. Label the middle tick mark with the mean male height
(Round to the nearest tenth of an inch=69 inches). See the example below. <strong style="color: blue;"> Insert number line example </strong> Then answer the following:

    100. What height is one standard deviation above the mean? To obtain your answer, add the standard deviation value to the mean value.
    100. What height is one standard deviation below the mean? To obtain your answer, subtract the standard deviation value to the mean value. 

    Label your number line with these values.

8. Continue filling your number line with the corresponding heights that are 2 and 3
standard deviations from the mean. 

9. According to the Empirical Rule, if the distribution of male heights is approximately normal, about 68% of males should be between 65.6 inches and 72.4 inches tall.

10. Use RStudio to confirm if indeed the distribution of male heights is approximately normal. The following code will subset the males whose height is between 65.6 inches and 72.4 inches tall.

    **> one_sd_males <- filter(males, height_in > 65.6, height_in < 72.4)**

    There are ________ males in this sample of 7749 males whose height are one
    standard deviation from the mean, so ________/7749 = ______. This means that around _____% of
    males’ heights in this sample fall within one standard deviation from the mean male height.
    This is close to 68%, so it seems that the distribution of male heights is approximately
    normally distributed.


11. Now that you have verified that a normal distribution is an appropriate model for this distribution,
draw a normal curve above the number line from step 7. Below is a suggested method to obtain a decent
normal curve:

    • Step 1: Draw a dot 4 centimeters above the mean height

    • Step 2: Draw dots 2.4 cm above the heights that are 1 standard deviation from the mean
    
    • Step 3: Draw dots 0.36 cm above the heights that are 2 standard deviation from the
    mean

    • Step 4: Draw dots right above the number line for the heights that are 3 standard
    deviation from the mean

    • Step 5: Connect the dots with a smooth curve

12. We are using this normal curve as a model to represent the distribution of all
teenage male heights. This will allow us to make comparisons, draw conclusions, and make
predictions about male heights. Let’s see:

    100. What proportion of teenage males are shorter than 69 inches? Explain.
    
    100. What proportion of teenage males are between 69 and 72.4 inches tall? 
    
    100. What proportion of males are taller than 72.4 inches? 

13. You will now investigate the distribution of teenage female heights. Use Rstudio to run
each of the following functions one by one. Once you run the second function, check if the distribution of teen female heights looks approximately normal. The approach we are going to take to verify whether it is or not is to overlay the histogram with a normal curve. That can be done by running the third function.

    **> females <- filter(cdc, gender == “Female”)**

    **> histogram(~height_in, data = females)**

    **> histogram(~height_in, data = females, fit = “normal”)**
    
    **> mean(~height_in, data = females)**

    **&nbsp;**

    **> sd(~height_in, data = females)**

14. Repeat steps 7, 8 and 11 with the distribution of teenage female heights.

15. Statisticians use something called a **z-score** to compare values. A z-score tells us
how many standard deviations above or below from the mean an observation is. Another name for z-score
is a **standardized score**.

16. Observe the formula for calculating a z-score below. 

    <center><img src="https://latex.codecogs.com/gif.latex?z=\frac{x-\bar{x}}{s}" title="z=\frac{x-\bar{x}}{s}" /></center>
where z represents the z-score, x represents the value of an observation, bar{x} represents the mean of the observations and s represents the standard deviation.
The following examples demonstrate how to find the z-score for a female height and a male height.
<strong style="color: blue;"> Insert examples </strong>

17. Z-scores answer the question: how typical is x? If x is the same as the typical value
(the mean), then z = 0. If x is one standard deviation away from the mean, then z = -1 if it is below or +1 if it is above.
Recall from the normal curve that as you move farther from the center (from the mean),
there are fewer observations. Therefore, a large z-score is considered an unusual value.

18. Calculate your z-score and record it in your DS journal. 
Then answer the following:

    100. <strong style="color: red;"> What does a negative z-score mean? </strong>A negative z-score means the x value is _______ the mean. This means that the height is ________ average.

    100.<strong style="color: red;">What does a positive z-score mean? </strong> 

    100.<strong style="color: red;"> What is the most negative z-score you think we will find? What is the most positive zscore?</strong>
    

19. Where do you fall within the distribution of height for your gender? Find your height (in inches) on the x-axis of the normal curve corresponding to your gender, and draw a vertical line from the x-axis until it intersects the normal curve. Shade the area
under the curve to the left of the vertical line.

20. The shaded area represents your percentile in the distribution. A percentile is
the exact value in which the desired proportion of observations lie below the specific value in a
distribution. For example, with regard to people’s heights, the 70<sup>th</sup> percentile would be the height
that is taller than exactly 70% of the observations. 

Let's use RStudio to find the percentile for the height for a teen male who is 70 inches tall.

    **> pnorm(70, mean = 69, sd = 3.4)** = 0.615666**

    Use the following sentence frame to interpret the percentile.
    This male student is at the ________ percentile in the distribution of teen male heights. That means that he is
    taller than _________ of all teen males, but shorter than ________ of all teen males.
    
21. Calculate and interpret your percentile in the distribution of height for your gender.

You will be using RStudio during the next few days to practice using normal
models. 


###<p style="background: black; color: white; text-align: center;">**Next 2 Days**</p>
[<u>***LAB 2H: Eyeballing Normal***</u>](lab2h.md)

[<u>***LAB 2I: R’s Normal Distribution Alphabet***</u>](lab2i.md)

Complete [Labs 2H](lab2h.md) and [2I](lab2i.md) prior to the [End of Unit Design Project](end.md).