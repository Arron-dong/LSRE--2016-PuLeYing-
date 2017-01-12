
# Seminar 1

## Homework 1.23 Date 11.3-11.10
-------



#### Q1:What is large scale requirements engineering?

The complexity and size of software intense system grows continuously which in turn gives increasingly large number and complex sets of requirements. As a result, the size and complexity of requirements database grow faster[1]. 
The order of magnitude is ~1000 requirements.




#### Q2:What are the challenges in large scale requirements engineering?

1.Sustainable requirements architectures: fighting information overload

2.Effective requirements abstractions: fighting combinatorial explosions.

3.Emergent quality predictions: fighting over-scoping

From the paper [4]: overload control, connecting fragments, Long-term product strategy and so on.

4.Pressure of time of completing the the whole requirement.

5.The customer can't provide the things related to the requirements that we need.

6.Lack of domain knowledge and technique facing so many requirements which include the risk and problems.


#### Q3:What is the order of magnitude of the number of requirements we are discussing?

1000 requirements  （SSRE 10 ,MSRE 100, VLSRE 10000）

#### Q4: Read up on and summarise [Strategic] Release Planning

RP(Release planning) comes up with decisions related to selecting and assigning features/requirements to create a sequence of consecutive product releases that satisfies important technical, resource, budget, risk management and so on . 
A good RP should:
* 1. Provide maximum business value by offering the best possible blend of features in the right release.
* 2. Satisfy the stakeholders who are the most important.
* 3. Be feasible with resources and reflect existing dependencies requirements or features.


-------



#### Article "The Art and Science of Software Release Planning" 

This paper introduce two approaches to release planning. The first one is the art of RP approach depends on human activities like intuition, communication and capabilities to negotiate between constraints and conflicting objectives. The other one is science of RP which through analyzing the problem and applying suitable algorithms to build the best solution. The author hope to create a synergy between the both.

There are some difficulties of creating a release plan:

1.Understanding of the planning objectives, constraints, stakeholders and feature preferences. 2. The planning scope is limited to the next release. 3.The project management includes many steps, how to perform the process effectively and efficiently is a challenge.

Later, the author introduce some essential part of RP which we have to consider by some equations. 1.Decision variables aims at assigning the feature to K of release options.  2.Dependencies between features and meanwhile a coupling relation called C and a precedence relation called P are used. 3.Resource constraints, every feature require an amount of source, and it should be within the capability 4.Stakeholders, different stakeholeders have different level of importance, so their feedback or idea has different influence. 5.Feature prioritization usually voted by stakeholders and make a order 6. Objective function

