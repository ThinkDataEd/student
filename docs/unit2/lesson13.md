##***<u>Lesson 13: The Horror Movie Shuffle</u>***

###**Objective**
You will understand that, just by chance, you can see differences between two groups, and that these differences are usually small. You will learn that by calculating differences in the percentages between two groups, you can determine if outcomes are due to chance for categorical variables.


###**Vocabulary**
chance, simulations, randomness, shuffle

###**Essential Concepts**

!!! note "Lesson 13 Essential Concepts" 
    You can "shuffle" data based on categorical variables and by using the difference in percents. The distribution formed by shuffling represents what happens if chance were the only factor at play. If the actual observed difference in percents is near the center of this shuffling distribution, then you could conclude that chance is a good explanation for the difference; but if it is extreme (in the tails or off the charts), then you should conclude that chance is NOT to blame. Sometimes the apparent difference between groups is caused by chance.

###**Lesson**

1. <u>**Stress/Chill Campaign Data Collection Monitoring:**</u>
    
    Your teacher will be monitoring your class's data collection using the *Campaign Monitoring Tool*. Keep in mind that this tool will inform your teacher about whether or not you are collecting data.

2.  Through the *Campaign Monitoring Tool*, your teacher can track the following:

    100. Who has collected the most data so far.

    100. How many active and inactive users there are.

    100. How many responses were submitted on any given day.

    100. How many responses have been shared, and how many remain private.

3. Quickwrite: In your IDS Journal, write down how you can be more accurate in your data collecting for the *Stress/Chill* campaign.

4. Recall what you have learned about **chance** (see [Lesson 8](lesson8.md)). 


    <span style="color:grey">***Synonyms: possibility, prospect, expectation, unintentional, unplanned. The actual definition of chance is “a possibility of something happening.”***</span>

5. Think back to the path you saw in [Lesson 9](lesson9.md) item #2 (chance → probability → simulations). You can use **simulations** to show that sometimes when you think two groups are different, the difference is really just because of chance, or **randomness**, and does not mean anything.

6. Remember that a simulation is a model for creating random outcomes. Randomness means that something just happens without a specific order.

7. Below are some examples for comparing two different groups:

    100. Men earn more money than women for some work.

    100. Basketball players are faster runners than baseball players.

    100. UCLA football players are better athletes than USC football players.

    100. You and a friend flipped a coin 10 times, and you got more "heads."

    In your IDS Journal, list other situations where two groups could be compared. 

8. Sometimes differences between two groups are real, but sometimes they might just be due to chance.  In your IDS Journal, state whether you think the differences are either real or due to chance for each of the situations in #7, and for the situations you came up with where two groups can be compared.
   
9. In this lesson, you will learn ways to tell the difference. Consider the following statement which offers a sample comparison: *Men earn more money than women for some work.*


    <strong style="color: red;">Write down whether you think this statement is real, or if it is due to chance.</strong>


    One possible response: <span style="color:grey">***I think this is real, especially in jobs where there is physical labor involved. I would guess that male construction workers make more than female construction workers because their boss might feel that male construction workers exert themselves more physically.***


10. In your IDS Journal, write down your thoughts about the following question:

    <strong style="color: red;">Do you think men and women have an equal likelihood of surviving by the end of a horror movie?</strong>

11. Today you will be pretending to be the producer of a horror movie. As a producer, you obtained data from 50 horror movies (sometimes called "slasher" films). There are a total of 485 characters in these 50 films. Two variables were recorded for each character: <strong style="color: purple;">Gender</strong> and <strong style="color: purple;">Survival</strong>. The values for <strong style="color: purple;">Gender</strong> were “Male” and “Female.” The values for <strong style="color: purple;">Survival</strong> were “Dies” and “Survives.”
    
    |          | Gender |      |   |   |
    |----------|:------:|------|---|---|
    | Survival | Female | Male |   |   |
    | Dies     | 172    | 228  |   |   |
    | Survives | 50     | 35   |   |   |
    | Total    | 222    | 263  |   |   |
    

