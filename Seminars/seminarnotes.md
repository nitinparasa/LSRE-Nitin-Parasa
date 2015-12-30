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

[1]Weerd & Brinkkemper “Towards a reference framework for software product management”
[2] Regnell & Brinkkemper “Market-Driven Requirements Engineering for Software Products” (Chapter 13 in Engineering and Management
of Software Requirements)

Question 2: What tools are available for continuous integration?

There are three popularly used tools for Continuous Integaration. They are Apache's Continuum, Hudson and Cruise Control (CC). All the tools are open source and the users can build software and test them as configured. Hudson and Continuum support only Java based softwares but Cruise Control supports both Java and .Net based softwares.

Question 3: What is Technical Product Management?

According to [1]:
Technical Product Management is the process of defining market requirements and packaging these features into various releases. This involves a close interaction with the development team, key customers, market analysts, etc.

Question 4: What is roadmapping? How can you do it large scale?

Roadmap is a list of the product releases that are determined to come over a time frame of three to five years. Especially for large scale or market driven requirements engineering where the costs and cosequences of a vendor change being large it is better to involve the customer in the roadmap decision-making[2]. Roadmaps help organizations identify important objectives and highlights the resources required to achieve those objectives. Roadmapping has many uses both for the corporate and industry level organizations. They are:

1. Development of a consesnsus about a set of needs and the resources required to fulfil those needs.
2. Provision of a mechanism that helps in forecasting the technology devlopments in the target areas in the years to come.
3. A framework to plan and coordinate the devlopmental activities in an organization.

In large scale context the process of Roadmapping can typically take place in four phases.
1. Initiation Phase: This phase involves activities like forming the roadmap team. Determining the strategy and the pre-conditions and finally setting the context.
2. Preparation phase: This phase involves activities like prioritizing the teams, selecting them and then determining a time schedule. Then a roadmap is created.
3. Finalization phase: In this pahse the developed roadmap is validated. Then communication takes place both internally and externally i.e within the organization and with the customer.
4. Follow-Up phase: Here the roadmap is periodically reviewed and updates are made.

Summaries:

Paper 1: This article stresses on mitigating the challenges related to making different requirements comparable in the development organizations. The authors propose a model named as Requirements Abstraction Model (RAM) with four abstraction levels as a response to the industrial needs. Requirements can be placed on different levels supporting abstraction and breakdown of requirements. The idea the author focussed on is to select about what a typical relsease should contain (requirements), when it shoudl be relsead and most importantly at what cost. Cost here is the various resources needed in designing and implementing the requirements specified for that particular release. 

The authors main motive in introducing RAM was to give the professionals working with the product development or planning a requirements egineering model that help them in making work a lot easier. RAM is a product-perspective continuous requirements engineering effort which breaks down abstract requirements into detailed ones eventually for the work up of the reuirements gahtered for a project. Few benefits of using RAM are also stated by the author like determining the correct scope of the project and lining the requirements within that scope, getting goo-enough requirements, formulating the requirements at the same level of abstraction and evetually givigna  richer understanding of the requirements. Different documents that are used in the industry in the same line as of RAM like the Market Requirements Specification -MRS which is further refined into Product Requirements Specification and the Technical Requirements Specifications are detailed in this article.

Inorder to validate the model prsented in this article a software process assessment activity has been performed at DanaherMotion Saro AB in Gothenberg, Sweden. The results of the process assessment of the model resulted in the identification of nine different issues which are further prioritized and packaged. The issues are described below:

1. Abstraction Level and Contents of Requirements: Need for looking over and establishing how the requirements are specified regarding abstraction level and level of detail.
2. State of the Art in relation to issue 1.
3. Roles and Responsibilities: Responsibilities needed to support the process have to be assigned with them being unamigous and clearly described.  
4. State of the Art in relation to issue 3.
5. Requirements Upkeep During and Post Project: Keeping the requirements active as long as they are in the scope of the project or the release to be specific. Keeping them updated is a crucial activity.

Along with the industry need motivating the author for the creation of RAM another factor influenced the creation of RAM which is that there isn't any model found in the literature that focussed on continuous requirements engineering catching and handling on multiple abstraction level. RAM has eveolved over several stages but the author described about two major stages that RAM went through. They are Validation One and Two also called the Static Validation and the Dynamic Validation respectively. The static validation steps involved the brainstorming sessions with the project manager, discussions with the representatives for development, system test and upper management while the dynamic validation consisted of using RAM for a real live requirements engineering effort. 

Companies using this model have the requirements phase carried out in three basic phases. The first step being (Specify) eliciting enough information for the raw requirements. Second step is to (Place) finding out the correct abstraction level a requirement has to reside on and the final step is (Abstraction) where each requirements goes through a work-up. The author has given a detailed description of these three phases. Of these three phases, Placing the requirements in one of these levels proves to be the most important. This step involves analyzing what level a requirements is on and placing it on this level. Four levels have been identified and they are Product Level, Feature Level, Function Level and Component Level. 

The Product Level is the most abstract level and have requirements in the form of goals to be achieved which don't fit the normal definition of a requirement. These can be measured directly with the prodcut strategies and fine-tuning them is compulsory. The next level is the Feature Level where the requirements here are the features which are a part of the system. This model specifies that the requirements must just give an abstarct description of the feature. Then there is the Function Level which itself suggest that it is a repository of functional requirements. In general requirements in this level are detailed enough to be handed over to the designer. Finally there is Component Level where the requirements are detailed enough to convey information about how to do something inoerder to solve it. 

The author says that requirements as a part of RAM model can exist in either of these possible states: Draft Requirement, Rejected Requirement, Incompletely specified, Refined Requirement. Then the author details about the validations performed about how this model works and also describes the lessons learned as a part of that action. They conclude saying that RAM breaks down the requirements as needed eventually creating requirements on several levels of abstractions as per the organizations needs.
