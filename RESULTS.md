## Methodology
Our experimentation with this project can be divided into two parts- the black box testing and a comparitive study.
- Black box testing- This included following set of instructions for a variety of purposes like-
  Downloading and installing this project including all the requirements.
  Executing the project efficiently and understanding how it works.
  Using the project for user's customised usage.
- Comparative Study- Since our project is a simplified version of git, it is very important to determine the difference between the two and contrast it briefly to understand the pros and cons of both. For the same, we conducted an experiment.
Step1- We asked the user to create a repo with a readme file and then clone it on their system after installing the project.
Step2- The user was asked to edit the readme file locally.
Step3- User then would commit changes on github, thus creating a merge conflict when he would later push the changes from the local machine.
Step4- We allowed the user to try to solve merge conflicts by himself using the traditional git commands.
Step5- We then facilitated the usage of GITS SYNC command to do the above task and surveyed the user on the basis of ease of solving conflicts, how likely the user will use this functionality and how smooth the process turned into.

## Material

## Observations
During the experiment, the participants will experience a new command called "GITS SYNC" that resolve the merge conflict situation when they push to the GitHub repository. It is important to know the participant's level of mastery on the Git commands. Also, we want to compare what the participants think to solve merge conflict in the traditional way v.s. GITS SYNC.

### Participants' GIT Commands Levels
<b>1: Not Familiar - 5: Master</b>
<img src="/img/pre1.png">
<img src="/img/pre2.png">
<b>1: Easy - 5: Hard</b>
<img src="/img/pre3.png">

### Participants' feedback about GITS SYNC
<b>1: Easy - 5: Hard</b>
<img src="/img/post1.png">
<b>1: Easy - 5: Hard</b>
<img src="/img/post2.png">
<img src="/img/post3.png">

## Analysis  
When looking at the graphs, we can find a very strong correlation between the ratings. Majority of the candidates (60%) had familiarity with GIT. Following along, everyone of them (even less familiar candidates) said that they had experienced merge conflict. The numbers also state that this is not a simple matter which can be resolved quickly, but indeed can consume a lot of efforts. This indicates that the issue is a common problem, justifying the need to make a project towards solving that issue. The objective is quite fruitful and can help a lot. 
  
We can see that we have a majority of candidates saying that it is easy to install as well. Here, the difference in familirtiy with GIT or conflicts does not matter because experience will get better for everybody if the install process can be made more convinient. So ideal result expected here could be to have almost all of the users say that the software is easy to install. Thus we can say that there can be some scope of improvement when it comes to setting up the project on a system.  
  
When it comes to checking if a candidate would recommend it to someone, the project got very good rating(8/10). This indicates that once set up, the project is easy to use and configure. Additionally it indicates that the project has an edge at the handling conflicts. This points to good implementation.

## Conclusion
1. All the participants have faced merge conflict issue while using GIT and nearly all the participants find it difficult to fix merge conflict.
2. 90% Participants found it easy to install our project.
3. All the participants found it very easy to fix merge conflict using "GITS SYNC" command of our project as they didn't have to go through the manual and time consuming process of fixing those merge conflicts. Participants are likely to recommend this feature of our project to others.

## Threats to Validity
There are a few things in our experiment which could be improved to have a clearer and more accurate statistics. Following are some highlights -

1. The candidates were using different machines with different configurations, and different network connections. Even though we tried to maintain the same environment by using Linux(locally or via VCL), the latency and speed factors still could affect the experience in subtle but important ways.  
2. The familiarity of different candidates with GIT was not considered to be equal. So if we ask if they would recommend this, the answers can vary because of different levels of comfort with GIT.  
3. There were some additional modules needed in python, this can create bias pertaining to the familiarity of python. The experiment would be longer for someone who doesn't have the compiler or even the package manager installed. This could affect the user feedback.  
4. The project stresses on some specific parts of GIT, especially the merge conflict. Someone who has likely experienced the worst of it would definitely give a better review and analysis, as compared to someone who rarely experienced it.  
5. The candidate's review is captured based on some fixed scales, and not given much room for subjective review. Due to this, some of the aspects are not examined in very detail regarding the review.  
