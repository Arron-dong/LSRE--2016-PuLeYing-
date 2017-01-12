# Seminar 3 

### Question 1: About Boston Matrix

The Boston Matrix is a more informal marketing tool used for product portfolio analysis and management. 
It considers the degree of market share and market growth and helps identify where best to use resources to maximize profit from a product management perspective. 
The Boston Matrix describes the impact of market share and market growth on businesses by using four categories: 
Dogs: Low market share and low market growth problems.
The usual marketing advice is to remove any dogs from your product portfolio as they are a drain on resources.
However, some can generate ongoing revenue with little cost.

Cash cows: High market share in low growing market
Milk these products as much as possible without killing the cow!. Often mature, well established products.

Question marks: Low market share in a high growing market
Named this, as it’s not known if they will become a star or drop into the dog quadrant. These products often require significant investment to push them into the star quadrant. The challenge is that a lot of investment may be required to get a return.

Stars: High market share in a high growing market
Can be the market leader though require ongoing investment to sustain. They generate more ROI than other product categories.

The apparent implication of its four-quadrant form is that there should be balance of products or services across all four quadrants.

(from wikipia and reference Hax A C, Majluf N S. The use of the growth-share matrix in strategic planning[J].)



-------

### Question 2: How do you connect your requirements to your architecture?


For the requirement, the inputs to your design can help you to formalize the requirements and constraints that your architecture must accommodate. 
When we design our architecture, we should follow iterative steps based on our requirements: 

1.Identify Architecture Objectives 2.Key Scenarios 3.Application overview 4.Key issues 5.Candidate solutions.

Later I have read a article named "Weaving together requirements and architectures"[5],he mentioned the twin Peaks model which can help develop progressively more detailed requirements and architectural specifications concurrently.

-------


### Question 3: Can you connect all requirements directly? What do you do if you cannot?

We can’t connect all requirements directly. For some requirements are independent worked. And also considering about the time, source, technique and so on, it is impossible to connect them directly[6].

A Requirement element can be connected to other Requirements, most commonly using Aggregate relationships to form a hierarchy of requirements. These relationships are very important, both in identifying how the Requirements are organized and used in the model, and in tracing the development from the Requirements throughout the model. 


-------


### Article “Towards a reference framework for software product management”


For this paper, the author aims at providing a structure for software product management by providing a reference framework.
For a basic framework structure: a software product management can set into 4-process area:

1.	Portfolio management: collecting of existing products, by looking for market trends and product development strategy, the decision of the product life cycle, and the establishment of a partnership and a new contract products.
2.	Product roadmapping: Planning and description of the use of science and technology resources, elements and their structural relationships in a period of time.
3.	Release planning: The release planning follow the step of prioritization, selection, write release definition, package for a prepared vision.
4.	Requirement management: Requirements management includes activities to collect, identify, modify, and organize various needs of different stakeholders. Demand management is one of the key areas in a software company
5. When it comes to the stakeholder interaction, it divided into 2 parts that we have to ensure the interaction with them work smoothly.

Internal stakeholders includes: company board, Research&innovation, Services, Development,Support and Sales$marketing
External stakeholders: Market, Partners of the company, Customers

I agree with the author idea about the interaction of stakeholders. Usually, more than one stakeholder participation needs to choose important aspects in the process of analysis, in this case, such as the budget, cost, resources and technology available, to find a group to meet the needs of users.[1]


-------


### Article “Market-Driven Requirements Engineering for Software Products” 
 
This paper is through an interview survey study to present the current practices and challenges in MDRE. For the results from the interview study, the author finds that there are some differences between the general study and actual companies implement:

Elicitation: Techniques such as customer visits, meeting with sales personnel, and working in customer’s projects are used. Many requirements are gathered from the internal sources.
Documentation: Using natural language is the most common way of documenting the requirements
Analysis: For this activity, most of the work is performed through group-discussions which can consisting of different kinds of participants and gaining different perspectives.
Validation: Validation is a difficult part in the process, different companies have different methods. Many companies release beta-version of their product the allow their customer to test it.
Release planning: The requirements relate to each other and affect the development work. During the development work, the developers should deal with requirements well under different situations. And in MDRE, different companies have different ways.
Requirement management: Some companies have their own database to collect and store requirements. Some companies use XP story cards to store relevant requirements or Top10-list to link their requirements. And some companies have their own requirement document. 

From the author’s conclusion, the literature and the results from the interview are mostly correspond and partly different. The characteristics of market-driven RE differs from the characteristics of customer-specific RE in several ways, the product are always developed in several consecutive releases for which competition is high. [2] The method used and the content summarized is valuable. Different companies have to make a wise choice for their RE.

-------


### D. Leffingwell “Scaled Agile Framework” http://www.scaledagileframework.com/

The principles of Safe is introduced  on the page of website.
1. Take an economic view 
2. Apply system thinking
3. Assume variability
4. Build incrementally with high-efficient learning cycles
5. Base milestones on working system objective evaluation 
6. Visualize and limit WIP
7. Apply
8. Motive the knowledge worker
9. Optimize the decision-making

