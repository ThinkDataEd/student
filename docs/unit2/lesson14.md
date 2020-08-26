---
output:
  html_document: default
  pdf_document: default
---
##***<u>Lesson 14: The Titanic Shuffle</u>***

###**Objective:**
You will continue to understand that, just by chance, we will see differences between two groups.
They will understand that these differences are usually small.



 

###**Essential Concepts:**

!!! note "Essential Concepts: "
    We can also "shuffle" data based on numerical variables. The statistic we use is the
    difference in means. The distribution we form by this form of shuffling still represents what happens if
    chance were the only factor at play. When differences are small, we suspect that they might be due to
    chance. When differences are big, we suspect they might be 'real.'

###**Lesson:**
1.Previously you learned how to determine if a difference is due to chance by
shuffling based on categorical variables (gender and survival).

2. View the dotplot created during [Lesson 13](lesson13.md) of the difference in proportions between female and
survivors of horror movies. Remember that, "by chance," the differences were typically
.0. Most of the time, they were pretty small. Sometimes they were bigger, but that was rare and
this tells us that if we see "small" differences, we might think they are due to chance. But if we
see "big" differences, they are not.

3. In your DS Journal <strong style="color:red;">write what you think small and big differences mean. Be sure
to provide units in your answer </strong> (which are percentage points for the horror movie data). So, for example, a
"big" difference might be 5 percentage points 

4. In today’s lesson, you will learn how to determine if there is a difference
between groups when a numerical variable is involved.

5. In particular, you will assume the roles of passengers in the *Titanic* for today’s lesson. In case
you  may not know about the *Titanic*, you may want to Google Titanic or ask friends and family what they know about the ship.

6. For now it's important to know that at its time, the *Titanic* was the largest cruise ship ever built and was declared to be
unsinkable. However, on its first voyage, it sank and was one of the worst maritime disasters in
history. About 40% of passengers survived; however, your chances of survival depended very
much on your age, gender, and wealth.

7. You are going to look at whether the amount of money a passenger paid
for his/her cabin (the fare price) had anything to do with whether or not he/she survived.

8. You  will need <strong style="color:blue;"> a Titanic Shuffle activity board handout AND strips from the [*LMR_Titanic Strips*](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_Titanic Strips.pdf) file—see below for instructions. </strong>

    **Advanced preparation required:**

    The Titanic Shuffle activity LMR contains data from 40 actual passengers on the titanic. Each strip
    represents the data from one passenger: the left hand side shows the fare paid and right hand
    side contains the survival information of that passenger after the collision. Randomly select 4 Survivor strips and 6 Victim strips from the LMR.  <strong style="color:red;">Record the fares into the Titanic Shuffle activity board such that the fare price is attached to the survivor status for each of the 10 observations selected.</strong>
    <div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://curriculum.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_Titanic Strips.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_Titanic Strips](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_Titanic Strips.pdf)</div>

9. 40 strips were created for a large class. However, you will do this activity at home using 10 strips.


10. The price on the strip represents the amount of money paid for their ticket to board the *Titanic*. 
$20 in 1912 is worth about $500 today.

11. You will divide the strips into two piles. The first pile will have 4 survivors and and the second pile will have 6 victims.

12. <strong style="color:red;"> In your DS Journal 
calculate the mean fare for each pile.  </strong>

13.  Find the difference between the mean fares for the two groups.

    mean of “Survivor” fares – mean of “Victim” fares

    <span style="color:grey">***<u>For example:</u>***</span>

    <span style="color:grey">***If all 15 survivor cards and all 25 victim cards are used, the difference is
    means would be:***</span>

    <span style="color:grey">***$43.55 – $17.76 = $25.79***</span>

14. One of the controversies of the *Titanic* disaster was that some people felt that the rich
people were given better access to the lifeboats than were the poor, so rich people were more
likely to survive. Note that the data represented on the fare cards are only a subset of the actual
*Titanic* data, which had over 800 passengers. However, the data were randomly selected from
the real data and are considered representative of the 800 passengers.

