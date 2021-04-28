##***<u>Lesson 8: How Likely Is It?</u>***

###**Objective**
You will understand the basic rules of probability. You will learn that previous outcomes do not give
information about future outcomes if the events are independent of each other.



###**Vocabulary**
chance, probability, simulation, model, sample proportion, fair, independence

###**Essential Concepts:**

!!! note "Lesson 8 Essential Concepts"
    Humans do not have a great sense of the concept of probability. Probability measures a long-run proportion: Fifty percent chance means the event happens fifty percent of the time *if you repeated it forever*. When we don't repeat forever, we see variability.

###**Lesson**

1. Consider possible synonyms for the word **chance**. If someone says, “That just happened by chance,” what does this mean? In your IDS Journal, write down what "That happened by chance"  means. 

2. Which game, dominoes or the board game “Monopoly” (if you don't know Monopoly, think Candy Land), is more based on chance? Explain why.


3.  Think of situations where chance is the only force at play (for example, drawing names out of a hat). Write down a few situations where you think this is the case.

4. Watch the “Heads” video from the movie *Rosencrantz and Guildenstern are Dead* found at:
[https://www.youtube.com/watch?v=NbInZ5oJ0bc](https://www.youtube.com/watch?v=NbInZ5oJ0bc "https://www.youtube.com/watch?v=NbInZ5oJ0bc").

5. In your IDS Journal, write down your initial reactions to the clip by responding to the following questions:

    100. <strong style="color:red;"> Is it *<u>possible</u>* to get 78 heads in a row when tossing a coin? Yes or no? Explain. </strong>

    101. <strong style="color:red;"> Do you think it is *<u>likely</u>* to get 78 heads in a row? Yes or no? Explain.</strong>

    100. <strong style="color:red;">If you were to flip a coin one time, what are the chances of getting a heads? What percent of the time would that be? </strong>

    100. <strong style="color:red;">Since the characters in the clip flipped the coin 78 times, how many times, on average, should they have gotten a heads?</strong> 

6. Ask questions a-d in #5 to 3-4 people (friends, family members, etc.). Record their answers in your IDS Journal.

7. Compare your answers with the ones of the people you asked in #6. Write down your noticings. What are the similarities and differences? For the differences, explain why you believe the responses were different.

8. Understanding chance helps us get a sense of the concept of **probability**. Chance is simply the possibility that something will happen, and probability is a measurement for how often something happens in the “long run.” The measurement is expressed as a proportion or percent. Recall that in [Unit 1](../unit1/overview.md), [Lesson 16](../unit1/lesson16.md) (*Categorical Associations*) that a proportion can be expressed as a percent. For example, a proportion of 0.42 is the same as 42%. You may  already have ideas about how to calculate probabilities based on prior classes or knowledge, but in IDS we will be taking a different approach: using simulations (see next step).

9. Since you don’t want to actually flip a coin 78 times like the actors did in the video, you can have
RStudio simulate them for you. A **simulation** is a way of creating random events that are close to
real-life situations without actually doing them. It is a kind of **model**, which is a way of representing real-world situations so that predictions can be made.

10.  R has a function that does coin flipping for us. This function assumes an equal probability of heads and tails. Login to RStudio to simulate a coin flip by running the following function:

    **> rflip(1)**

11.  The value of 1 in the argument part of the rflip function tells R to flip the coin 1 time. If you want to flip the coin 10 times, you could simply change the function to **rflip(10)**.

12. Run the rflip function again using 10 as the number of times to flip the coin. Then record your responses to the following in your IDS Journal:

    100. <strong style="color:red;"> Record the number of Heads (“H”s) you got. </strong>

    100. <strong style="color:red;"> Record  the number of  Tails (“T”s) you got. </strong>

    100. <strong style="color:red;"> In the output, explain what does **Flipping 10 coins [Prob(Heads) = 0.5]** mean? </strong>
    100. <strong style="color:red;"> When we ran our rflip (10) function, we got the following output: Number of Heads:3 [Proportion of Heads: 0.3]. What does this mean?</strong>

        **Note:** This is RStudio telling us that in our sample, we got heads 3 out of the 10 times we flipped the coin. The **sample proportion** is automatically calculated for us by dividing the number of heads by the total number of tosses (in this case, 3/10 = 0.3).

    100. <strong style="color:red;"> What was the output of your rflip (10) function? What was the proportion of heads in your output?</strong>
     
13. To relate back to the video at the beginning of the lesson, repeat the simulation once more, but use 78 as the number of coin flips **rflip(78)**. Record answers to the following questions in your IDS Journal:

    100.  <strong style="color:red;">How many heads (“H”s) were there?  Since we know to expect about 39 heads if the coin is fair, does the value seem reasonable?</strong>

    100.  <strong style="color:red;">How many Tails (“T”s) were there? </strong>

    100. <strong style="color:red;">What proportion of the coin flips were heads?</strong>
    
14. Using the **rflip(78)** command, run the simulation a few more times (3 – 5 times is fine). Then write down the values for both the number of heads and for the proportion of heads.

    <span style="color:grey">***For example, we ran the function three times and wrote down the following values for the first coin flip (sample 1):***</span>

    <span style="color:grey">***amount of heads - 45***
    
    <span style="color:grey">***proportion of heads - 0.577***</span>

    
15. The important thing to note is that the values can and almost always WILL change each time you run the simulation to create a new sample. Think about what would happen to the proportion of heads and tails if you increased the numbers of times flipped the coin. 

16. Go back to your three samples of rflip (78) and answer the following quesitons in your IDS Journal:

    100. <strong style="color:red;">How do the proportions of heads in the samples compare to each other? </strong>
    100. <strong style="color:red;">How do the proportions of heads compare to the true probability of heads (1/2, or 50%)?</strong>
    100. <strong style="color:red;">Why is there a 50% chance of getting heads during each coin flip? </strong>
    100. <strong style="color:red;">Explain why or why not.</strong>
    
17. A coin is considered **fair** when nothing has been done to it so that it favors one side over the other. Another word for fair is equitable, or equally. When tossing a fair coin, there is no relationship between each toss. The second toss does NOT depend on the first toss. The coin tosses are independent of each other. This concept is called **independence**.

###**Reflection**

<strong style="color:red;"> What are the essential learnings you are taking away from this lesson?</strong>


###<p style="background: black; color: white; text-align: center;">**Homework**</p>
Using 280 characters or fewer, write a Tweet about the meaning of probability (you do not have to post it online).