12. From this data, a few summary statistics were calculated. The percent of total survivors was calculated by dividing the total number of survivors by the total number of characters using the following code: 


    **>tally(~survival,data=slasher,format="percent")**


    Only 18% of all characters survived in these slasher films! The percent of survivors was calculated for each gender. In other words, for all female characters, the number of female survivors was divided by the total number of females. Similarly, for all male characters, the number of male survivors was divided by the total number of males.


    <center><img src="https://latex.codecogs.com/gif.latex?\frac{\&hash;(''&space;Female&space;''&space;\&''&space;Survives&space;'')}{\&hash;(''&space;Female&space;'')}\&space;\&space;\&space;or\&space;\&space;\&space;\frac{\&hash;(''&space;Male&space;''&space;\&''&space;Survives&space;'')}{\&hash;(''&space;Male&space;'')}" title="\frac{\#('' Female '' \&'' Survives '')}{\#('' Female '')}\ \ \ or\ \ \ \frac{\#('' Male '' \&'' Survives '')}{\#('' Male '')}" /></center>


13. By the end of a horror movie about **23%** of females survived, and about **13%** of males survived.

    100. <strong style="color: red;">Is this what you expected?</strong>
    
    
        <span style="color:grey">***If you thought males would survive more often, then these results would be unexpected. If you thought females would survive more often, then these results would be expected. If you thought there was an equal likelihood of survival, these results would also be surprising.***</span>
    
    100. <strong style="color: red;">What is the difference in the proportions of survival rates between genders? What does
    this mean in the context of surviving a horror movie?</strong> 
    
    
        <span style="color:grey">***The difference is 23% - 13% = 10%. This means that 10% more women characters survived than men.***</span>
    
    100. <strong style="color: red;">Is this difference “big” or “small”? Can you define what is a “big” difference and what is “small difference?”</strong> 
    
    
        <span style="color:grey">***Upon first glance, it may seem like 10% is a big difference, but we do not know for sure.***</span>


14. You will now participate in an activity to determine if the 10% difference seen in the actual data set is big or small. This will help you determine if there really is a difference in horror movie survival rates for males versus females, or if the 10% difference was just due to chance.


15. You are going to be the producer of the slasher film Inescapable Dark Studios with a cast of 20 characters.

    <span style="color:grey">***<u>Breakdown</u>***</span>

    <span style="color:grey">***46% of 20 (0.46 x 20) which is appoximately 9 characters, will portray females***</span>

    <span style="color:grey">***Of those 9 female characters 23%, or 2 will survive (0.23 x 9 ≈  2) ***</span>

    <span style="color:grey">***The remaining 11 characters (20 – 9 = 11) represent male characters.***</span>

    <span style="color:grey">***Of those 11 male characters, 13%, or 1 (0.13 x11 ≈ 1), are survivors.***</span>


16. Each group of characters (males and females) decide which characters will be survivors. They will use 3” x 5” cards to write either “dies” or “survives.”

    <span style="color:grey">***<u>For example</u> (continued from above):***</span>

    <span style="color:grey">***2 of the females are survivors; so 2 females from the group should write “survives” on their 3” x 5” card. The rest of the group should write “dies” on their card.***</span>

    <span style="color:grey">***1 of the males survived; so 1 male from the group should write “survives” on their 3” x 5” card. The rest of the group should write “dies” on their card.***</span>

    <img src="../../img/StudentHorror.png" width="300" height="400"/>
    
17. *IF* there really is no difference between genders in horror films, then the characters who survived would only have done so by chance. In other words, males and females would have an equal likelihood of surviving. In your IDS Journal, write your answers to the following questions:

    100. <strong style="color: red;">How many total people in the Inescapable Dark Studios cast are survivors? What is the total proportion of survivors?</strong>  
    
    
        <span style="color:grey">***Using the example above, there would be a total of 3 survivors from the cast of 20 students. The proportion of survivors would be 3/20 = 0.15 = 15%.***</span>

        <span style="color:grey">***Using the example above, you could expect to see 15% of males and 15% of females survive, since that was the overall proportion of survivors. So we would expect 0.15x11 = 2 male survivors, and 0.15x9 = 1 female survivor.***</span>


