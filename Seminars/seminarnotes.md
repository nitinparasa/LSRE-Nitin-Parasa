Seminar 1:

Questions:

1.	What is Large Scale Requirements Engineering?
2.	What are the challenges in large scale requirements engineering?
3.	What is the order of magnitude on the number of requirements we are discussing?
4.	Read and summarise Release Planning?

List Of References:

1. Konrad, S.; Gall, M., "Requirements Engineering in the Development of Large-Scale Systems," in International Requirements Engineering, 2008. RE '08. 16th IEEE , vol., no., pp.217-222, 8-12 Sept. 2008
2. B. Regnell, R. B. Svensson, and K. Wnuk, “Can we beat the complexity of very large-scale requirements engineering?,” Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics), vol. 5025 LNCS, pp. 123–128, 2008.

Answers:

1. Requirements Engineering for the development of complex software systems for large scale industrial project is Large Scale Requirements Engineering.

2. Challenges faced in large scale requirements engineering according to [1] are:
    1. Large number of customer requirements: Analyzing, Specifying,and managing the requirements at a large scale is burdensome and challenging to the organizations.
    2. Formal interface to customer: Communication with the customer is often formal and the number of meetings is very less with them being a huge number in the large scale projects. 
    3. Management of customer expectations: The expectaitons of the customer have to be satisified by the organization by showing a prototype of the model being developed. This over a large scale has to be propoerly managed.
    4. Changing Technology: A project ususally spans for several years. During this time technology changes and this has to be taken into account and addressed.
    5. Distributed teams: Many projcts today are globally distributed. Various teams from different geograpical locations work to finish the project. Handling and coordinating these teams can prove challenging.
    6. Traceability: Tracing out the requirements is a difficult task in this context as it requires large amount of time and human effort.
    7. Resource fluctuation: Team members join and leave the project during the development of the project. Knowledge transfer for the team members like information regarding the deadlines, deliverables, etc is a challenge.

3. The order of magnitude on the number of requirements addressed in a particular project with repsect to Large scale requirements engineering is of the order of 1000 as stated by B. Regnell et al. in their article [2].

Summaries:

Paper 1: 

- This paper mainly focuses on describing the art and science of Release Planning. The author states that the 'art of release planning' is related with the human intuitions and the negotiation and marketing skills they apply for conflicting demands. The science of release planning is a practical approach of dealing by the application of algorithms and formalizing a problem. Release planning is an important phase of any type of product development. Organizations often deal with various difficulties during the release planning, the prime one being the complexity of the problem being dealt. Release planning is often done adhoc, there are no methodologies to carry out this process. 
- According to the Capability Maturity Model Integration (CMMI) project planning is a very important step to establish and plan various management activities to execute a project. The author in this article elaborates the science of release plannng with the help of an example. Plannig has to be done to release a product within two releases. Several attributes have been discussed, which are as follows:
    1. Decision Variables: List of features planned for this release.
    2. Dependencies between features: The dependencies between features can be of two types. One is Coupling Relation which         intends that both the dependent features must be a part of the same release. Other is Precedence relation.
    3. Resource Constraints: Feasibility of the resources. What is the amout of resources required to develop the features.
    4. Stakeholders
    5. Prioritizing the features

- Then the objective function is derived which helps determine good release plans. The author proposed a hybrid release planning framework. It is a 3 phased framework starting with the modeling the details of the problem. Planning objectives, Resource Allocation and Stakeholder voting are all a part of modeling. Then exploration is done where an actual solution to modeled problem is derived. Finally there is Consolidation where the solutions are analyzed and modifications are performed (Scenario-playing and Re-Estimation).

Paper 2: 

- One of most prominent factor for product is to make sure it meets the quality requirements, one such model for planning the quality releases is QUPER. The most challenging issues that could be raised for the organisations which develop such kind products are high market competitors and future demands from the customers. This paper discusses the working of QUPER a model developed to support high-level decision making in release planning of quality requirements. The main objective of release planning as mentioned is to maximize the benefits where 'benefit' has no explicit definiton. The author portrayed a few studies that stresses on strategic releae planning of quality requirements. One of them by Svahnberg et al. portray two methods addressing quality requirements 1. Quantitative Win-Win model 2. QUPER model stressing on quality and cost constraints. The author exemplifies the QUPER model and presents a full description of the application of this model in a company and various lessons learned. 
- Related work by Svahnberg et al. identified 24 different strategic release planning techniques where 14 are original and the other 10 being derived from them. The author states that two main factors motivated for the evolution of QUPER model: 1. A direct need of the industry 2. Lack of a suitable model to fulfil this criteria.  
- Qualitative research was used to evaluate the QUPER model and finding enlisted. Several practitioners believe that QUPER is very easy to understand and does not require much time to apply in industrial environment. The guidelines provide all the necessary information to apply for industrial practices. Few practitioners also agree that all steps are not mandatory to be performed. Some feel that model should not be too complicated and should be a “light model”. From the interviews that have been conducted during the empirical research new approaches for finding the breakpoints were discovered like his/her own experience of estimates, comparison with competitors, access the database and market analysis. From the research few also felt the importance of workshops to educate about the QUPER model. It is also important to understand that QUPER cannot be applied for all the quality requirements and QUPER should be used from the very beginning to the end of the project. In general the paper talks about QUPER, the steps involved in QUPER and also the evaluation of the model for industrial practice.

