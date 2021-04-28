##***<u>Lesson 10: Marbles, Marbles…</u>***

###**Objective**
You will understand that random events vary. Therefore, the percentage predicted by a probability isn't exact - it varies. You will also practice converting percentages to proportions.


###**Vocabulary**
percent (percentage), event, with replacement, without replacement

###**Essential Concepts**

!!! note "Lesson 10 Essential Concepts"
    There are two ways of sampling data that model real-life sampling situations: with
    and without replacement. Larger samples tend to be closer to the "true" probability.

###**Lesson**
1. In the previous two lessons you learned how to estimate probabilities for a population with the help of simulations to create sample data. Both lessons had nice, prepackaged functions already available in RStudio, which made the simulations fairly quick and easy. In [Lesson 8](lesson8.md) the **rflip()** function was used to simulate flipping a coin; and in [Lesson 9](lesson9.md) the **roll_die()** function was used to simulate rolling one of two dice.

2. What if we don’t have a nice function to perform a simulation for us? Can you create your own method? Yes! You will learn to create a simulation from scratch in the next RStudio task, [Lab 2C](lab2c.md).

3. In your IDS Journal, respond to the following question:

    <strong style="color:red;"> If you have a bag of 50 marbles and 20 of them are blue and 30 of them are red, what is the probability of drawing a red marble? What is the probability of drawing a blue marble?</strong>

4. How do you convert a fraction into a **percent**? As you may recall from [Unit 1](../unit1/overview.md), [Lesson 16](../unit1/lesson16.md) (*Categorical Associations*), a fraction is also called a proportion. Convert the proportions (fraction) you calculated in step 3 to a percent. 


5. Respond to the following question in your IDS Journal:

    <strong style="color:red;">If we actually drew out one marble, recorded its color, then replaced it back in the
    bag and did this 10 times, would the percentage of red marbles in this sample be exactly the same as the probability that you calculated in step 3? Explain why or why not. </strong>  
    
    
    Each time a marble is drawn, you are creating an **event**. An event is an outcome or result of an experiment.


6. You will now use an online simulator to practice drawing marbles from a bag. Go to: [http://www.shodor.org/interactivate/activities/Marbles/](http://www.shodor.org/interactivate/activities/Marbles/ "http://www.shodor.org/interactivate/activities/Marbles/"). As you go through the steps below, record your work in the *Marbles Marbles* handout.



    100. In the " Marble Info" portion of the screen, input 30 red marbles and 20 blue (set green and purple marbles to 0). Be sure the settings are set to: *draw 1 marble at a time*, *1 trial*, and *replace marbles*. Set *Order* button to *Order does not Matter*.

    100. Press the *Run Trials* button to simulate drawing a marble from the bag. A trial is an action that is done to create an event (also referred to as an experiment). 

    100. Record the marble’s color in your *Marbles Marbles* handout.

    100. When you selected Replace Marbles in the Marble Info, you are telling the simulator to put the marble back after the trial. This is called sampling **with replacement**. "With replacement" means that after you get the result from your trial, the simulator puts the marble back before running another trial.


    <strong style="color: black;">Click on the document name to download a fillable copy of the [*Marbles, Marbles* handout](https://ucla.box.com/s/p0etkmrat7r7x3h3yfa0mnsfd3jmig25)</strong>.


    <iframe src="https://app.box.com/embed/s/p0etkmrat7r7x3h3yfa0mnsfd3jmig25?sortColumn=date&view=list" width="500" height="400" frameborder="0" allowfullscreen webkitallowfullscreen msallowfullscreen></iframe>


7. Change the number of trials to *10 trials*. Press the *Run Trials* button.  This means that a marble was drawn and replaced 10 times. Record the number of red and blue marbles drawn.</strong> Press the *Clear Trials* button. Repeat this process 10 times. Record the results the *Marbles Marbles* handout. Be sure to *Clear Trials* after you run each trial. 

    100. Calculate and record the corresponding sample proportions for the proportion of red and blue marbles drawn. 
    
        <span style="color:grey"> For example, if you drew 7 red marbles out of their 10 draws, your sample proportion is 7/10 = 0.70 (which is the same as 70%).</span>
    
    101. Are all of your proportions the same? Are the proportions different from the “true” probability of drawing each color marble that you calculated in step 3?     

8. Change the number of trials to *50 trials*. Press the *Run Trials* button. This means that a marble was drawn and replaced 50 times. Record the number of red and blue marbles drawn. Repeat this process 10 times. Press the *Clear Trials* button. Record the results. Be sure to *Clear Trials* after you run each trial.

    100. <strong style="color: red;">Calculate and record the corresponding sample proportions for the proportion of red and blue marbles drawn.</strong> 
    
    101. <strong style="color: red;">Are all of your proportions the same? Are the proportions different from the “true” probability of drawing each color marble that you calculated in step 3?</strong>

9. Compare the proportions of drawing a red marble for each of your 10 trials versus each of your 50 trials. What do you notice?

10. In the comparison on step 9, you should see that sample size affects the sample proportion. In your own words, explain what happens to the sample probability as the sample size changes? Write this in your IDS Journal.

    <span style="color:grey"> You should see that as you draw more marbles, your sample probability gets closer and closer to the true probability. If we were to continue drawing marbles forever, in the long run our sample proportion should equal the


11. Think back to your bag of 50 marbles with 20 blue and 30 red marbles. Suppose you will be drawing marbles again, but this time you will not replace the marble back into the bag. On your first trial, you draw a red marble. What happens to the number of marbles in the bag after the first trial? 

12.  In your IDS Journal, write down what you think it might mean to sample without replacement. In the scenario in step 11, you did not put the red marble back in the bag. This is sampling **without replacement**.  “Without replacement” means that after you select a marble from the bag, you never put it back into the bag (you do not replace it). Instead, you simply select another marble from the bag immediately. You should recognize that, by not replacing the marble each time, the probabilities will change. This means each draw from the marble bag is NOT independent from another draw because removing one marble impacts the next event.

11. A 5th grader wants to know what the following words mean: sample, event, sample with replacement, and sample without replacement. In your IDS Journal, write the meaning of each so that a 5th grade student can understand them. 

###**Reflection**
<strong style="color:red;">What are the essential learnings you are taking away from this lesson? </strong>


###<p style="background: black; color: white; text-align: center;">**Homework**</p>
[<u>***LAB 2C: Which Song Plays Next?***</u>](lab2c.md)

Complete [Lab 2C](lab2c.md) prior to [Lesson 11](lesson11.md).