At last, the author comes up with a hybrid approach based on integer linear programming. There are several phases. Phase1:Modeling (including a.Plan objectives and constraints b.Offer stakeholder voting. c.Estimate resources.)  Phase2: Exploration（generate the solution plan） Phase3:Consolidation(the algorithm's solution will be evaluated by decision makers)

For this article, i will point out some parts of the viewpoints that i agree with.

When the author points out the Dependencies between features, it is really important. There are lots of dependencies and interactions between features during the development, if we ignore one part, it may influence others or make the whole planning fail. So, we have consider it when we do the RP[8].
Different Stakeholder has different influence in planning, a product has different functions aims at serving different stakeholders, give a degree to stakeholders and later we can judge the importance of information from stakeholders.
The approach with the modeling-exploation-consolidation step is good. It is very effective.


-------



#### Article "A Case Study Evaluation of the Guideline-Supported QUPER Model for Elicitation of Quality Requirements" 
This is the paper through a case study to evaluate QUPER Model for Elicitation of Quality Requirements.
QUPER Model aims to support high-level decision-making in release planning of quality requirements. The author points the steps of QUPER  Model.

* Step1: Identify candidate QR. It refers that when we define QR, we have to consider relevant features, niche market, competitors, and the hardware platform.
* Step2: Define scale and unit. It means that a scale and a measurement unit can be used to help us express the level of QR.
* Step3: Identify reference levels. It is based on actual products and help further calibrate QR's estimation and objective measures.
* Step4: Elicit quality breakpoints. This step is that, firstly, the utility breakpoint is determined. Then, the saturation breakpoint is determined. We determine the differentiation breakpoint between the utility and the saturation that build above.
* Step5: Estimate cost barriers. It recommends that identify 2 similar quality requirements from other projects as input, for one is mainly related to software changes and the other is related to hardware components.
* Step6: Set candidate requirements. We can specify two targets like Good or Stretch target to specify the interval of a actual QR.
* Step7: Identify cost dependencies :If more than two QR affect, they always dependent. Or we can use existing dependency tools to identify dependencies.
After introducing QUPER, the author tells us about his case study evaluation of QUPER.Two methodology used by the author are interviews and questionnaires. He finds that it is important to concrest guidelines combined with instructive examples from real practice.Future work includes industry assessments in different areas. The long-term impact of using QUPER needs to be investigated in order to adequately validate its feasibility and scalability.
In addition, in order to replicate this empirical study in the same field, the usefulness and applicability of the QUPER model in different companies is an interesting future work. In addition, the transferability of guidelines and examples used to support methodological adoption and the use of analog-based estimates are interesting questions for further study.

For this paper, i agree with that there is a great need for a supporting model for helping with QR in industry. So the following i mentioned that LSRE is widespread.
Then i think eliciting quality breakpoints is very important. As i find that QUPER-benefit view, there are utility breakpoint, differentiation breakpoint and saturation breakpoint. Both too low or too high quality is bad for the product, so we have to balance it and find breakpoints to help us make it well.



-------


#### Article"Introducing support for release planning of quality requirements –an industrial evaluation of the QUPER model"

The author introduce that the QUPER model was developed by three main steps: Problem Definition, Model Definition and Model validation. Meanwhile this model aims at supporting prioritization and roadmapping of QR at early ages of release planning.
The author planned the following steps of using the QUPER at Sony Session: 1.Define quality aspects 2. Estimate the current quality of our product and make a competition. 3. Estimate the breakpoint for each quality aspects and relevant qualifier.
In this paper, the author presents an industrial evaluation of QUPER model at Sony Ericsson through an interview-workshop-interview step. 
He found that QUPER is easy to understand and learn, straightforward and not complicated for the current practice of Sony Ericsson. In fact, all subjects indicate that they are and will use QUPER. In addition, the concept behind QUPER improves communication among employees about the need for prioritization. The main challenge is that it is difficult to identify and specify the values of the split and saturation breakpoints. In addition, a different understanding of the value of staff break-points was presented as a challenge.

I am quite for the figure 1. and figure 2. The relationship between Quailty level and Benefit or Cost is non-linear influence relationship. The line rises unevenly. So breakpoints are defined by user experience and makert value.
The author want to evaluate the QUPER model in industrial area, the method he used is quite nice and the aim is to evaluate QUPER-benefit view. When we develop the level of QUPER, the benefit is increase apparently. 
The one interview before the workshop, and the other after the workshop. This is kind of good, for the staff can experience the process of QUPER in real project. Their feedback can be valuable.


-------



#### Article "A Market-Driven Requirements Engineering Process: Results from an Industrial Process Improvement Programme"
In this paper, the author describes a specific RE process called REPEAT (Requirements Engineering ProeSS At Teleogic). It is a process that manage the requirements through a whole release cycle.
First, the role involved in REPEAT can be various:Requirements Management Group, Issuer,Customers & users,Requirements team, Construction team,Test team, Expert and Requirements Database.
Meanwhile each unique requirement has a life cycle through specific states: New,Assigned,Classified, Selected (this 4 states can be Rejected)and Applied.
REPEAT includes several phases:

* 1.Elicitation Phase includes collection(made by an issuer in the web form and upload for storing in RQDB) and classification(through RQMG by assigning it to an expert).

* 2.Selection Phase the aim of the phase is to 1.select requirements to execute in the current release. 2. make the selected requirements more detail 3.Validate the document of requirement  This phase will output the RD includes a selected list, a detailed specification an a non- selected list.

* 3.The 3rd phase include Change management, Construction(using an iterative design and implementation process), Verification(using requirements-based testing method) and Conclusion(collect metrics and write a final report)

* 4.There are some Process Enactment Scenarios of REPEAT
* In the end ,the author point out some challenges which can be fixed and improved in the future: overload control, connecting fragments, Long-term product strategy and so on.

I quite agree with the Fig 1."The states of a requirement in the REPEAT process" shown. Build a good requirement is a strict and long process, every step is important, once some risk or problem come up with, we can reject the requirement.
The challenge that the author mentioned are worth considering.  For Overload control: there will be a lot of information through the website interface everyday. A mechanism that building sustainable requirements architecture can help solve this risk.


-------



### Reference 
[1] Visualizing, Analyzing and Managing the Scope of Software Releases in Large-Scale Requirements Engineering

[2] Wiegers K, Beatty J. Software requirements[M]. Pearson Education, 2013.

[3] Robertson S, Robertson J. Mastering the requirements process: Getting requirements right[M]. Addison-wesley, 2012.

[4] Kotonya G, Sommerville I. Requirements engineering: processes and techniques[M]. Wiley Publishing, 1998.

[5] Lauesen S. Software requirements: styles and techniques[M]. Pearson Education, 2002.

[6]Leffingwell D. Agile software requirements: lean requirements practices for teams, programs, and the enterprise[M]. Addison-Wesley
Professional, 2010.

[7]Wohlin C. Engineering and managing software requirements[M]. Springer Science & Business Media, 2005.

[8]Feature interaction and dependencies: Modeling features for reengineering a legacy product line

[9]Svahnberg M, Gorschek T, Feldt R, et al. A systematic review on strategic release planning models[J]. Information and software technology, 2010, 52(3): 237-248.