From the page of Scaled Agile Framework, I can see several case studies, which filled with good experience.
For the SAFe, there are many users, and most of them feel good about using it.
SAFe can help deliver faster with better quality and less manpower. And as a good framework, it can help improve the quality, productivity, and employee satisfaction of the product, for example, there is a 40% defect reduction from their first round with SAFe, and 20% quality improvement and faster delivering of HP Enterprise.

I am support the framework can make an important role, and believe the comment are reliable. For the need for a reference framework for software product management is found in the desire to get an understanding of its complete domain[3]. 
SAFe has many good points:
1. Open for users to use.
2. Complete and detailed description of SAFe
3. Lots of beneficial activities for improve RE
4. Continuously improved is still processed.

And as the users' comments about their using feedback, the comments of the SAFe is quite good.


-------

 
### Article “Are You Biting Off More Than You Can Chew? A Case Study on Causes and Effects of Overscoping in Large-Scale Software Engineering”
 
In this article, the author talks about the Scope management that is an important part of software release management and a key factor of releasing successful software product.
For the interview result, the author summarizes and lists some causes of over-scoping that are partly agreed and helpful for our study:

1.	Continuous requirements inflow via multiple channels.
2.	No overview of software resource availability
3.	Low DT involvement in early phases
4.	Requirements are not consist with DT
5.	The requirement specification are not detailed enough
6.	Unclear of the overall goal
7.	Weak process adherence
And there are many bad effects of over-scoping: a. many changes will be needed to set.  b. Quality issues c. delay of delivery d. can’t satisfy the customer’s expectations e. Communication gaps ,etc

The author points out the causes and effects through this study. What he summarized is based on the interview. The study is helpful, I think in further study, author can use some experiences to get the some information and come up with some solutions to solve or reduce the risk of over-scoping.

-------

### Article “Factors Affecting Decision Outcome and Lead-time in Large-Scale Requirements Engineering”

For this paper, the purpose of the author is to figure out which characteristics of change requests may influence the decision lead-time and outcome of decision. The characteristics can be various: number of products, release number, the type of customer.
As the result the study can present:

1. The lead-time to make a decision increases when the products become more.
2. There is no significant relationship between the product releasing that a change influences and the decision lead-time.
3. Change requests from important customers can reduce the lead-time for decisions.
4. The chance of receiving a change request is higher if it affects more products
5. There is a significantly higher probability of acceptance of the changes required for late versions
6. Change requests made by key customers are more likely to be accepted.
7. Refusing to decide the advance time is longer than the time to accept the decision.

As we can see from the article, the author thinks that an important customer plays a significant role in decision. From i read an article, for software development companies should adapt their practices to customers and new research efforts addressing these issues are necessary, the more important the customer is, the higher he will influence[3].


-------


### Article “An industrial survey of requirements interdependencies in software product release planning”, in Proceedings of the fifth IEEE International Symposium on Requirements Engineering, 2001.

For this paper, the author through a survey of 5 different companies to explore the interdependencies of requirements in software product release planning.
The author points out 5 types of interdependencies, which are really helpful for our understanding of interdependency: 
AND: R1 and R2 require function to each other
REQUIRES: R1 requires R2 to function, but not vice versa
TEMPORAL: Either R1 has to be implemented before R2, or vice versa
CVALUE: R1 affects customer value for R2
ICOST: R1 can affect the cost of implementing R2
OR: R1, R2 only one to be necessary implemented.
For the summary of identified interdependencies of 5 different cases, we can the different situations in different factory, while ICOST is kind of common type. There are only 20% requirement are singular, which means that there are lots of requirements are interdependent.

For there are lots of data, formula and survey result can support the author’s finding, I am willing to think the result is reliable. Most of the requirements can not be treated independently, because they are interrelated and interact in a complex manner. Actions that may affect other requirements are not expected or not even expected, according to a request. Dependencies between requirements may also affect various decisions and activities during the development process [4].


-------


### Extra Reference:

[1] Pitangueira A M. Incorporating preferences from multiple stakeholders in software requirements selection an interactive search-based approach[C]//2015 IEEE 23rd International Requirements Engineering Conference (RE). IEEE, 2015: 382-387.

[2] Karlsson L, Dahlstedt Å G, Regnell B, et al. Requirements engineering challenges in market-driven software development–An interview study with practitioners[J]. Information and Software technology, 2007, 49(6): 588-604.

[3] De La Vara J L, Hoyos L, Collado E, et al. Towards customer-based requirements engineering practices[C]//2012 Second IEEE International Workshop on Empirical Requirements Engineering (EmpiRE). IEEE, 2012: 37-40.

[4]Dahlstedt A G, Persson A. Requirements interdependencies-moulding the state of research into a research agenda[C]//Proceedings of Ninth International Workshop on Requirements Engineering: Foundation for Software Quality, Klagenfurt/Velden, Austria. 2003: 55-64.

[5]Nuseibeh B. Weaving together requirements and architectures[J]. Computer, 2001, 34(3): 115-119.

[6]Van De Weerd I, Brinkkemper S, Nieuwenhuis R, et al. Towards a reference framework for software product management[C]//14th IEEE International Requirements Engineering Conference (RE'06). IEEE, 2006: 319-322.