15. Answer the following question in your DS Journal:

    100. <strong style="color:red;"> Based on the data from our dotplots, do you think rich people were more likely to
    survive? In other words, did passengers who paid more for their tickets have a better
    chance of survival?</strong>
    

16. Your teacher will give you an opportunity to share and discuss with your classmates.

17. Tear each strip such that you separate the fare from the outcome (survivor or
victim). Randomly shuffle the outcomes.

    Distribute the shuffled outcome to the passengers ( 6 victims, 4 survivors) to each of the fares. 

18. Think about the following question and record in your DS Journal:

    100. <strong style="color:red;"> Why do we shuffle the survivor/victim strips and not the fare strips? </strong>

    100. <strong style="color:red;">What do you think the mean fare difference of our shuffled groups will be? </strong> <span style="color:grey">***Your teacher will give you an opportunity to discuss this question***</span>

19. Repeat the process of shuffling by survival status, redistributing and calculating the mean fare price for each group 4 more times. <strong style="color:red;"> Record results in your journal </strong>

    100. <strong style="color:red;"> Do you think this difference, of ___ dollars, is real or due to chance? </strong>

20. <strong style="color:red;"> Create a table to display the mean fare prices for each group, and include a column
for the difference (mean “Survivor” fare – mean “Victim” fare). Fill in the table with the values the
 found in Step 13.</strong> **<u>Note:</u>** The first row has been filled in with the example data from
above BEFORE the shuffles have taken place.

    | Mean Fare Price of Survivors | Mean Fare Price of Victims | Difference in Means (Survivors - Victims) |
    |------------------------------|----------------------------|-------------------------------------------|
    | $43.55 | $17.76 | $43.55 - $17.76 = $25.79 |
    | ? |  |  |

21. Note that values in the “Difference in Means” column can be positive or negative because
sometimes the survivors will pay more for their tickets, and other times the victims will pay more
for their tickets.

22. Draw a dotplot on the board labeled “Difference in Means.” Include a vertical line at $25.79 (or
whatever value was calculated in Step 13) to represent the actual difference in the
mean fare prices between the survivors and the victims (see example below).

   

23. Using the information from Steps 19 and 20, place a dot at the corresponding value
for the shuffled data’s difference in means. 

    100. How does this difference compare to the actual difference of $25.79 (from Step 13)?
    <span style="color:grey">*** yours may be different from a classmate. Most likely, the difference in means will be much
    smaller than $25.79. ***</span>

24. Remember:  a small differences might be due to chance and big differences typically
mean that there is a “real” difference between groups. In this case, a big difference might mean
that the rich passengers were more likely to survive. And a small difference might mean that
survival was just a matter of plain luck.

25. <strong style="color:red;"> Record all your mean differences in the chart for all 5 rounds of the activity. </strong>

26.<strong style="color:red;"> Do you think the real difference in mean fare prices you
calculated in Step 13 ($25.79 if all cards were used) is small or large. </strong>

27. One way that we can decide what is “large” or “small” is by creating cut-off values that
we think are too far away from the center of the distributions of differences. In general, we can
assign a rule that states that any difference in mean fare prices that is greater than 2 MAD values
above or below the mean is considered unusual. This means that any value in the outer edges of
the plot would indicate that a passenger’s ticket price impacted his/her chances of survival.

28. You will use RStudio to shuffle the actual *Titanic* data of all 800 passengers
during the next lab and can decide if the difference in survival rates of rich passengers and
poor passengers was real, or just due to chance.


In your DS Journal, <strong style="color:red;"> write  what you think the 3 most important topics of the lesson are.</strong>

###<p style="background: black; color: white; text-align: center;">**Homework & Next Day**</p>
For the next 3 days, students will collect data for the *Stress/Chill* campaign either through the UCLA [IDS
UCLA](../download/app.md) App or via web browser at [https://tools.idsucla.org](https://tools.idsucla.org "https://tools.idsucla.org")

[<u>***LAB 2F: The Titanic Shuffle***</u>](lab2f.md)

Complete [Lab 2F](lab2f.md) prior to [Lesson 15](lesson15.md).
