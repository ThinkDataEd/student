##***<u>Lesson 10: Marbles, Marbles…</u>***

###**Objective:**
You will understand that random events vary, so that the percentage predicted by a probability isn't
exact, but varies. You will practice converting percentages to proportions.


###**Vocabulary:**
proportion, percentage, event, with replacement, without replacement

###**Essential Concepts:**

!!! note "Essential Concepts: "
    There are two ways of sampling data that model real-life sampling situations: with
    and without replacement. Larger samples tend to be closer to the "true" probability.

###**Lesson:**
1. Remember in the previous two lessons, you learned how to estimate probabilities
for a population with the help of simulations to create sample data. Both lessons had nice, prepackaged
functions already available in RStudio, which made the simulations fairly quick and
easy – in [Lesson 8](lesson8.md), the **rflip()** function was used to simulate flipping a coin; and in [Lesson 9](lesson9.md),
the **roll_die()** function was used to simulate rolling one of two dice.

2. But what if we don’t have a nice function to perform a simulation for us? Can you create your own
method? Yes! You will actually learn to create a simulation from scratch during [Lab 2C](lab2c.md).

3. In your DS Journal respond to the following question:

    100. <strong style="color:red;"> If you have a bag of 50 marbles, where 20 of them are blue and 30 of them are red, what
    is the probability of drawing a red marble? </strong>


5. <strong style="color:red;"> How do you convert the **proportion** you calculated in question 3 to a  **percentage**. How do you turn a fraction into a percentage? </strong>

6. Respond to the following in you DS journal:

    100.   What if we actually drew out one marble, recorded its color, then replaced it back in the
    bag, and did this 10 times?  <strong style="color:red;"> Would the percentage of red marbles in this sample necessarily be exactly the same as
    the probability? Explain why or why not. </strong>  <span style="color:grey">  (Each time a marble is drawn, you are creating an **event**) <span/>

7. You will now simulate drawing marbles from a bag by doing an interactive activity. Go to: http://www.shodor.org/interactivate/activities/Marbles/.  
Use the following handout <strong style="color: blue;"> Marbles handout </strong>  to record your work as you complete the following steps:

    100. In the " Marble Info" portion of the screen, input 30 red marbles and 20 blue (set green and purple marbles to 0). Be sure the settings are set to : draw 1 marble at a time,  1 trial,  and replace marbles. 

    100. Press the "Run Trials" button to simulate drawing a marble from the bag.

    100. <strong style="color:red;"> Record the marble’s color in your DS journal. </strong>

    100. Replace the marble back into the bag- this is called sampling **with
    replacement**.  <span style="color:grey">***“With replacement” means that after you select a marble from the bag, you
    have to put it back into the bag (replace it) before you select another marble.***</span>


8. **Change the number of trials to 10 trials**. Press the " Run Trials" button.  <strong style="color:red;">Record the number of red and blue marbles drawn.</strong> Repeat this process 10 times. Record the results.( Be sure to " Clear Trials" after you run each trial) 

    100. <strong style="color:red;">Calculate and record the corresponding sample proportions for the proportion of red and blue         marbles drawn. </strong> <span style="color:grey"> For example, if you drew 7 red marbles out of their 10 draws, your sample proportion is 7/10 = 0.70 (which is the same as a sample percentage of 70%).</span>
    
    101. <strong style="color:red;"> Are all of your proportions the same? Are the proportions  different from the “true”
probability of drawing each color marble? </strong>     

10. **Change the number of trials to 50 trials**. Press the " Run Trials" button.  <strong style="color:red;">Record the number of red and blue marbles drawn.</strong> Repeat this process 10 times. Record the results.( Be sure to " Clear Trials" after you run each trial) 
    100. <strong style="color:red;">Calculate and record the corresponding sample proportions for the proportion of red and blue         marbles drawn. </strong> 
    
    101. <strong style="color:red;"> Are all of your proportions the same? Are the proportions  different from the “true”
probability of drawing each color marble? </strong>  

11. How does the sample size affect the sample proportion? <span style="color:grey"> You
should see that as you draw more marbles, your sample probability gets closer and closer to the
true probability. If we were to continue drawing marbles forever, in the long run, our sample
proportion should equal our true probability.</span>

12. Consider what it might mean to sample **without replacement**. Will you get the same or different results if you do not replace the marble back into the bag? Explain your answer.  

<span style="color:grey">***“Without replacement” means that after you select a marble
from the bag, you never put it back into the bag (do not replace it). Instead, you simply
select another marble from the bag immediately. You should recognize that, by not
replacing the marble each time, the probabilities will change. This means each draw from
the marble bag is NOT independent from another draw because removing one marble
impacts the next event.***</span>

13. In your DS journal, <strong style="color:red;">describe a sample, an event, with replacement and without replacement.</strong>


###<p style="background: black; color: white; text-align: center;">**Next Day**</p>
[<u>***LAB 2C: Which Song Plays Next?***</u>](lab2c.md)

Complete [Lab 2C](lab2c.md) prior to [Lesson 11](lesson11.md).