# Instructor's guide
---
## Detailed Lesson Plan
---

### R Stream Session 1 

Time: 9am - 10:30 am

1. Challenge:

Turn to the person next to you and tell them about a time where you've struggled with computers.

**Me:** Use this time to hand out sticky notes

#### Introduce software carpentry: 

1. Explain sticky note purpose: help and challenges.
2. Get people to stick up sticky notes if they can't connect to wifi so helpers can come help

2. **Introduce Software Carpentry:**
 - "Teaching basic lab skills for scientific computing"
 - Goal is not to make you proficient, but to give a basic foundation to build from,
   - i.e. useful concepts so you have a starting point to go on later
 - Show map of upcoming workshops
 - Global community of volunteer instructors and trainers 
 - Lesson materials are collaborated on worldwide, are free, and open source
   - Show R lesson materials

3. **Introduce R:**
 - R is a statistical programming language. It excels at data analysis and visualisation,
   but can also be used as a general purpose programming language.
 - Why R?
   - It has a large user community of researchers from many disciplines
   - It has many scientific libraries, and more are constantly being added
   - It is free

4. **What are we going to learn?**
Link to website: https://github.com/resbaz/r-resbaz-2016

 - Today:
   - The basics of how to use R and RStudio
   - How to get your data into R
   - How to interact with this data once its in R
   - Problem solving techniques (i.e. programming concepts)
   - Visualising data
   - How to get help when you're stuck
 - Tomorrow:
   - Project management (how to effectively lay out a project)
   - Keeping a backed up notebook of your work using version control
   - Collaborating with others
   - Using R on a remote cluster
      - How to navigate in the shell environment
   - How to batch process files
   - Search and replace text programmatically

**We will not be learning any statistics**
  - Statistical tests vary greatly depending on discipline, and the 
    type of data you are, or will be analysing.
  - Lots of courses at the university already to learn statistics i.e.
    statistical consulting centre: http://www.scc.ms.unimelb.edu.au/
    ( link to etherpad )
  - There's not enough time to fit both statistics and programming
    concepts into the course
  - Focus here is on the basics and best practices for scientific computing and data
    analysis

5. **Introduce Etherpad**
Link to etherpad: http://pad.software-carpentry.org/r-resbaz-2016

 - What and Why?
   - Collaborative note taking environment
   - I will be posting challenges and useful links there throughout each session
   - Work together with and get help from other attendees. 
     The best way to reinforce what you're learning is to try to teach!
 
5. **Introduce DIT4C**
Go to https://resbaz.cloud.edu.au/login

 - What and Why?
   - Teaching environment hosted on the national research cloud
     - Infrastructure available to all researchers across australia
     - Kind of like drop box or google drive, but with computational resources
   - Common teaching environment so that everyone has the same version of the tools 
     we'll be learning.
      - If you go back to the workshop website there are additional installation
        instructions for all the tools if you want to use them on your own machine later
   - I will be live coding the entire time
     - You're not expected to keep up
     - We don't recommend trying to follow along with the commands as the instructor types them
     - The challenges are your opportunity to try things out
     - Remember the lesson notes are all online for reference later!

### Challenge:
Do each one in turn, getting the attendees to follow along afterwards

Log in to DIT4C using one of:
  - Your university username and password (AAF authentication)
  - Twitter
  - GitHub account (if you know what that means, we'll talk about this more tomorrow)

Claim access to a compute node:
**This is your virtual computer online**
  - Click the "Compute Nodes" link, then click the "Claim Compute Node Access" button.
  - Select your allocated compute node from the drop down list
  - Copy and paste the access key from the etherpad

Create a container:
 - Click the "Containers" link, then the "+" button. 
 - Type in a name for your container: it must be all lower case and not conflict with
   anyone else in the room so we suggest using your own name.
 - Select "RStudio" from the drop down menu

Open RStudio
 - Click on the container (the link should be blue!)
 - A new tab will open, go to it and click on RStudio
 - A new tab will open, go to it!

### Introduction to RStudio
Go to lesson one from the online notes, ignore the vectorising note
Make sure to highlight and explain interactive pane and scripting pane (for saving your work)
as well as the environment and history tabs.
It is useful to cover the math stuff because people probably won't remember order of operations.
Get them to install the ggplot2 package

This will probably have taken most of the lesson!

### Reading in data
Go to the lesson on data.frames and skip down to the reading in data part. The first thing
we're likely to want to do is to read our own data into R!

First use `read.csv`, then show them `read.table`, and use this as an opportunity to go 
through a help file.

### Getting help
Go to the third lesson on getting help, show them CRAN Task Views, and Stack Overflow, and
the RStudio cheat sheets




