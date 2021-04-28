##***<u>Lesson 10: Making Histograms</u>***

###**Objective**
You will learn that a histogram represents observations grouped into "bins", and that bars are
drawn to show how many observations - or what proportion of the observations - lie in each bin (vs. individual observations, as in a dotplot).


###**Vocabulary**

algorithm, input, output, histogram, bin(s), bin widths, left-hand rule, right-hand rule

###**Essential Concepts**

!!! note "Lesson 10 Essential Concepts"
    Histograms can be created through the use of an algorithm. The distributions displayed in a histogram can be classified using the technical terms for the shapes of distributions. Learning to describe routine tasks through an algorithm is an important component of computational thinking.

###**Lesson**

1. Giving clear, concise instructions to others is an important skill for you to learn. In this activity you will practice using descriptive vocabulary, communicating ideas to others, recognizing steps in a process, and recognizing the importance of using clear language.

2. In order for you to understand how important giving clear and precise directions is, you will watch a video of a student reading directions to their teacher for how to make a sandwich.

3. Think back to a time when you followed a recipe. If you have not followed a recipe before, think about what it might look like.

    100. <strong style="color: red;">What kinds of things have you made?</strong>

    100. <strong style="color: red;">Do you know how to make a peanut butter and jelly sandwich?</strong>

    100. <strong style="color: red;">Would you be able to teach someone else how to make one?</strong>

    100. <strong style="color: red;">Would you be able to list the steps for making a sandwich?</strong>

4. The materials you typically need to make a peanut butter and jelly sandwich are: peanut butter, jelly, sliced bread, a butter knife, and a plate for making a sandwich.  In your IDS Journal, write down your instructions for making a peanut butter and jelly sandwich using these materials.
    
5. Precise instructions for any process are like a formula or a recipe to follow in order to get the same results each time. We can also call these instructions an **algorithm**. An algorithm is how we communicate with the computer. In this case, the person making the PB&J sandwich is the computer, and our job is to give him/her precise instructions (the algorithm) so that he/she can successfully make the PB&J sandwich.

6. Every algorithm needs **input** and produces **output**. The input here will be the steps or actions to make a PB&J sandwich, and the output will be the sandwich itself.

7. Your instructions/algorithm for making a PB&J sandwich might be randomly chosen by your teacher to model with your classmates.

8. Keep in mind that in making the sandwich your teacher must do EXACTLY what the instructions say. For example, if the directions say “Put the peanut butter on the bread,” your teacher can literally put the jar of peanut butter on the bag of
bread since there was no instruction to open the bread or the jar of peanut butter, no instruction to use
the knife in a particular way, etc.; or if it is not clear where to spread the peanut butter, the teacher might put it on the crust. A computer reads instructions very literally and has no reference point for what the instructions might intend to say.

9. Watch the clip of a teacher following a student's instructions for making a PB&J sandwich. 

    <strong style="color: red;"> Do you think the student's instructions were clear or not? What
are some instructions he might have given differently? </strong> 

    <iframe src="https://drive.google.com/file/d/1XgAysSUjoLnXEM3AK7KTc0ogbrfQVLMq/preview" width="640" height="480"></iframe>

10. Compare your instructions to the instructions you just saw. 

    <strong style="color: red;"> How would your instructions be carried out to make a PB&J sandwich? Do you need to add some clarifications to your instructions? </strong>

11. <strong style="color: red;"> Thinking about these sandwich-making experiences, do you think clear instructions are important?
Why? </strong>

12. You will develop an algorithm for building a **histogram** to represent the sleep dotplot you saw in [Lesson 9](lesson9.md).

    <iframe src="https://drive.google.com/file/d/1BffM29u9F6Ns4z76deJA3mQZum5stnrL/preview" width="640" height="480"></iframe>
    
13. Rather than showing the frequency for each value, a histogram shows the frequency **bin**. For example, we might choose bins that go from 0-5, 5-10, 10-15, 15-20, 20-25.

14. Modeled below is a histogram using the data from the *Hours of Sleep Last Night* dotplot from [Lesson 9](lesson9.md). The x-axis has **bin widths** of 0-3, 3-6, 6-9, etc., with marks on the plot at those intervals. The first bin has a frequency of 1, which means that one student got between 0 to 3 hours of sleep.

    <strong style="color: red;">Determine the frequencies of each bin and interpret what they mean.</strong>


    <iframe src="https://drive.google.com/file/d/14l68stTcznQOL0T_YqrfV-SQQzLYOTCC/preview" width="640" height="480"></iframe>

 15. Notice that multiples of three appear in more than one bin. Let’s take the value of 6 hours as an
    example. Should those observations be included in the second bin (3-6) or the third bin (6-9)?

    * If you include the values of 6 hours in the second bin (3-6), you are using the
        **left-hand rule** because when choosing between the two bins that are next to each other, (3-6) and (6-9), you chose the bin on the left.

        <iframe src="https://drive.google.com/file/d/14tBgcSHiE7hV94szrrCQ40GuZlfcbnPn/preview" width="640" height="480"></iframe>

    * If you include the values of 6 hours in the third bin (6-9), you are using the **right-hand rule** because when choosing between the two bins that are next to each other, (3-6) and (6-9), you chose the bin on the right.

        <iframe src="https://drive.google.com/file/d/1Pi_p8LTfqwL0hLnnZHpOMIPsGbrWt2mc/preview" width="640" height="480"></iframe>

16. Similar to the way you wrote a process for making a PB&J sandwich, you will write a process - or an algorithm - for creating a histogram. Create an algorithm that gives directions for constructing a histogram for the data from the *Hours of Sleep Last Night* dotplot from [Lesson 9](lesson9.md). Remember, an algorithm is a set of rules that can always be applied.  Continue thinking of the process for transforming the dotplot data to create a histogram. The input will be the dotplot data, the algorithm provides the instructions for creating the histogram, and the output is the histogram.

17. Make sure your algorithm works no matter how wide the bin will be. For instance, it might be 5 hours, it might be 1 hour, or it might be 10 hours (or even half an hour). Whatever it is, your algorithm should work for any input value.

18. In your IDS Journal, write out your algorithm as a set of steps: Step 1, Step 2, etc. Try to create a histogram with your instructions and a bin width of 4.

19. Then sketch the histogram in your IDS Journal, based very literally on your instructions.

    For example, if you did not say exactly where the bins should start, you could start one way off to the left. If you are vague and say something like "Divide the number line into groups of 10,” then the bins could be arbitrary sizes. If they have to be the same size, how would you do that? Points to consider:

    100. Where will you start drawing the bins? Always at the location of the smallest dotplot?
    Always at the greatest? A little to the left?

    100. What will you do with points that fall exactly on a boundary? Do they go to the bin on the
    left or on the right? Does it matter? 

    100. Remember that you cannot do it differently every time. You need to be consistent. You'll follow
    either the left-hand rule or the right-hand rule, depending on which one you choose.

20. <strong style="color: red;"> After following your algorithm to create your sketch, do you feel your algorithm is precise enough? Revise your algorithm as needed.</strong>

21. <strong style="color: red;"> What are the similarities and differences between the original dotplot and a histogram?</strong>

    100. <strong style="color: red;"> What have we gained from the histogram?</strong>

    100. <strong style="color: red;"> What have we lost?</strong>


###**Reflection**
<strong style="color: red;">What are the essential learnings you are taking away from this lesson?</strong> 


###<p style="background: black; color: white; text-align: center;">**Homework**</p>
Continue to collect nutritional facts data using the *Food Habits* Participatory Sensing campaign on your smart device or via web browser.