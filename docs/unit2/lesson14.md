---
output:
  html_document: default
  pdf_document: default
---
##***<u>Lesson 14: The Titanic Shuffle</u>***

###**Objective**
You will continue to understand that just by chance, you can see differences which are usually small - between two groups.


###**Essential Concepts**

!!! note "Lesson 14 Essential Concepts"
    We can also "shuffle" data based on numerical variables. The statistic we use is the difference in means. The distribution we form by this type of shuffling still represents what happens if chance were the only factor at play. When differences are small, we suspect that they might be due to chance. When differences are big, we suspect they might be "real".

###**Lesson**
1. You've already learned how to determine if a difference is due to chance by shuffling based on categorical variables (<strong style="color:purple;">gender</strong> and <strong style="color:purple;">survival</strong>).

2. View the dotplot created during [Lesson 13](lesson13.md) of the difference in proportions between female and survivors of horror movies. Remember that "by chance," the differences were typically .0. Most of the time the differences were pretty small. Sometimes they were bigger, but that was rare, and this tells you that if you see "small" differences, you might think they are due to chance; but if you see "big" differences, they are not.

3. In your IDS Journal, write what you think small and big differences mean. Be sure to provide units in your answer (which in the case of the horror movie data are percentage points). For example, a "big" difference in the horror movie data might be 5 percentage points. 

4. In today’s lesson you will learn how to determine if there is a difference between groups when a numerical variable is involved.

5. For today's lesson, you will assume the role of passenger on the Titanic. In case you may not know about the Titanic, you may want to Google "Titanic" or ask friends and family what they know about the ship.

6. For now it's important to know that at its time, the Titanic was the largest cruise ship ever built and was declared to be unsinkable. However, on its first voyage, it sank and was one of the worst maritime disasters in history. About 40% of passengers survived; however, the passengers' chances of survival depended very much on their age, gender, and wealth.

