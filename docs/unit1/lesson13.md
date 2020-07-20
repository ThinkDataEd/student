##***<u>Lesson 13: RStudio Basics</u>***

###**Objective**
You will learn RStudio’s interface, as well as a few basic commands to discover the structure behind
a data set.


###**Vocabulary**
pane, preview, console, plot, environment

###**RStudio Commands**
data( ), View( ), names( ), help( ), dim( ), tally( ), load_labs( )

###**Essential Concepts**

!!! note "Essential Concepts:"
    The computer has a syntax, and it can only understand if you speak its language.
    

###**Lesson:**
1. The Dashboard and PlotApp are data visualization tools that are coded in R,
the statistical programming software that academics and professional statisticians use. The
Introduction to Data Science course will utilize RStudio, which also runs on R. You will learn the
programming language of RStudio for data analysis.

2. You can access RStudio by going to the URL: [https://tools.idsucla.org](https://tools.idsucla.org "https://tools.idsucla.org") and
then click on the RStudio icon on the page.

3. Your RStudio login is the same as your IDS App & IDS Homepage login.

4. Once logged in, notice each **pane**, or rectangular area, of the RStudio interface:

    100. **preview** (spreadsheet) - where you will be able to see the variables and observations
    (index); rows and columns of data

    100. **console** - where you will be entering your code

    100. **plot** - where your plots/graphs/visualizations will be generated

    100. **environment** - where you will see values and objects

5. You will be looking at a data set from The Centers for Disease Control and
Prevention (CDC), a government agency that collects data about teenagers on a variety of topics.

6. You can load and view the CDC data file to the workspace by typing the following
command in the console and then typing the Enter or Return key on your keyboard: **<u>Note:</u>** You will be taking notes in an RScript. On the menu tab, go to File, then click on New, then click on RScript. Type the commands below in your RScript and Run your commands. Refer back to the video to learn how to use an RScript.

    **>data(cdc)**

    **>View(cdc)**

7. Examine the environment pane. <strong style="color: red;"> Describe how the data are displayed. </strong> 

8. <strong style="color: red;"> Since the data are displayed in rows and columns, where do you think you can find the variables in the CDC data set? </strong> Type the next command in the console:

    100. **>names(cdc)**

    100. <strong style="color: red;"> What do you notice? What is one variable of this data set? How many variables are
    there? How does this output compare to the information in the preview pane?  </strong>

9. The previous command lists the names of each variable in this data set but there is a command that gives you more detailed information about the data set. Type the following
command in the console:

    100. **>help(cdc)**

    100. <strong style="color: red;"> What unit of measurement is height reported in? </strong>

10. You can also find the number of rows and columns in the data set. Type the following command in the console:

    100. **>dim(cdc)**

    100. <strong style="color: red;"> Which number do you think represents the rows? Which one represents the
    columns? How does this output compare to the information in the preview and
    environment panes? How many observations are there in the data set? How many
    variables does this data set contain? </strong> 
    
    <span style="color:grey">***There are 15,624 rows, or 15,624 observations;
    and there are 33 columns, or 33 variables. This information is also visible in the
    preview pane.***</span>

11. You can also access the number of observations of a specific variable. Type the following command to get the number of observations for seat belt wearers:

    100. **>tally(~seat_belt, data = cdc)**

    100. <strong style="color: red;"> What do you notice? Describe the output. </strong> 
    
    <span style="color:grey">***Notice that six categories are
    displayed. Each category shows the number of observations contained in it. E.g,.
    “Never” has 326 observations, meaning 326 teens reported never wearing their
    seat belt as a passenger in a motor vehicle. &lt;NA> = Not Available, represents teens
    that did not provide information about their seat belt habits.***</span>

12. Now change the variable to height:

    100. **>tally(~height, data = cdc)**

    100. <strong style="color: red;"> What do you notice? Describe the output. </strong> <span style="color:grey">***The levels are missing. It happened
    because the variable height contains numbers, not categories.***</span>

13. Let’s take a closer look at the variables seat_belt and height. Maximize the console. Brainstorm the following question:

   <strong style="color: red;"> What is the difference between the data from the variables seat_belt and height? </strong>

14. To Summarize: In data science, the variable seat_belt is what we call a **categorical variable**, and
the variable height is what we call a **numerical variable**.

15. Let’s look at the other variables in this data set. <strong style="color: red;"> Categorize each variable as categorical
or numerical: </strong>

    100. <strong style="color: red;"> eat_fruit </strong>

    100. <strong style="color: red;"> weight </strong>

    100. <strong style="color: red;"> grade </strong>

    100. <strong style="color: red;"> gender </strong>

16. You will be learning RStudio code to work with data and will be completing
RStudio labs throughout the course.

17. You can load the menu of labs by typing the following code:

    **>load_labs( )**

18. The load labs command displays a list of available labs and a selection prompt. To select Lab 1A,
type number 1 after the selection prompt.

19. Next, direct your attention to the plot pane. Notice the location of Lab 1A’s presentation. If you do not see it, click on Viewer or refresh the page.

20. Click on the arrows at the bottom right-hand side of the presentation to view each slide. Pause on
a slide titled “R’s most important syntax.” There are 3 boxes, each containing a line of code.

21. Every time you see a grey box with a line of code, you are to type the code in the
console. The output will appear either on the console itself or on the plot pane.

22. Type in one of the lines of code. In this particular case, the output will be a plot. Notice that the location of the plot is in the same area of the slides but under the Plots tab. You can toggle between the plots and presentation tabs by clicking each tab.

23. You will be completing the first lab, 1A, the next day of class.


###<p style="background: black; color: white; text-align: center;">**Homework & Next 3 Days**</p>
You should continue to collect nutritional facts data using the Food Habits Participatory Sensing
campaign on your smart device or via web browser.

[<u>***Lab 1A: Data, Code & RStudio***</u>](lab1a.md)

[<u>***Lab 1B: Get the Picture?***</u>](lab1b.md)

[<u>***Lab 1C: Export, Upload, Import***</u>](lab1c.md)

Complete [Labs 1A](lab1a.md), [1B](lab1b.md) and [1C](lab1c.md) prior to [Lesson 14](lesson14.md)