##***<u>Lesson 3: Let’s Try an Experiment!</u>***

###**Objective**
You will explore the importance of randomized assignment in experiments. You will understand that
without random assignment, there might be confounding variables, and you will be able to suggest possible
confounding variables.

###**Materials**
1. Measuring tape

###**Vocabulary**
confounding factor

###**Essential Concepts**

!!! note "Essential Concepts"
    Randomized assignment is required to determine cause and effect.

###**Lesson**
1. An important point from the previous lesson is that random assignment is necessary to determine causation. Therefore, by investigating an experiment, you will be exploring the question, "Why do we need randomized assignment?"

    **Note:** Recall that in an experiment, we typically have a treatment group and a control group. In the MythBusters experiment they compared number of yawns after treatment and not any measurements before treatment, because they were comparing the treatment group to the control group (the control group is specifically here because it is a comparable untreated group - this allows us to not need “before” measurements).

2. **An Experiment at the Zoo**

    A zoo keeper claims to have a treatment that can make elephants taller. To show this, he will divide the zoo's elephants into two groups. One group will get the treatment, and the other group will not. The group that does not receive the treatment will be the control group. After the treatment, he will measure the groups to see which is taller.

    The zoo keeper divides the elephants into two groups by placing the males in the treatment group and the females in the control group. After the treatment group takes the treatment, he then decides to measure the heights of the elephants as the statistic to compare average height of the treatment group to that of the control group. If the average height of the treatment group is taller, then the treatment must have worked. 

3. Reread the experiment at the zoo in item #2. Then answer the questions below:

    100. <strong style="color: red;">How might the way the zoo keeper divided the animals affect the experiment?</strong>
    100. <strong style="color: red;">good evidence that the treatment is effective?</strong>


4. By now you have likely recognized that by putting the male elephants in one group, the outcome was predetermined, since male elephants tend to be taller than female elephants to begin with. This is an example of a **confounding factor**. Confounding factors are variables that provide an alternative explanation of the effect of the treatment on the outcome variable.

4. Ask students: “How should students be put into groups?”

5. Question to ponder:  How should elephants be put into groups? In your IDS Journal, write down at least two ways in which the elephants can be put into two groups.

6. If you flipped a coin to decide which elephant goes into each group:

    100. <strong style="color: red;">What would happen to the number of male and female elephants in each group?</strong>

    100. <strong style="color: red;">Why is it important that the groups be similar in composition?</strong>

7. In this lesson, you will begin to design your own experiment using what you have learned about experiments thus far. The question you will investigate is:

    **How does our perception of time change when exposed to a stimulus?**

    A stimulus is something that elicits or accelerates a physiological or psychological activity or response. For example, running is a stimulus that makes your heart beat faster.

8. You will try to determine the answer to the question "How long is one minute?" without the use of time aids like a watch or smartphone. In your experiment, you will subject some subjects to a stimulus and others to no stimulus. You will then analyze the data to determine if those who were subjected to a stimulus were affected in terms of their perception of how long a minute of time lasts.

9. Respond to the following questions about the elements of the experiment you are designing:

    100. What is the research question you are interested in addressing?
    100. Who are the subjects that will be participating in the experiment?
    100. How should you randomly assign the subjects into treatment and control groups? See step 12 for an RStudio method that the you can use.
    100. What is the outcome variable that you will be measuring? What unit of measurement should you use?

    **Note:** You will decide on a treatment (stimulus) to apply to each group on the following day.

10. Decide who will be the subjects in your experiment and the ways in which the experiment can be conducted (e.g., online).

11. Once you have decided who your subjects will be, assign each subject randomly to one of two groups. You may choose any random method to place them into groups or use the method in item #12.

12. One method to determine group assignment would be to make a numbered list with each of your subjects' names in alphabetical order, and use the sample() function in RStudio. In your numbered list, each subject has a number next to their name (i.e., subject #1’s name most likely starts with an A, and then we move alphabetically through the list). You can then use RStudio to randomly select which half of the numbers/students will be assigned to the treatment group. In the code below, replace x with the number of subjects in your roster. For size, the value is half of x. The output will be one of the groups. The numbers that don't get listed belong to your other group.

    **>sample(1:x, size = x/2, replace = FALSE)**

    For example, if you have 20 people on your list, your code will be:

    **>sample(1:20, size = 10, replace = FALSE)**  

13. You will conduct the experiment in the [next lesson](lesson4.md).

###**Reflection**
<strong style="color: red;">What are the essential learnings you are taking away from this lesson?</strong> 