18. As the film director you will collect all of the 3” x 5” cards from the characters and you will shuffle the cards and redistribute them to the characters so that their genders have no influence on whether or not they survive the horror movie.  But wait, you know how to code in RStudio so you will simulate collecting and distributing the 3” x 5” index cards. The video below shows a simulation of shuffling and distributing 3” x 5” cards to the characters. Pause the video after the first shuffle.
    <iframe width="560" height="315" src="https://www.youtube.com/embed/0cHRQo2SUCw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


19. Copy the table below in your DS journal.  The table displays the proportions of survivors for each gender as well as the difference in proportions (female survivors – male survivors).

    **Note:** The first row has been filled in with the example data from above BEFORE the shuffles have taken place. These values do not match the actual horror movie data set. Recall that using all 485 characters, the proportion of females that survive is 23% vs males 13% which is a difference of 10%.


    |         | # of Female Survivors | # of Male Survivors | Proportion of Female Survivors | Proportion of Male Survivors | Difference in Proportions (Female-Male) |
|---------|:---------------------:|---------------------|--------------------------------|------------------------------|-----------------------------------------|
|         | 2                     | 1                   | 2/9=0.22                       | 1/11=0.09                    | 0.22-0.09=0.13                          |
| Take 1  |                       |                     |                                |                              |                                         |
| Take 2  |                       |                     |                                |                              |                                         |
| Take 3  |                       |                     |                                |                              |                                         |
| Take 4  |                       |                     |                                |                              |                                         |
| Take 5  |                       |                     |                                |                              |                                         |

20. Note that values in the “Difference in Proportions” column can be positive or negative because
sometimes more women will survive, and other times more men will survive.

21. Draw a dotplot in your DS journal labeled “Difference in Proportions (Female – Male).” Include a vertical line at 10% to represent the actual difference in gender survival rates in real horror movies (see example below).


    <img src="../../img/21323.png" />


22. Using the information from Steps 19, place a dot at the corresponding value for the shuffled data’s difference in proportions, then answer the following question in your IDS Journal:

    <strong style="color: red;">How does this difference compare to the actual data set’s difference of 10%?</strong>  
    
    
    <span style="color:grey">***When using the entire slasher data set, most likely, the difference in proportions will be much smaller than 10%. In fact, the difference in proportions will be centered around 0. But with such a small data set the difference will most likely not be close to 0.***</span>


23. Go back to the video and watch the rest of the shuffles (take 2 – take 5), fill in the table and the corresponding dotplot, then answer the following questions in your IDS Journal:
    
    100. <strong style="color: red;">What was the biggest difference we saw from our shuffles? What was the smallest?</strong>
    
    
    

    100. <strong style="color: red;">What do you think this dotplot would look like if you shuffled your survival cards 1000
    times?</strong> 
    
    
        <span style="color:grey">***Using the entire slasher data set, the dotplot would look roughly symmetric and centered around 0, meaning that if there were no relationship between a character’s gender and whether or not they survive, the difference in proportions would typically be 0.***</span>

24. The actual difference in gender survival (10%) is rarely seen when you assign “survives” or “dies” just by chance (aka when shuffling). 

    <strong style="color: red;">What does this mean in terms of who will die in actual horror movies?</strong>  
    
    
    <span style="color:grey">***Since you never (or rarely) saw a 10% difference in the proportions of female survivors versus male survivors, it seems that horror movies actually favor female survivors.***</span>

25. <strong style="color: red;">If you were going to be cast in a horror movie, would you want to be male or female?</strong>  


    <span style="color:grey">***You would want to be a female character because they are more likely to survive by the end of the film.***</span>

26. In the next lab, you will learn how to shuffle in RStudio in order to determine if an event is real or simply due to chance.


###**Reflection**
<strong style="color: red;">What are the essential learnings you are taking away from this lesson?</strong> 


###<p style="background: black; color: white; text-align: center;">**Homework & Next Day**</p>
For the next 5 days you will collect data for the *Stress/Chill* campaign either through the UCLA [IDS UCLA](../download/app.md) App or via web browser at [https://tools.idsucla.org](https://tools.idsucla.org "https://tools.idsucla.org")

[<u>***LAB 2E: The Horror Movie Shuffle***</u>](lab2e.md)

Complete [Lab 2E](lab2e.md) prior to [Lesson 14](lesson14.md).
