
# Reflective Report
##     Assignment For Course PA2521
####    Author: PULE, YING     Student ID: 9401064499 

   

### Article 1: “Requirements prioritization in on-line banking systems: using value-oriented framework”

#### Motivation for selection:
Firstly, the published year of the book is 2009, which is recent. So the article has its value to help me better understand the LSRE.

The article is about requirements prioritization in online banking system, and describes how a value-oriented framework work can help prioritize the requirement. The technique is easy to understand and we can execute it in large-scale requirement. The article detailedly describes the steps of prioritize requirements, and the motivation of each step. Based on the practical example, we can understand and master this technique.

#### Implementation plan:
  For the value-oriented framework which plans to be implemented, firstly, we should understand the value categories identified in our project product. We can list a table about names of the value and their definitions. For different types of value, we can give different weighted value to them, for example, for the banking system, we can give 9 points to security while we give 4 points to speed as the weighted value.
  
  Then, we can input our requirement into a table, there are different value categories with its weighted value. We can give score to each requirement’s value. As a result, we can calculate the total score of each requirement by summing the each value that we identified multiplied by the score we give. As a result, we can get a final score of each requirement. The prioritization will be executed by the order of requirements’ score. The higher score of the requirement means the requirement is more important and more valuable to execute.
  
####   Execution 
For this part, I would like to describe what I have done.
The example of the project I select is the Course Management System which has 208 requirements.
First, I have classified the requirements with other 

members. We have discussed about the value categories about these requirements through activities like brainstorming, searching for relevant knowledge on literatures.
Then we can list several values that related to the requirements with it weighed value. Such as Security(8), Student satisfaction(6), Teacher Satisfaction(6), Realizable(5), Competitive(4)... 

#### Proof of Concept

| Requirement\Value | Security(8) | Student Satisfaction(6) | Teacher  Satisfaction(6) | Realizable(5) | Competitive(4) | Score |
| --- | --- | --- | --- | --- | --- | --- |
| 11. Personal Start Page  | 5 | 5 | 3 | 4 | 2 | 116 |
| 12. Course Start Page | 5 | 4 | 3 | 4 | 2 | 110 |
| 19. User Interface Language | 5 | 3 | 2 | 3 | 2 | 93 |
| 21. Course Info | 5 | 4 | 3 | 4 | 2 | 110 |
| ... | ... |...| ... |...  |...  |...  |

So with the result of the score, we can order the requirement. That the valued-oriented result is 11> 12=21>19 as a result that can help us prioritize the requirement.

##### Lesson Learned:
From this article and my implementation , I know that the correct business strategy is the essential first step for achieving high quality of product. Through understanding of value of requirements and prioritization of requirements based on these values can help us build the prioritization well. 

For this method, it includes agreement among stakeholders(or stakeholder's viewpoints that we stand from) on business values has a visible step for prioritization.
And for later phase, the stakeholders can understand the basic operation and processes, which can raise the discussion from individual requirements to business discussion.

The VOP(value-oriented prioritization) is a good technique for Requirement prioritization phase, even in a LSRE, it also can perform well.

##### Reflection:
For my implementation of this technique, it is a little of complex but meaningful to handle and can provide a visible of result. With various kinds of value based to get the result, the score can be reliable.

From article "Value-Based Requirements Prioritization: Usage Experiences[3]" he says that for systems with a large number of early requirements(300-500 on average),simple methods like ranking is hard to handle the true value of the requirements and the result of prioritization is not reliable. For VBRP, it has several benefits that better than simple methods. Like 1. High correlation of priorities with intuition 2. Better allocate resource and build plan around high-value items 3.Ability to provide a metric of percent value delivered  and so on.
 
  



  
###   Article 2 : Choosing the “Right” Prioritization Method 

##### Motivation for selection: 
Firstly, the published year of the book is 2008, which is recent. So the article is also valuable in the requirement domain.
In this article, the author mentions several methods which have its own characteristic. The author describes the principle of each method and even make a comparison of the methods with their advantages and disadvantages. It’s a theoretical article that include many methods, I can learn a lot and pick one for own execution in this report.

##### Implementation plan:
For the implementation plan, I would like to use MoSCoW technique for my technique. For we firstly classify the requirements into different types. Then for each type of requirement, we based on our project actual demand to classify requirements into Must Have, Should Have, Could Have and Won’t Have. So, when we do the release planning, we will first focus on the Must have requirement, and then Should have requirements, Could have requirements and Won’t have requirements are less important and optional to do.


#####   Execution 
For using MoSCoW, I firstly classify the requirements into different types. Combined with the roadmap, we briefly assign requirements based on their type to different releases. Then stand for the different viewpoints, we give labels to each requirement for "Must have","Should have","Could have" and "Won't have". The activity is based on the importance and role of the requirements in the whole project. When we do the release planning, we will do the follow the order of Must->Should->Could->Won't.

##### Proof of Concept

| Number of RQ | Content | type of MoSCoW |
| --- | --- | --- |
| 1 | Restricted Interface | Should |
| 27 | Login/Logout | MUST |
| 61 | Incorrect login | MUST |
| 62 | Successful login | MUST |
| 63 | First login | COULD |
| 88 | Login Credentials | MUST |
| 89 | Information provided to the user on restriction | COULD |
| 103 | Automatic logout | Should |
| 104 | Enable and disable option for automatic logout | COULD |
| 109 | Session Manager | COULD |
| 137 | Login in time reset | Should |
| 187 | Automatically Log out  | WON't |
| 197 | Account automatically sign out | WON't |

It's the part of requirements of "LOG IN and LOG OUT", I prioritize them in to different prioritization.


##### Lesson Learned:
From this article, I can see that MoSCoW has many benefits that suitable for requirement prioritization. Like Quick and easy to perform， easy to handle the additional requirements, category information.

For LSRE, there are plenty number of requirements, we can execute a quick MoSCOW that have a first and inspired requirement prioritization, which can help us understand the requirements. 


##### Reflection:
From my implementation, it is a very visible and simple technique that be used in requirement prioritization. 

For the reference[4] that Waters mentioned that for we do the requirement prioritization also in LSRE, it is good idea to has a healthy number of Should and Could have requirements which could give some flexibility， if a project only has "MUST have" which is of highest priority, the scope can't be varied. So, using this technique is also helpful for executing them in the later phase.

From BABOK Guide that provides, if we want to do the requirement prioritization well, we should judge the option of MoSCoW to requirement by several criterias :
1. Business Value 2.relevant Risk 3.Difficulty of implementation 4.Relationship to other requirements 5. Stakeholder Agreement and so on。





### Reference 
[1] Danesh A S, Mortazavi S M, Danesh S Y S. Requirements prioritization in on-line banking systems: using value-oriented framework[C]//Computer Technology and Development, 2009. ICCTD'09. International Conference on. IEEE, 2009, 1: 158-161.

[2] Hatton S. Choosing the right prioritization method[C]//19th Australian Conference on Software Engineering (aswec 2008). IEEE, 2008: 517-526.

[3] Kukreja N, Payyavula S S, Boehm B, et al. Value-based requirements prioritization: usage experiences[J]. Procedia Computer Science, 2013, 16: 806-813.

[4]Waters K. Prioritization using moscow[J]. Agile Planning, 2009, 12.

[5]IIBA A. guide to the business analysis body of knowledge (BABOK Guide)[J]. International Institute of Business Analysis (IIBA), 2009.
   



