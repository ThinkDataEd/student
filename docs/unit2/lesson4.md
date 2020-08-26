##***<u>Lesson 4: How Far is it from Typical?</u>***

###**Objective:**
You will understand that the mean of the absolute deviations (MAD) is a way to assess the degree of
variation in the data from the mean and adjusts for differences in the number of points in the data set (*n*).
The MAD measures the total distance between all the data values from the mean and divides it by the
number of observations in the data set.


###**Vocabulary:**
measures of variability (spread), deviation, mean of absolute deviations (MAD)

###**Essential Concepts:**

!!! note "Essential Concepts: "
    MAD measures the variability in a sample of data - the larger the value, the greater
    the variability. More precisely, the MAD is the typical distance of observations from the mean. There are
    other measures of spread as well, notably the standard deviation and the interquartile range (IQR).

###**Lesson:**
1. You learned about 2 different measures of center during the previous 2
lessons: the mean and the median. <strong style="color: red;">Copy the sentence frames in your DS Journal and fill the blanks with the appropriate word/words:</strong>

    100. <strong style="color: red;">Mean – is used with _____________ distributions.

    100. Median – is used with ___________ distributions or when there are __________.</strong>

2. In today's lesson, you will learn about **measures of variability** –
also known as measures of **spread**. These values show us how much the quantitative data varies
from the center of a distribution. Similar to measures of center, you will use two different measures
of spread: (1) the mean of absolute deviations (MAD), and (2) the interquartile range (IQR).
    
3. <strong style="color: red;"> In your DS Journal, write what you think the word **deviation** means and how it could relate to variability and give at least 3 common synonyms like: fluctuation, modification, etc.</strong>

4. Find an open floor space in your house and on the floor,<strong style="color: red;"> place a 4-5 foot long piece of masking tape (or painter’s tape). </strong> You will need the help of your family members to complete the activity. <strong style="color: red;">Read to the following scenario to them:</strong>

    Your family team has been invited to guest star at the circus! You have been asked to perform
    as part of the tightrope act – a routine that requires tremendous focus and balance to
    walk across a tightly pulled rope that is suspended high in the air. In order to practice
    your balancing skills, the circus has provided your team with a line of tape that will
    represent the tightrope.

5. Have the entire family consider the piece of tape (aka the rope) to be the “typical” path you all must
take to finish the circus act. Since nobody wants to fall from the suspended tightrope while
performing at the actual circus, you will all need to practice walking directly on the middle of the line
at all times. If anyone *deviates* from the line, he/she will no longer be walking the “typical” path, and will
likely fall.

6. You should select who will be the starting performer.

7. There should be at least 4 of you working together in this activity, one is the performer, two are measuring the distance of the deviation (one
on each side of the tape), and one is the recorder.

8. Place a ruler perpendicular to the “rope” and measure the distance, in centimeters, from the path
to the center of the back of their heel as one family member walks and attempts to balance across the
“rope.”

9. The performer will walk the tightrope by looking straight up to the sky – first looking to place a
foot on the line, then walk naturally while looking up to the sky, and repeating one step at a time
for 4 steps, measuring after each step. Any time the performer missteps, this is considered a
variation from the typical value. You will take turns so everyone gets a chance to
balance, walk, measure and to record your observations in the DS Journal.

<strong style="color: blue;">Insert video of the process here</strong>

10. Now that you have an idea about what it means to deviate from something you consider
“typical,” you can start looking at distributions to see how data points vary from your typical value.

11. In this activity, you were observing deviations from typical while calculating actual
differences between the rope and the performer’s steps. When data are quantified with numbers,
you can then calculate how far away each value is from the center.

12. One such calculation that is popular among data scientists is the mean of absolute deviations
(MAD). Consider the components of the MAD in math terms, and in your DS Journal, write what the MAD value might represent.

    <strong style="color: red;">***mean – average***

    ***absolute – __________________***

    ***deviation – _________________***</strong>

13. Using the 3 concepts in Step 10, the MAD measures the absolute distance of each data point from the mean, and then finds the average of all those distances.

14. Below is the formula for the MAD distribution:
<center><img src="https://latex.codecogs.com/gif.latex?MAD=\frac{ &space;\sum_{x=1}^{n}&space;|x_i-\bar{x}|}{n}" title="MAD=\frac{ \sum_{x=1}^{n} |x_i-\bar{x}|}{n}" /></center>

