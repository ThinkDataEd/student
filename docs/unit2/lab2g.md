##***<u>Lab 2G - Getting It Together</u>***
Directions: Follow along with the slides and answer the questions in **bold** font in your IDS Journal.

###**Putting data together**
* So far in the labs you've only looked at individual data files.

* However, you can gain additional insights by including information from a separate data set.

* In this lab you will learn how to merge information from your *personality color* data with your *stress/chill* data.

* *Export*, *upload*, and *import* your *Personality Color* data set and name it ```colors```.

* Then, *export*, *upload*, and *import* your *Stress/Chill* data set and name it ```stress```.

###**Looking at stress/chill**
* Now you'll analyze the research question:

    *How do people's personality colors and/or sports participation affect their stress levels?*

* You already have data about *personality color* and a seperate data set about *stress*. What you don't have is a single data set with information from both...yet. You'll start by strategizing on how to merge your data together.

###**Deciding how to merge**
* Before you merge data, you'll need to decide *how* you plan to merge it.

* You can *stack* your data sets, which means you can take the rows from one data set and add them to the bottom of the other data set.

* You can also *join* your data sets horizontally. You do this by taking one data set's columns and adding them to the end of the other data set's columns, based on matching an *ID* variable. The *ID* variable will have entries that you use to *match* observations in both data sets.

* **To answer the statistical question of interest, would it make more sense to *stack* or *join* your ```colors``` and ```stress``` data?**

###**Finding variables in common**
* Look at the ```names``` of the variables in each data set. To merge different data sets together, you need to find variables they share in common.

* **Which variables do the data sets have in common?**

* **If you merge data sets based on a shared variable, which variable would you choose? Why not the others?**

###**Caution required**
* Whether *stacking* or *joining*, you need to be careful when you merge data.

* When *stacking* data, you must be absolutely certain that the variables you're stacking represent the exact same measurements For example, you wouldn't want to stack ```height``` in meters and ```height``` in inches without converting one to the other.

* When *joining* data, you must make sure that the *id* variable in your primary data set matches to *one* and *only one* observation in the joining data. Otherwise, ```R``` won't know which observation to match to.

###**Getting ready**
* The goal is to add the variables from the ```colors``` data onto the ```stress``` data.

* Start by ensuring that every ```user.id``` in the ```colors``` data is unique. If there's a duplicate, have your teacher remove the duplicate from the IDS *Response Manager*, then re-export, *upload*, and *import* your ```colors``` data.

* **After you add the data from *colors* to *stress*, how many rows should your merged data have? Write this number down.**

###**Putting them together**
* You can use the ```merge``` function to join your data sets together using the variables that appear in both sets.

* **Fill in the blanks below to join the information from the ```colors``` data onto the ```stress``` data.**

        merge(____, ____, by = "____")

* ```Assign``` this ```merged``` data set the name ```stress_colors```. Make sure your data has the same number of observations that you wrote down on the previous slide.

###**Saving your data**
* ```View``` your merged data and make sure nothing appears to be obviously wrong with it.

* **Why didn't you stack the rows of data instead?**

* **What happens if you swap the order of the data sets in the ```merge``` function?**

* Fill in the blank below to save your ```stress_color``` data for later use.

        save(stress_colors, file = "stress_colors.rda")

* Be sure to look in the *Files* tab to make sure your data was saved.

###**Moving on**
* In the next lab, you'll begin analyzing your merged data. In the meantime:

    – **Make a few plots using variables from the ```stress``` data and *facet* or *group* the plots based on variables from the ```colors``` data.**

    – **Write down the most interesting discovery you make by just exploring your data. Write out how you found your discovery and interpret what it means for the people in your class.**

    – **With your *colors* data, you could answer questions about the *typical* color scores in your class. Why can this question no longer be answered in your ```stress_color``` data?**