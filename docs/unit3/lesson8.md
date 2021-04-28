##***<u>Lesson 8: Monsters that Hide in Observational Studies</u>***

###**Objective**
You will learn about confounding factors that may impact the results of an observational study, which
is why causation can never be concluded with observational studies, only associations between variables.

###**Materials**
1. Computers

2. *Spurious Correlations* website: [tylervigen.com](http://tylervigen.com/spurious-correlations)

###**Vocabulary**
cause, confounding factors, associated

###**Essential Concepts**

!!! note "Essential Concepts"
    Confounding factors/variables make it difficult to determine a cause-and-effect relation between two variables.

###**Lesson**
1. In [Lesson 6](../unit1/lesson6.md), you looked at the relationship between a student’s GPA and the number of friends that person has on social media. It seemed that students with higher GPAs had more friends than students with lower GPAs; but does did this mean that the **cause** of a person’s GPA is the amount of friends they have? NO!

2. You also identified other variables that could have contributed to the relationship. These outside variables are called **confounding factors**. Confounding factors are variables that are related to both the explanatory variable and the response variable in an observational study.

3. Ponder the statement below:

    **“Research suggests that a rise in umbrella sales leads to decreased crime rates.”**

    In your IDS Journal, write down possible confounding factors. You should choose a variable that is related to umbrella sales - one that might lead to decreased crime rates.

4. Now that you have thought of a few possibilities, study the following diagram progression to further understand the impact of confounding factors:

    100. Step 1: The arrow shows that “a rise in umbrella sales leads to decreased crime rates”, since that is what researchers have stated.

        <img src="../../img/30804a.png" />

    100. Step 2: A variable that might be related to people buying more umbrellas - the confounding factor - might be the weather because, when it is rainy, people buy more umbrellas.

        <img src="../../img/30804b.png" />

    100. Step 3: You'll see an arrow going from “Weather” to “Crime Rates Down” because it is well known that when the weather is bad, people are less likely to be outside committing crimes.

        <img src="../../img/30804c.png" />

    100. Step 4: Remember that the original claim was that “a rise in umbrella sales leads to
    decreased crime rates”.” However, we’ve now shown that maybe buying umbrellas is not
    the only thing that could be contributing to a decrease in crime, which makes us question
    the link between the two variables.

        <img src="../../img/30804d.png" />

    100. Step 5: Therefore, we have found a confounding factor with the variable “crime rates.”
    This means we can erase the original “link” between a rise in umbrella sales and
    decreased crime rates since there are outside variables interfering. We can’t say buying
    umbrellas *causes* decreased crime rates, but we can say that a rise in umbrella sales is
    **associated** with decreased crime rates.

        <img src="../../img/30804e.png" />

5. Now that you have an understanding of what confounding factors are and how to identify them, take a look at the [*Spurious Correlations*](http://tylervigen.com/spurious-correlations) website by Tyler Vigen. This site shows many explanatory and
response variables that are randomly associated with each other.

    <img src="../../img/30805.png" />

6. For the example given above, we see that as the U.S. spends more money on science, space, and
technology, more people are dying by suicide. Clearly it does not make sense that if the
U.S. keeps spending money on science, then more people are going to commit suicide. It simply
happened by chance (or a bizarre chain of confounding factors) that the two variables are related
to each other.

7. Explore the website on your own. Choose a graph that interests you and answer the questions below in your IDS Journal:

    **Note:** There are multiple pages of graphs, so you are not restricted to simply the homepage. Also, this can be difficult, depending on the graph chosen. Some factors to consider: weather, economy, fashion trends.     


    100. <strong style="color: red;">What are the two variables shown in your graph?</strong>

    100. <strong style="color: red;">Is there a positive association or a negative association between the variables?</strong>

    100. <strong style="color: red;">Write an interpretation of this plot in the context of the data.</strong>

    100. <strong style="color: red;">Write the data points in a "spreadsheet format" in a form that RStudio could read. Each row should represent a point on the graph, and each column one of the two variables.</strong>

    100. <strong style="color: red;">By hand, make a scatterplot of the association. Describe whether the association seems strong, weak, or moderate to you.</strong>

    100. <strong style="color: red;">Do you think that the explanatory variable *causes* the response variable? Explain.</strong>

    100. <strong style="color: red;">If you answered "no" to f, then draw a diagram like in #4 with possible confounding factors.</strong>


8. Example answers to Step 7 are given below:

    <img src="../../img/30808.png" />

    100. What are the two variables shown in your graph? <span style="color:grey">***Total revenue generated by arcades
    in the US and the number of computer science doctorates awarded.***</span>

    100. Is there a positive association or a negative association between the variables? <span style="color:grey">***There is
    a direct relationship because the lines have the same shape (they follow the same
    pattern).***</span>

    100. Write an interpretation of this plot in the context of the data. <span style="color:grey">***It seems that as more
    doctorates are awarded to computer scientists, arcades are generating more
    revenue.***</span>

        <span style="color:grey">***Arcade Revenue &nbsp;&nbsp;&nbsp;&nbsp;CS doctorates***</span>

        <span style="color:grey">***&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1196 &nbsp;&nbsp;&nbsp;&nbsp;861***</span>

        <span style="color:grey">***&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1176 &nbsp;&nbsp;&nbsp;&nbsp;830***</span>

        <span style="color:grey">***etc.***</span>

    100. Answers will vary.

    100. Can you conclude that the one variable *causes* the other? <span style="color:grey">***No. Although the two
    variables are associated with one another, we do not have evidence to say that
    more doctorate awards cause arcades to make more money because the data do
    not come from a controlled experiment.***</span>

    100. Draw a diagram like the one we did together earlier (in step 4 of lesson) with possible
    confounding factors. <span style="color:grey">***Student’s diagram should look like the one below:***</span>

        <img src="../../img/30808f.png" />

9. Once you have selected a graph and have answered the above questions, share your responses with a partner. Explain why you thought your particular graph was interesting, how the two variables are related (directly or inversely), and whether or not there is a causal link between the variables.

###**Reflection**
<strong style="color: red;">What are the essential learnings you are taking away from this lesson?</strong> 

###<p style="background: black; color: white; text-align: center;">**Next Day**</p>
[<u>***LAB 3B: Confound it all!***</u>](lab3b.md)

Complete [Lab 3B](lab3b.md) prior to [Lesson 9](lesson9.md).