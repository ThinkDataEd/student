##***<u>Lesson 13: RStudio Basics</u>***

###**Objective**
You will learn the RStudio interface, as well as a few basic commands to discover the structure behind
a data set.


###**Vocabulary**
pane, preview, console, plot, environment

###**RStudio Commands**
data( ), View( ), names( ), help( ), dim( ), tally( ), load_labs( )

###**Essential Concepts**

!!! note "Lesson 13 Essential Concepts"
    The computer has a syntax, and it can only understand if you speak its language.
    

###**Lesson**
1. The Dashboard and PlotApp are data visualization tools that are coded in R,
the statistical programming software that academics and professional statisticians use. The
Introduction to Data Science course utilizes RStudio, which also runs on R. You will learn the
programming language of RStudio for data analysis. Watch the following video to learn RStudio Basics before moving on.

    <iframe width="560" height="315" src="https://www.youtube.com/embed/WkxCfaol3pE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

2. You can access RStudio by going to your server: <br> [https://idsucla.org/ids-servers](https://www.idsucla.org/ids-servers "https://www.idsucla.org/ids-servers"), then click on the RStudio icon on the page.

3. Your RStudio login is the same as your IDS App and IDS Homepage login.

4. Once logged in, notice each of the following **panes**, or rectangular areas, of the RStudio interface:

    100. **preview** (spreadsheet) - where you will be able to see the variables and observations
    (index); rows and columns of data

    100. **console** - where you will be entering your code

    100. **plot** - where your plots/graphs/visualizations will be generated

    100. **environment** - where you will see values and objects

5. You will be looking at a data set from The Centers for Disease Control and
Prevention (CDC), a government agency that collects data on a broad range of topics, including issues concerning teenagers.

6. You can load and view the CDC data file to the workspace by typing the following
commands into the console, then pressing the *Enter* or *Return* key on your keyboard:


    **>data(cdc)**

    **>View(cdc)**


    **Note:** If you wish, you can take notes in an RScript. As a reminder, to create an R script, find the *Menu* tab, go to **File** and click on *New File*, then click on *RScript*. Type the commands below in your RScript and Run your commands. Refer back to the video to learn how to use an RScript.


7. <strong style="color: red;"> Examine the preview pane. How are the data displayed?</strong> 

8. <strong style="color: red;"> Where on the spreadsheet can you find the variables?</strong> 
    
    100. Type the following command in the console: **>names(cdc)**

    100. <strong style="color: red;"> What do you notice? What is one variable of this data set? How many variables are
    there? How does this output compare to the information in the preview pane?  </strong>

9. The previous command lists the names of each variable in this data set, but there is a command that gives you more detailed information about the data set. 

    100. Type the following command in the console: **>help(cdc)**

        A document should appear on the bottom right-hand pane under the **Help** tab with more details about the CDC dataset.


    100. <strong style="color: red;"> What unit of measurement is height reported in? </strong>

10. You can also find the number of rows and columns in the data set. 
    
    100. Type the following command in the console: **>dim(cdc)**

    100. <strong style="color: red;"> Which number do you think represents the rows? Which one represents the columns? How does this output compare to the information in the preview and
    environment panes? How many observations are there in the data set? How many
    variables does this data set contain? </strong> 
    
        <span style="color:grey">***There are 15,624 rows, or 15,624 observations;and there are 33 columns, or 33 variables. This information is also visible in the environment pane.***</span>

11. You can also obtain the number of observations of a specific variable. 

    100. Type the following command to get the number of observations for seat belt wearers: **>tally(~seat_belt, data = cdc)**
        
        <span style="color:grey">***Notice that six categories are displayed. Each category shows the number of observations contained in it. For example, “Never” has 326 observations, meaning 326 teens reported never wearing their seat belt as a passenger in a motor vehicle. &lt;NA> = Not Available, represents teens that did not provide information about their seat belt habits.***</span>

    100. <strong style="color: red;"> What else do you notice?</strong> 
  
12. Now change the variable to height:

    100. Type the following command: **>tally(~height, data = cdc)**

        <span style="color:grey">***Notice that categories are missing. This happened because the variable height contains numbers, not categories.***</span>

    100. <strong style="color: red;"> What else do you notice?</strong> 
    
    
13. Let’s take a closer look at the variables <strong style="color: purple;">seat belt</strong> and <strong style="color: purple;">height</strong>. Brainstorm the following question:

    <strong style="color: red;"> What is the difference between the data from the variables <strong style="color: purple;">seat belt</strong> and <strong style="color: purple;">height</strong>?</strong>

14. To summarize: In data science, the variable <strong style="color: purple;">seat belt</strong> is what we call a **categorical variable**, and the variable <strong style="color: purple;">height</strong> is what we call a **numerical variable**.

15. Let’s look at the other variables in this dataset. 

    <strong style="color: red;"> Categorize each variable as categorical
or numerical: </strong>

    100. <strong style="color: purple;">eat_fruit </strong>

    100. <strong style="color: purple;"> weight </strong>

    100. <strong style="color: purple;"> grade </strong>

    100. <strong style="color: purple;"> gender </strong>

16. Throughout the IDS course you will be completing RStudio labs and learning RStudio code to work with data.

17. You can load the menu of labs by typing the following code: **>load_labs( )**

18. The **load labs** command displays a list of available labs and a selection prompt. To select Lab 1A,
type the number "1" after the selection prompt.


    <iframe src="https://drive.google.com/file/d/1SYO8OZvbFi1jOt69WbKrU3C-qwRWIYfN/preview" width="640" height="480"></iframe>


19. Next direct your attention to the plot pane, and notice the location of Lab 1A’s presentation. If you do not see it, click on **Viewer** or refresh the page.

20. Click on the arrows at the bottom right-hand side of the presentation to view each slide. Pause on
the slide titled “Syntax in action”. You should see 3 boxes, each containing a line of code.


    <iframe src="https://drive.google.com/file/d/19_QUunJUJEcV0T6-yo5GshL2fdBUwrkl/preview" width="640" height="480"></iframe>


21. Every time you see a grey box with a line of code, you must type the code into the
console. The output will appear either on the console itself or on the plot pane.

22. Type in one of the lines of code. In this particular case, the output will be a plot. Notice that the location of the plot is in the same area of the slides, but under the **Plots** tab. You can toggle between the **Plots** and **Viewer** tabs by clicking each tab.


    <iframe src="https://drive.google.com/file/d/1eSFpzWRVwn7UcVipqjzA4o_7Af85zPnq/preview" width="640" height="480"></iframe>


23. You are now ready to complete Lab 1A.


###**Reflection**
<strong style="color: red;">What are the essential learnings you are taking away from this lesson?</strong> 


###<p style="background: black; color: white; text-align: center;">**Homework**</p>
Continue to collect nutritional facts data using the *Food Habits* Participatory Sensing campaign on your smart device or via web browser.

###<p style="background: black; color: white; text-align: center;">**Lab Time**</p>
It's time to begin learning how to do data analysis in RStudio! Before going on to the next lesson, you must complete Lab 1A, Lab 1B, and Lab 1C using RStudio. The following video will show you how to log in to your RStudio account and complete Lab 1A.

<iframe width="560" height="315" src="https://www.youtube.com/embed/v3qPfE4ruQA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[<u>***Lab 1A: Data, Code & RStudio***</u>](lab1a.md)

[<u>***Lab 1B: Get the Picture?***</u>](lab1b.md)

[<u>***Lab 1C: Export, Upload, Import***</u>](lab1c.md)

Complete [Labs 1A](lab1a.md), [1B](lab1b.md) and [1C](lab1c.md) prior to [Lesson 14](lesson14.md).