15. <strong style="color: red;">Copy the formula in your DS Journal and write what each symbol in the formula means and how we use it to perform the calculation by completing the table below:

    ***x<sub>i</sub> - represents each individual data point***
    
    ***x̄             - represents the mean value***
    
    ***n             - _________________________***
    
    ***Σ             -__________________________***</strong>

16. To practice using this formula with actual data, you will calculate and compare the MAD values for 2 distributions.

17. Download  the *How Far Apart?* handout  ([LMR_2.6](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.6_How Far Apart.pdf)), which contains 2 of the dot plots - plots (a)
and (c) from the *Where is the Middle?* handout ([LMR_2.5](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.5_Where is the Middle.pdf)) used in [Lesson 3](lesson3.md). As before, the dot
plots depict the number of candies eaten by a group of 17 high school students on different days
of the week. The means are also given.
<div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://curriculum.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.6_How Far Apart.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_2.6](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.6_How Far Apart.pdf)</div>

    <span style="color:grey">**The calculations for each plot are shown below for your reference reference.**</span>

    <u><span style="color:grey">***MAD for plot (a)***</span></u>

    <img src="https://latex.codecogs.com/gif.latex?\begin{align*}&space;MAD&space;&=&space;\frac{1|0-2|&plus;5|1-2|&plus;6|2-2|&plus;3|3-2|&plus;2|4-2|}{17}&space;\\&space;&=&space;\frac{1(2)&plus;5(1)&plus;6(0)&plus;3(1)&plus;2(2)}{17}\\&space;&=&space;\frac{2&plus;5&plus;0&plus;3&plus;4}{17}\\&space;&=&space;\frac{14}{17}\\&space;&\approx&space;0.8235&space;\end{align*}" title="\begin{align*} MAD &= \frac{1|0-2|+5|1-2|+6|2-2|+3|3-2|+2|4-2|}{17} \\ &= \frac{1(2)+5(1)+6(0)+3(1)+2(2)}{17}\\ &= \frac{2+5+0+3+4}{17}\\ &= \frac{14}{17}\\ &\approx 0.8235 \end{align*}" />

    <u><span style="color:grey">***MAD for plot (c)***</span></u>

    <img src="https://latex.codecogs.com/gif.latex?\begin{align*}&space;MAD&space;&=&space;\frac{3|0-2.53|&plus;0|1-2.53|&plus;4|2-2.53|&plus;5|3-2.53|&plus;5|4-2.53|}{17}&space;\\&space;&=&space;\frac{3(2.53)&plus;0(1.53)&plus;4(0.53)&plus;5(0.47)&plus;5(1.47)}{17}\\&space;&=&space;\frac{7.59&plus;0&plus;2.12&plus;2.35&plus;7.35}{17}\\&space;&=&space;\frac{19.41}{17}\\&space;&\approx&space;1.1418&space;\end{align*}" title="\begin{align*} MAD &= \frac{3|0-2.53|+0|1-2.53|+4|2-2.53|+5|3-2.53|+5|4-2.53|}{17} \\ &= \frac{3(2.53)+0(1.53)+4(0.53)+5(0.47)+5(1.47)}{17}\\ &= \frac{7.59+0+2.12+2.35+7.35}{17}\\ &= \frac{19.41}{17}\\ &\approx 1.1418 \end{align*}" />

18. <strong style="color: red;">Complete the handout and answer the following questions in your DS Journal: </strong>
    
    100. <strong style="color: red;">Which MAD value did you think would be larger based only on the look/shape of the
    distributions? Why? </strong>
    <span style="color:grey">***Since plot (c) is skewed to the left, it probably has a larger MAD
    because more points will be further away from the mean than in plot (a).***</span>
    
    101. <strong style="color: red;">Which MAD value was actually larger when you calculated it? </strong>
    
    102. <strong style="color: red;">Did your prediction match the actual calculated values, or were you surprised by the
    results? </strong>

19. To continue exploring with the class’s Personality Color survey data, let's revisit the same dot plot visuals that we used in Lesson 2.  
<strong style="color: blue;">Insert visuals here</strong>
<strong style="color: red;">Compute the MAD value for the <span style="color:blue">***Blue***</span> scores Does the MAD value seem reasonable based on the dot plot?</strong>


###<p style="background: black; color: white; text-align: center;">**Homework & Next Day**</p>
Calculate the MAD values for each of the other 3 personality color scores and
compare the values of the 4 color scores.

[<u>***LAB 2A: All About Distributions***</u>](lab2a.md)

Complete [Lab 2A](lab2a.md) prior to [Lesson 5](lesson5.md).