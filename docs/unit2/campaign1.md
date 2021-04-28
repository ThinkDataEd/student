##**Campaign Guidelines – Stress/Chill**

###**1. The Issue**

People report being more and more stressed everyday. This trend now extends beyond adults, to children and teenagers as well.  To understand what makes you feel stressed, some important questions to ask are:

a) What factors affect your stress/chill level?

b) Do different personality types have different things that make them happy/sad?

c) Do you like to be alone or with people?

d) Do you think that your stress/chill level is a function of your environment?

###**2. Objectives**

Upon completing this campaign, you will have compared groups and gained an understanding of variability within and between groups. You will learn how to a)conduct and use permutations to model variability, b)perform informal inference, and c)do simulations to make predictions.

###**3. Survey Questions**

Use a random number generator to generate two random times a day for the next 5 days, including a weekend if possible. If a time falls within the school day, it is up to your teacher to use this time or not.

**Note:** Enter data only for the activities in which you participated.

| **Prompt** | **Variable** | **Data Type** |
| ---------- | ---------- | ---------- |
|Take a photo of what you are doing right now.| photo |photo|
|How stressed are you feeling right now? (3 is very stressed, 0 is not stressed at all)|level|integer|
|How many people are you with (not counting yourself) up to 107,282?|howmanypeople|integer|
|Who are you with?<br>&nbsp;&nbsp;&nbsp;&nbsp; -alone<br>&nbsp;&nbsp;&nbsp;&nbsp; -friends<br>&nbsp;&nbsp;&nbsp;&nbsp; -family<br>&nbsp;&nbsp;&nbsp;&nbsp; -friends and family<br>&nbsp;&nbsp;&nbsp;&nbsp; -classmates<br>&nbsp;&nbsp;&nbsp;&nbsp; -teacher<br>&nbsp;&nbsp;&nbsp;&nbsp; -teacher and classmates<br>&nbsp;&nbsp;&nbsp;&nbsp; -strangers|who|categorical|
|Where are you?<br>&nbsp;&nbsp;&nbsp;&nbsp; -school<br>&nbsp;&nbsp;&nbsp;&nbsp; -work<br>&nbsp;&nbsp;&nbsp;&nbsp; -home<br>&nbsp;&nbsp;&nbsp;&nbsp; -public place<br>&nbsp;&nbsp;&nbsp;&nbsp; -others’ house<br>&nbsp;&nbsp;&nbsp;&nbsp; -commuting|where|categorical|
|Why are you here (in one word)?|why|text|
|AUTOMATIC|location|lat, long|
|AUTOMATIC|time|time|
|AUTOMATIC|date|date|

**When?** Surveys are taken two to three times per day at predetermined, randomly selected times.

**How Long?** About two weeks. Ideally, two of these days include a weekend.

###**4. Motivation**

It's important to remember that you must keep collecting data. 

Answer the folloiwing in your IDS Journal:
100. What is your stress/chill level in the evening versus morning?
100. Does it change everyday? How about during the weekend?

    
###**5. Technical Analysis**
You will be using RStudio.

###**6. Guiding Questions**


a) What’s my typical stress/chill level and how does it compare to whole class?

b) Do my stress/chill levels vary by weekday or weekend, or by type of people I am with?

d) Under which conditions is my stress/chill level affected?


###**7. Report**
Complete the [*What Stresses Us?* Practicum](practicum3.md). Using the data analysis and RStudio skills that you've learned in this unit, analyze your stress/chill data. 







