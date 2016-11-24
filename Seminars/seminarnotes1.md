Questions:

GAP Analysis

Gap analysis is a way to assess the performance differences between business information systems or software applications to determine whether or not to meet the business requirements. GAP analysis measures positive and negative 'gaps' between what the product offers and what the customer perceives[1]
For a gap analysis, we can follow 5 steps:
1.Decide the topic we’re going to do the Gap Analysis on
2.Identify where we are right now based on metrics or attributes
3.Identify where we’d like to be over a specific time frame
4.Identify the gap between where we are and where we want to be.
5.Determine how the Gap should be filled.
 
CVA Analysis

Customer value analysis, is the measurement of the same variable as the gap analysis, but adds a competitor's product of the process, analyzing the product, judging whether it's disadvantages compared to that of the competitor's products.

IVA Analysis
Internal value analysis, is a measurement whether a product compliance with the company's other products or strategies in the limits of mental resources.

What tools are available for Continuous Integration?

Jenkins, Buildbot, Travis CI, Strider. They are all open source tools.
I have no experience about using aboved tools, but from other's using experience, I know that Jenkins is a open-source continuous integration tool which is developed in Java. It has two major jobs: building/tesing software project continously and monitoring externally run jobs. We are able to build Apache Ant and Apache Maven based projects and other shell scripts or batch files for the pre or the post-build activities.

What is technical product management?

The technical product management needs Technical product managers who have understand the company technology at a deep level and interface with the Development Team in order to successfully lead the strategy for the product. Always the management includes several activity:1. Focus on the bussiness side   2. Use the technical skills to imporve priorization and the planning 3. Leverage the technical skills to close the communicaiton gap between the software prduct itself and the rest of the world.

What is roadmapping? How can you do it large scale?

Roadmapping is a technique that aims for planning an organization's technical capabilities to ensure that they meet their business or strategic objectives. The graphical characteristics of the roadmap support the strategic adjustment and dialogue between the functions of the enterprise and the organization. In other words, roadmapping has three major functions: 1.help reach a consenus about the requirement of technologies and needs 2. Provide a mechanism to help the future development work 3.Provide a framework to help plan the software development.
For large scale, we should detail the each part while we keep caring about the relationship between each part.


----------------------------------------------------------------------------------------------------------------------------------------

Article "Gorschek & Wohlin “Requirements Abstraction Model"

For this article, the author put forward a model with abstraction levels which as a response to the industrial need.The goal of RAM is to offer PM a model supporting the ability to handle requirement on multiple levels of abstraction in software requirement engineering effort.
RAM(Requirement Abstraction Model)has several benefits:
1.Compare all requirements to the product stratiegies to ensure that the requirements follow the management demand.
2.Break all the requirements down to an abstraction level where they could initiate a development effort. 
3.Work-up of the requirements that make the requirement formulated on the same level and the requirement can be compared
4.Through several levels of abstraction, all requirements can be early understand. Thus decisions about requirements can be better made.

How to action the RAM is also specified in the parer.
The fisrt step is Specify :
a. (Description) make a brief description about the requirement b.(Benfit&Reason) The content about why this requirement and the benefit of implementing this requirement should be explained c.(Risks) descirbe the potential risk d.(Title) build a title of the requirement within 5 words

The second step is Place:
The step is analyzing the level of a requirement and place it on the corresponding level. For RAM there are 4 abstraction levels: Product level, feature level and component level.

The third step is Abstraction(work up):
it includes 2 parts: 1.Make all requirements connact to the Product Level 2.Break down all requirements to Function Level.

From my point of view, RAM the author points out is really useful for the solving the direct need in industry.
From another article that about a study[3] result based on the study of 11 RAM specified requirements were selected and an exercise was conducted in academia,states that RAM provides an effective way of managing QRs and is in compliance to the ISO-9126 quality model and RAM is equally feasible for managing quality requirements as it has other benefits of requirement management.
In addition, i think that the evolution of RAM will go on, incorporating explicit support for requirements estimation, risk analysis, prioritization and requirements packaging into development practice. As the author menitoned that the work name for this endeavor isRAMv.2.0. Requirements engineering closer to and within projects will be incorporated.

----------------------------------------------------------------------------------------------------------------------------------------

Article "A method for early requirements triage and selection utilizing product strategies"

In this paper, the author presents a method for early requirements triage and selection utilizing product startegies.

The bad situation is that in market-driven product development, there are a plenty large numbers of requirements which may overload the development organization. It is very important for come up with a good solution for the project management to help select the requirements based on the overall business goal and give up others.

The Early Requirements Trige has several steps
Step 1 Specify: this is the step that can help explicitly state the goals of a product. We have to answer several questions focus on Where to go, How to get and What to do.

Step 2 Assign Weights:In this step, we will assign each of factors in the last answers.