7. You are going to look at whether the amount of money a passenger paid for his/her cabin (the fare price) had anything to do with whether or not he/she survived. For this next activity, you will need 2 documents:

    100. The [*Titanic Shuffle Activity Board handout*](https://ucla.box.com/s/tu4yujf3y0rvokh21iz8tbf8qplwt3bk). <strong style="color: black;">Click on the document name to download a fillable copy</strong>.


        <div align="center"><iframe src="https://app.box.com/embed/s/tu4yujf3y0rvokh21iz8tbf8qplwt3bk?sortColumn=date&view=list" width="500" height="400" frameborder="0" allowfullscreen webkitallowfullscreen msallowfullscreen></iframe>
    
    
    100. A set of [*Titanic Strips*](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_Titanic Strips.pdf). Click on the document name to download a pdf.

        Forty strips representing the data of 40 actual passengers on the Titanic were created for a large class. However, you will do this activity at home using 10 strips. Each strip represents the data from one passenger: the left-hand side shows the fare paid and right-hand side contains the survival information of that passenger after the collision. Randomly select and cut out 4 Survivor strips and 6 Victim strips.

        **Note:** The prices on the strips represent the amount of money that a given passenger paid for their ticket to board the *Titanic*.  Twenty dollars in 1912 is worth about $500 today.


        <div align="center"><iframe src="https://docs.google.com/viewerng/viewer?url=https://curriculum.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_Titanic Strips.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe>

    
8. Record the fares from your 10 strips into the *Titanic Shuffle Activity Board*, matching the fare price and survivor status for each of the 10 observations selected.

9. Now divide the strips into two piles. The first pile will have 4 survivors and and the second pile will have 6 victims.

10. In your IDS Journal, calculate the mean fare for each pile.

11.  Find the difference between the mean fares for the two groups:

    <strong style="color:black;">mean of “Survivor” fares – mean of “Victim” fares</strong>

    <span style="color:grey">***<u>For example:</u>***</span>

    <span style="color:grey">***If all 15 survivor cards and all 25 victim cards are used, the difference is
    means would be:***</span>

    <span style="color:grey">***$43.55 – $17.76 = $25.79***</span>

12. One of the controversies of the Titanic disaster was that some people felt that the rich people were given better access to the lifeboats than were the poorer passengers, so rich people were more likely to survive. Note that the data represented on the fare cards are only a subset of the actual Titanic data, which had over 800 passengers. However, the data were randomly selected from the real data and are considered representative of the 800 passengers.

13. <strong style="color:red;"> Based on the data from our dotplots, do you think rich people were more likely to survive? In other words, did passengers who paid more for their tickets have a better chance of survival?</strong>

14. Your teacher will give you an opportunity to share and discuss with your classmates.

15. Tear each strip by separating the fare from the outcome (survivor or victim). Randomly shuffle the outcomes, then distribute the shuffled outcome to the passengers (6 victims, 4 survivors) to each of the fares. 

16. Write your answers to the following questions in your IDS Journal:

    100. <strong style="color:red;"> Why do we shuffle the survivor/victim strips and not the fare strips? </strong>

    100. <strong style="color:red;">What do you think the mean fare difference of our shuffled groups will be?</strong>
    
17. Repeat the process of shuffling by survival status 4 more times, redistributing and calculating the mean fare price for each group. Write down your results in your IDS Journal.


    <strong style="color:red;"> Do you think this difference of ___ dollars is real or due to chance? </strong>

18. In your IDS Journal, create a table to display the mean fare prices for each group, and include a column for the difference (mean “Survivor” fare – mean “Victim” fare). Fill in the table with the value found in Step 13.


    **Note:** The first row has been filled in with the example data from above BEFORE the shuffles have taken place.


    | Mean Fare Price of Survivors | Mean Fare Price of Victims | Difference in Means (Survivors - Victims) |
    |------------------------------|----------------------------|-------------------------------------------|
    | $43.55 | $17.76 | $43.55 - $17.76 = $25.79 |
    | ? |  |  |

19. Note that values in the “Difference in Means” column can be positive or negative because sometimes the survivors will pay more for their tickets, and other times the victims will pay more for their tickets.

20. Draw a dotplot in your IDS Journal and label it “Difference in Means.” Include a vertical line at $25.79 (or whatever value was calculated in Step 11) to represent the actual difference in the mean fare prices between the survivors and the victims (see example below).

21. Using the information from Steps 17 and 18, place a dot at the corresponding value for the shuffled data’s difference in means. 

    100. How does this difference compare to the actual difference of $25.79 (from Step 11)?

        <span style="color:grey">*** Yours may be different from that of a classmate. Most likely the difference in means will be much smaller than $25.79. ***</span>

22. Remember: Small differences might be due to chance, and big differences typically mean that there is a “real” difference between groups. In this case, a big difference might mean that the rich passengers were more likely to survive, and a small difference might mean that survival was just a matter of plain luck.

23. <strong style="color:red;"> Record all your mean differences in the chart for all 5 rounds of the activity. </strong>

24. <strong style="color:red;"> Do you think the real difference in mean fare prices you calculated in Step 11 ($25.79 if all cards were used) is small or large? </strong>

25. One way that we can decide what is “large” or “small” is by creating cut-off values that we think are too far away from the center of the distributions of differences. In general, we can assign a rule that states that any difference in mean fare prices that is greater than 2 MAD values above or below the mean is considered unusual. This means that any value in the outer edges of
the plot would indicate that a passenger’s ticket price impacted his/her chances of survival.

26. In the next lab, you will use RStudio to shuffle the actual Titanic data of all 800 passengers. You decide if the difference in survival rates of rich passengers and poor passengers was real, or just due to chance.


###**Reflection**
<strong style="color: red;">What are the essential learnings you are taking away from this lesson?</strong> 


###<p style="background: black; color: white; text-align: center;">**Homework & Next Day**</p>
For the next 3 days, you will collect data for the *Stress/Chill* campaign either through the UCLA [IDS UCLA](../download/app.md) App or via web browser at [https://tools.idsucla.org](https://tools.idsucla.org "https://tools.idsucla.org")

[<u>***LAB 2F: The Titanic Shuffle***</u>](lab2f.md)

Complete [Lab 2F](lab2f.md) prior to [Lesson 15](lesson15.md).