Paper 3:

- Market driven product development and release planning have become most necessary part of the software industry. Due to increase in market driven development the role of product manager and project management have become very crucial. Release planning guarantees overall success of the project. To support release planning and mapping of the quality requirements a quality performance model has been developed. This particular article investigates on the implementation of QUPER (Quality Performance) in large scale software industries. The QUPER model was developed in 3 steps: 1. Problem definition 2. Model definition 3.Model validation. This model supports prioritisation and road mapping of the quality requirements. From this model quality was identified as a continuous and non-linear attribute. Few goals were selected for the development of the QUPER model: robustness to uncertainties, ease of use, domain relevance.
- The QUPER domain view has three different break points utility breakpoint, differentiation breakpoint and saturation breakpoint. The QUPER cost view represents the non- linear relationship between cost and quality. QUPER roadmap view visualises the benefit breakpoints and cost benefits in relation with the quality and supports the release planning of the product. This presents the generic nature of QUPER. The evaluation of the QUPER, the following are few steps that are used for QUPER benefit view 1.Define quality aspects 2.Estimation of the current quality 3.Estimate the breakpoints and 4.Decide on actual targets of the upcoming releases.
Research was carried out to find about the QUPER relevance in industrial setting, adaption of QUPER and value of QUPER. Finally few results were concluded from the research by the means of continuous interviews and workshops. The research concludes that QUPER provides a very structured to handle the performance requirements and also justifies the reason for selecting the particular quality requirements. 
- QUPER model identifies the richer picture and provides a good understanding of the performance requirements. It is also stated from the research that the estimates were more accurate by using the QUPER model. The overall results conclude that QUPER is used in high level decision making during the release planning. The different breakpoints and market analysis has lead to the identification and reasoning for understanding the performance and quality requirements in a more appropriate way.
- The only challenges that were addressed during the evaluation of the QUPER model is identifying and understanding of the breakpoints. The evaluation also suggests the feasiblity and domain specific nature of QUPER. Further reasearch could be carried in evaluating the model using more subjects with different roles.

Paper 4:

- Requirement engineering practices differ from one product to another product. The practices may be different for the packaged products and bespoke products. The packaged software product is also known as commercial off the self-products (COTS) .The product is released with particular components with planed releases. One of the various industrial requirement processes for packaged products is known as REPEAT (Requirement Engineering ProcEss At Telelogic). This process used for eliciting, selecting and managing the requirements. In REPEAT different actors are involved, they are: Requirement management group, issuer, customers, user’s requirements team, construction team, test team, expert team and requirement database. Different steps are used to accept the particular requirement by the requirement management group and it undergoes the following states: new, assigned, rejected, classified, selected and applied. 
- The REPEAT process has different phases namely the elicitation phase and selection phase. In the elicitation phase two main activities are involved i.e. collection and classification. Requirements are collected from the users, they fill the forms and these requirements are stored in the requirements database. The estimates about the impact (I), cost(C) and priority (P) are decided. After the collection they are moved into the classified state. 
- During the selection phase the following steps are implemented: They are selected for the release they are specified with more details and validated. Change management occurs and high priority are taken. The requirements undergo change management, construction, verification and conclusion. 
- REPEAT is also enacted using different Message Sequencing Charts (SMC).Many challenges also have been identified for REPEAT enactment like overload control, connecting fragments, building the chasm between collection and selection, long term market analysis. 
Seminar 2:

Question 3: What is Technical Product Management?

Technical Product Management is the process of defining market requirements and packaging these features into various releases. This involves a close interaction with the development team, key customers, market analysts, etc.

Question 4: What is roadmapping? How can you do it large scale?

Roadmap is a list of the product releases that are determined to come over a time frame of three to five years. Especially for large scale or market driven requirements engineering where the costs and cosequences of a vendor change being large it is better to involve the customer in the roadmap decision-making. Roadmaps help organizations identify important objectives and highlights the resources required to achieve those objectives. Roadmapping has many uses both for the corporate and industry level organizations. They are:

1. Development of a consesnsus about a set of needs and the resources required to fulfil those needs.
2. Provision of a mechanism that helps in forecasting the technology devlopments in the target areas in the years to come.
3. A framework to plan and coordinate the devlopmental activities in an organization.

In large scale context the process of Roadmapping can typically take place in four phases.
1. Initiation Phase: This phase involves activities like forming the roadmap team. Determining the strategy and the pre-conditions and finally setting the context.
2. Preparation phase: This phase involves activities like prioritizing the teams, selecting them and then determining a time schedule. Then a roadmap is created.
3. Finalization phase: In this pahse the developed roadmap is validated. Then communication takes place both internally and externally i.e within the organization and with the customer.
4. Follow-Up phase: Here the roadmap is periodically reviewed and updates are made.