Step 3 Compare Requirements:All requirements are assigned points for factors. Then the tool can help do the normalization based on the points for each requirement and make a clear comparison.

Later the author points out about the Requirement selection for release

Step 1 Specify product-technology roadmap: For this step, we have to draw a prodcut-technology roadmap for help us understand the relationship between releases and technonogy generations.

Step 2:Estimate resoucre: Based on the result of the Step 1, we have to analyze the feasibility of the requirements. Estimate their cost,effort and time based on differenet methods.

For the author's conclusion, the use of MERTS requires times and resources to understand and formalize. Meanwhile a "tailroing" is made to make the MERTS to fit different sizes of enterprises.

From my points of view, the MERTS method that the author points out is quite good. The step of answer Where to go? How to get there? What to do? and the Table build is really helpful. We can also read the factors and weightings of factors, sub classification ,etc.  

----------------------------------------------------------------------------------------------------------------------------------------
Article "Requirements Engineering. In search of dependent variables"

In this paper, the author mainly present a framework of dependent variables that serves as a full range to access the requirement engineering quality.
The author prints out that the bases of improve the ability to perform requirement engineering could be: 1.The requirement process itself 2.The primary product of the requirement process.
Level of quality can change differenet variables.
For Requirement phase, the dependent variables are relate to Requirements coat and time, Requirement quality.
For Project, the dependent variables that relate to Project cost and time, project estimates and degree of requirements change. 
For Product, the dependent variables relate requirment selection and degree of impact.
For Company, the dependent variables relate to Portfolio management, Strategic alignment and degree of impact.
For Sociery, the dependent variables relate to positive and negative externalities

I think the concluison that made by the author are important and helpful. At a higher level of taxonomy, We need to realize that the effects are multidisciplinary and multi-perspective. The higher level of taxonomy, the content will be more complex which including the content of lower level of taxonomy, the dependent variables are different.
From the figure 2.Forsberg study of NASA projects we can see from the picture that, the higher the project cost for requirement, the lower project cost overrun within a certain range. As we known from the previous study that, the high quality of requiremnt can make the project process go on better.

----------------------------------------------------------------------------------------------------------------------------------------
Article "Quality Requirements in Industrial Practice – an extended interview study at eleven companies"

In this paper, the author presnets an empirical study by collectiong data with 22 practiioners from 11 different companyies about the quality requirements in Industrial Practice. The main methodology that the author used is interview.
For the author's conclusion we can find some useful information and points.
For RQ1: Usability is demand the most important QR in general and especially for B2C. Meanwhile, safety is considered the most important aspect for B2B. For RQ2: The author summarize that REQUIRES(the most common for B2B) and CVAULE(the most common for B2C) are consider as the most common and important interdependency type to identify. For RQ3:the findings are that there is no big distinction between Functional requirement and Quality requirement during cost estimation. And expert opinion plays an important role for estimation. For RQ4,the author finds that the QR has different priority in different situation and he points out that the QR should be acknowledged by practitioners, mainly in practive not only theory.

From my point of views, not all QR are equally important for different types of companies. And the insight of difference can cause the difference in priorities. The result about interdependency that the author found helps us understand what types of interdependent relationships are considered the most important to be given to practitioners the instructions which begin to identify. For the role of expert is very impoartent, they can make the estimaiton more accurate based on their experience. At last but not the least, too little considering QR in project planning is still a big problem, so it is very important for PM to focus on and rely on QR to achieve beneficial advantages. 

----------------------------------------------------------------------------------------------------------------------------------------

Article "A cost-value approach for prioritizing requirements"

In this paper, the author mainly introduces the cost-value approach for prioritizing requirements which can help effectively and accurately manage the system requirement from stakerholder.
There are 5 steps to prioritize requirements.

1.The requirement engineer review the candidate requirements, checking their completeness and make sure they are started in a right way.
2.Apply AHP’s pairwise comparison method to get the value of the candidate requirements.
3.Estimate the cost of implementing candidate requirements by experts.
4.Build a cost-value diagram based on the data from step3 and step4 
5.Stakeholders use cost-value diagram to discuss about the candiadate requirements and select some candidate requirements for RP.
The author put the method in two case studies and says that the approach is useful and both value and cost is ordered by magnitude, through this diagram, we can maximize satisfaction of the stakeholder .

I think the approach the author points out is useful and easy to realize. The cost and vaule is what we have to balance when we do the software requirement. Through such a value-cost diagram we can directly judge whether a candidate requirement is suitable for our development.


----------------------------------------------------------------------------------------------------------------------------------------

Reference

[1]Gorschek T. Requirements engineering supporting technical product management[J]. 2006.


[2]Gorschek T, Davis A M. Requirements engineering: In search of the dependent variables[J]. Information and Software Technology, 2008,
50(1): 67-75.


[3]Mahmood F, Rasheed W. Quality Requirement Abstraction Model (QRAM)[J]. 2014.
