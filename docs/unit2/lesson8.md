##***<u>Lesson 8: How Likely Is It?</u>***

###**Objective:**
You will understand the basic rules of probability. You will learn that previous outcomes do not give
information about future outcomes if the events are independent.



###**Vocabulary:**
probability, simulation, model, sample proportion, chance, independence

###**Essential Concepts:**

!!! note "Essential Concepts: "
    Probability is an area that we humans have poor intuition about. Probability
    measures a long-run proportion: 50% chance means the event happens 50% of the time *if you repeated it
    forever*. When we don't repeat forever, we see variability.

###**Lesson:**

1.Consider possible synonyms to the word **chance**. If someone says, “That just
happened by chance,” <strong style="color:red;"> In your IDS journal, write down what "That happened by chance""  means </strong>  

2. Which game – chess or the board game “Sorry” – is more based on chance? <strong style="color:red;">Explain why </strong>


3.  Think of situations where chance is the only force at play. <strong style="color:red;">Write down a few situations where chance is the only force at play. </strong>
4. Play the “Heads” video from the movie *Rosencrantz and Guildenstern are Dead* found at:
[https://www.youtube.com/watch?v=NbInZ5oJ0bc](https://www.youtube.com/watch?v=NbInZ5oJ0bc "https://www.youtube.com/watch?v=NbInZ5oJ0bc").

5. In your IDS journals, <strong style="color:red;"> write down your initial reactions to the clip by responding to the following questions:</strong>

    100. Is it *possible* to get 78 heads in a row when tossing a coin? <strong style="color:red;"> Yes or no and explain </strong>

    101. Do you think it is *likely* to get 78 heads in a row? <strong style="color:red;">Yes or no and explain </strong>

    100. <strong style="color:red;">Write down how many times should we get a heads when tossing a coin? </strong>

    100. On average, <strong style="color:red;">  write down how many times should the characters have gotten a heads out of the 78
    tosses? </strong> 

 6. Your teacher will give you an opportunity to share and discuss your results.  Be prepared to discuss any differences and similarities you see. 

7. After discussing and comparing results, in your IDS Journal, <strong style="color:red;">write down any additions  or revisions to your  initial findings. </strong>

8. The concept of chance, we can start learning about  is called **probability**.
Chance is simply the possibility that something will happen, and probability is a measurement for
how often something happens in the “long run.” You may  already have ideas about how to calculate
probabilities based on prior classes or knowledge, but in IDS we will be taking a
different approach – using simulations (see next step).

9. Since we don’t want to actually flip a coin 78 times like the actors did in the video, we can have
RStudio simulate them for us. A **simulation** is a way of creating random events that are close to
real-life situations without actually doing them. It is a kind of **model**, which is a way of
representing real world situations so that predictions can be made.

10.  R has a function that does coin flipping for us, and that it assumes an
equal probability of heads and tails.  In RStudio you will simulate a coin flip. Use the following
function:

    **> rflip(1)**

11.  The value of 1 in the argument part of the function tells R to flip the coin 1 time. If you
want to flip the coin 10 times, you could simply change the function to **rflip(10)**.

12. Run the function again using 10 as the number of times to flip the coin. 

    100. <strong style="color:red;"> Record the number of Heads (“H”s) you got </strong>

    100. <strong style="color:red;"> Record  the number of  Tails (“T”s) you got </strong>

    100. In the output, <strong style="color:red;"> explain what does **Flipping 10 coins [Prob(Heads) = 0.5]** mean? </strong>
    100. In the output, <strong style="color:red;">explain what does **Number of Heads: 3 [Proportion Heads: 0.3]** mean?</strong>
    
        **<u>Note:</u>** This is example output. Your sample may have a different value for the number of
        heads that appeared, and thus a different value for the proportion of heads. 
        
13. To relate back to the video at the beginning of the lesson, repeat the simulation once more, but use 78
as the number of coin flips **rflip(78)**. Record answers to the following
questions in the IDS journals:

    100.  <strong style="color:red;">How many heads (“H”s) were there?  Since we know to expect about 39 heads if the coin
    is fair, does the value seem reasonable?</strong>

    100.  <strong style="color:red;">How many Tails (“T”s) were there? </strong>
    100. <strong style="color:red;">What proportion of the coin flips were heads?</strong>
    
14. Using the **rflip(78)** command, run the simulation a few more times (3 – 5), 
record the values for the number of heads and the proportion of heads.

    <span style="color:grey">***As an example, we ran the function one times, look at the  following value:***</span>

    <span style="color:grey">***Sample 1 – amount of heads: 45***</span>

    <span style="color:grey">***&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;proportion of heads: 0.577***</span>

    
15. Answer the questions listed below. The important thing to note is that the values
can and (almost always) WILL change each time you run the simulation to create a new sample.

    100. <strong style="color:red;">How do the proportions of heads in the samples compare to each other? </strong>

    100. <strong style="color:red;">How do the proportions of heads compare to the true probability of heads (1/2 or 50%)?</strong>
   
    100. <strong style="color:red;">Why is there a 50% chance of getting heads during each coin flip? </strong>

16. Next, answer following question in your IDS Journal:

    100. <strong style="color:red;">If you get a heads on the first toss of a coin, will you definitely get a heads on the next
    toss? Will you definitely get a tails on the next toss? </strong>
    
17. When tossing a fair coin, there is no relationship between each toss. The second toss does NOT depend on the first toss; this concept is called **independence**. In this case,the coin tosses are independent of each other.


In your journal, <strong style="color:red;">write what you think the 3 most important topics were. </strong>

###<p style="background: black; color: white; text-align: center;">**Homework**</p>
 <strong style="color:red;">Create a Tweet (you do not have to post it online). Using 280 characters or fewer, write a
Tweet about the meaning of probability.</strong>