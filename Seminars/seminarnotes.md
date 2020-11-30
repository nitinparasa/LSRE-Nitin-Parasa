# Seminar 0:

### Questions:

1.	What is Large Scale Requirements Engineering?
2.	What are the challenges in large scale requirements engineering?
3.	What is the order of magnitude on the number of requirements we are discussing?
4.	Read and summarise Release Planning?

### List Of References:

[1] Konrad, S.; Gall, M., "Requirements Engineering in the Development of Large-Scale Systems," in International Requirements Engineering, 2008. RE '08. 16th IEEE , vol., no., pp.217-222, 8-12 Sept. 2008
[2] B. Regnell, R. B. Svensson, and K. Wnuk, “Can we beat the complexity of very large-scale requirements engineering?,” Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics), vol. 5025 LNCS, pp. 123–128, 2008.

### Answers:

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

## Summaries:

**Paper 1:**  

[3] Ruhe, Günther, and Moshood Omolade Saliu. "The art and science of software release planning." Software, IEEE 22.6 (2005): 47-53.

- This paper mainly focuses on describing the art and science of Release Planning. The author states that the 'art of release planning' is related with the human intuitions and the negotiation and marketing skills they apply for conflicting demands. The science of release planning is a practical approach of dealing by the application of algorithms and formalizing a problem. Release planning is an important phase of any type of product development. Organizations often deal with various difficulties during the release planning, the prime one being the complexity of the problem being dealt. Release planning is often done adhoc, there are no methodologies to carry out this process. 
- According to the Capability Maturity Model Integration (CMMI) project planning is a very important step to establish and plan various management activities to execute a project. The author in this article elaborates the science of release plannng with the help of an example. Plannig has to be done to release a product within two releases. Several attributes have been discussed, which are as follows:
    1. Decision Variables: List of features planned for this release.
    2. Dependencies between features: The dependencies between features can be of two types. One is Coupling Relation which         intends that both the dependent features must be a part of the same release. Other is Precedence relation.
    3. Resource Constraints: Feasibility of the resources. What is the amout of resources required to develop the features.
    4. Stakeholders
    5. Prioritizing the features

- Then the objective function is derived which helps determine good release plans. The author proposed a hybrid release planning framework. It is a 3 phased framework starting with the modeling the details of the problem. Planning objectives, Resource Allocation and Stakeholder voting are all a part of modeling. Then exploration is done where an actual solution to modeled problem is derived. Finally there is Consolidation where the solutions are analyzed and modifications are performed (Scenario-playing and Re-Estimation).

**Paper 2:** 

[4] Svensson, Richard Berntsson, and Björn Regnell. "A Case Study Evaluation of the Guideline-Supported QUPER Model for Elicitation of Quality Requirements." Requirements Engineering: Foundation for Software Quality. Springer International Publishing, 2015. 230-246.

- One of most prominent factor for product is to make sure it meets the quality requirements, one such model for planning the quality releases is QUPER. The most challenging issues that could be raised for the organisations which develop such kind products are high market competitors and future demands from the customers. This paper discusses the working of QUPER a model developed to support high-level decision making in release planning of quality requirements. The main objective of release planning as mentioned is to maximize the benefits where 'benefit' has no explicit definiton. The author portrayed a few studies that stresses on strategic releae planning of quality requirements. One of them by Svahnberg et al. portray two methods addressing quality requirements 1. Quantitative Win-Win model 2. QUPER model stressing on quality and cost constraints. The author exemplifies the QUPER model and presents a full description of the application of this model in a company and various lessons learned. 
- Related work by Svahnberg et al. identified 24 different strategic release planning techniques where 14 are original and the other 10 being derived from them. The author states that two main factors motivated for the evolution of QUPER model: 1. A direct need of the industry 2. Lack of a suitable model to fulfil this criteria.  
- Qualitative research was used to evaluate the QUPER model and finding enlisted. Several practitioners believe that QUPER is very easy to understand and does not require much time to apply in industrial environment. The guidelines provide all the necessary information to apply for industrial practices. Few practitioners also agree that all steps are not mandatory to be performed. Some feel that model should not be too complicated and should be a “light model”. From the interviews that have been conducted during the empirical research new approaches for finding the breakpoints were discovered like his/her own experience of estimates, comparison with competitors, access the database and market analysis. From the research few also felt the importance of workshops to educate about the QUPER model. It is also important to understand that QUPER cannot be applied for all the quality requirements and QUPER should be used from the very beginning to the end of the project. In general the paper talks about QUPER, the steps involved in QUPER and also the evaluation of the model for industrial practice.

**Paper 3:**

[5] Svensson, Richard Berntsson, Thomas Olsson, and Björn Regnell. "Introducing support for release planning of quality requirements—an industrial evaluation of the QUPER model." Software Product Management, 2008. IWSPM'08. Second International Workshop on. IEEE, 2008.

- Market driven product development and release planning have become most necessary part of the software industry. Due to increase in market driven development the role of product manager and project management have become very crucial. Release planning guarantees overall success of the project. To support release planning and mapping of the quality requirements a quality performance model has been developed. This particular article investigates on the implementation of QUPER (Quality Performance) in large scale software industries. The QUPER model was developed in 3 steps: 1. Problem definition 2. Model definition 3.Model validation. This model supports prioritisation and road mapping of the quality requirements. From this model quality was identified as a continuous and non-linear attribute. Few goals were selected for the development of the QUPER model: robustness to uncertainties, ease of use, domain relevance.
- The QUPER domain view has three different break points utility breakpoint, differentiation breakpoint and saturation breakpoint. The QUPER cost view represents the non- linear relationship between cost and quality. QUPER roadmap view visualises the benefit breakpoints and cost benefits in relation with the quality and supports the release planning of the product. This presents the generic nature of QUPER. The evaluation of the QUPER, the following are few steps that are used for QUPER benefit view 1.Define quality aspects 2.Estimation of the current quality 3.Estimate the breakpoints and 4.Decide on actual targets of the upcoming releases.
Research was carried out to find about the QUPER relevance in industrial setting, adaption of QUPER and value of QUPER. Finally few results were concluded from the research by the means of continuous interviews and workshops. The research concludes that QUPER provides a very structured to handle the performance requirements and also justifies the reason for selecting the particular quality requirements. 
- QUPER model identifies the richer picture and provides a good understanding of the performance requirements. It is also stated from the research that the estimates were more accurate by using the QUPER model. The overall results conclude that QUPER is used in high level decision making during the release planning. The different breakpoints and market analysis has lead to the identification and reasoning for understanding the performance and quality requirements in a more appropriate way.
- The only challenges that were addressed during the evaluation of the QUPER model is identifying and understanding of the breakpoints. The evaluation also suggests the feasiblity and domain specific nature of QUPER. Further reasearch could be carried in evaluating the model using more subjects with different roles.

**Paper 4:**

[6] Regnell, Björn, Per Beremark, and Ola Eklundh. "A market-driven requirements engineering process: results from an industrial process improvement programme." Requirements engineering 3.2 (1998): 121-129.

- Requirement engineering practices differ from one product to another product. The practices may be different for the packaged products and bespoke products. The packaged software product is also known as commercial off the self-products (COTS) .The product is released with particular components with planed releases. One of the various industrial requirement processes for packaged products is known as REPEAT (Requirement Engineering ProcEss At Telelogic). This process used for eliciting, selecting and managing the requirements. In REPEAT different actors are involved, they are: Requirement management group, issuer, customers, user’s requirements team, construction team, test team, expert team and requirement database. Different steps are used to accept the particular requirement by the requirement management group and it undergoes the following states: new, assigned, rejected, classified, selected and applied. 
- The REPEAT process has different phases namely the elicitation phase and selection phase. In the elicitation phase two main activities are involved i.e. collection and classification. Requirements are collected from the users, they fill the forms and these requirements are stored in the requirements database. The estimates about the impact (I), cost(C) and priority (P) are decided. After the collection they are moved into the classified state. 
- During the selection phase the following steps are implemented: They are selected for the release they are specified with more details and validated. Change management occurs and high priority are taken. The requirements undergo change management, construction, verification and conclusion. 
- REPEAT is also enacted using different Message Sequencing Charts (SMC).Many challenges also have been identified for REPEAT enactment like overload control, connecting fragments, building the chasm between collection and selection, long term market analysis. 

# Seminar 1:

[1]Weerd & Brinkkemper “Towards a reference framework for software product management”
[2] Regnell & Brinkkemper “Market-Driven Requirements Engineering for Software Products” (Chapter 13 in Engineering and Management
of Software Requirements)

Question 1: GAP/CVA/IVA Analysis?

According to [5] GAP analysis is a measurement echnique which can find out the positive or negative gaps that exist between what the product offers and what the customer actually wants. There can be different ways to understand this concept, when the product offers more than what the customer wants then there is said to be a positive gap and vice-versa. Customer Value Analysis is similar to GAP analysis can be used ot measure the quality post-release an these results can be used to enhance the next round of requirements.

Unlike the above mentioned techniques Internal Value Analysis is manily used for checking if the product is in line with the strategies of the company taking various criteria into account.

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

### Summaries:

**Paper 1:** 

[3] Gorschek, Tony, and Claes Wohlin. "Requirements abstraction model." Requirements Engineering 11.1 (2006): 79-101.

This article stresses on mitigating the challenges related to making different requirements comparable in the development organizations. The authors propose a model named as Requirements Abstraction Model (RAM) with four abstraction levels as a response to the industrial needs. Requirements can be placed on different levels supporting abstraction and breakdown of requirements. The idea the author focussed on is to select about what a typical release should contain (requirements), when it should be released and most importantly at what cost. Cost here is the various resources needed in designing and implementing the requirements specified for that particular release. 

The authors main motive in introducing RAM was to give the professionals working with the product development or planning a requirements engineering model that help them in making work a lot easier. RAM is a product-perspective continuous requirements engineering effort which breaks down abstract requirements into detailed ones eventually for the work up of the requirements gathered for a project. Few benefits of using RAM are also stated by the author like determining the correct scope of the project and lining the requirements within that scope, getting good-enough requirements, formulating the requirements at the same level of abstraction and eventually giving a richer understanding of the requirements. Different documents that are used in the industry in the same line as of RAM like the Market Requirements Specification -MRS which is further refined into Product Requirements Specification and the Technical Requirements Specifications are detailed in this article.

Inorder to validate the model presented in this article a software process assessment activity has been performed at DanaherMotion Saro AB in Gothenberg, Sweden. The results of the process assessment of the model resulted in the identification of nine different issues which are further prioritized and packaged. The issues are described below:

1. Abstraction Level and Contents of Requirements: Need for looking over and establishing how the requirements are specified regarding abstraction level and level of detail.
2. State of the Art in relation to issue 1.
3. Roles and Responsibilities: Responsibilities needed to support the process have to be assigned with them being unambigous and clearly described.  
4. State of the Art in relation to issue 3.
5. Requirements Upkeep During and Post Project: Keeping the requirements active as long as they are in the scope of the project or the release to be specific. Keeping them updated is a crucial activity.

Along with the industry need motivating the author for the creation of RAM another factor influenced the creation of RAM which is that there isn't any model found in the literature that focussed on continuous requirements engineering catching and handling on multiple abstraction level. RAM has evolved over several stages but the author described about two major stages that RAM went through. They are Validation One and Two also called the Static Validation and the Dynamic Validation respectively. The static validation steps involved the brainstorming sessions with the project manager, discussions with the representatives for development, system test and upper management while the dynamic validation consisted of using RAM for a real live requirements engineering effort. 

Companies using this model have the requirements phase carried out in three basic phases. The first step being (Specify) eliciting enough information for the raw requirements. Second step is to (Place) finding out the correct abstraction level a requirement has to reside on and the final step is (Abstraction) where each requirements goes through a work-up. The author has given a detailed description of these three phases. Of these three phases, Placing the requirements in one of these levels proves to be the most important. This step involves analyzing what level a requirements is on and placing it on this level. Four levels have been identified and they are Product Level, Feature Level, Function Level and Component Level. 

The Product Level is the most abstract level and have requirements in the form of goals to be achieved which don't fit the normal definition of a requirement. These can be measured directly with the product strategies and fine-tuning them is compulsory. The next level is the Feature Level where the requirements here are the features which are a part of the system. This model specifies that the requirements must just give an abstract description of the feature. Then there is the Function Level which itself suggest that it is a repository of functional requirements. In general requirements in this level are detailed enough to be handed over to the designer. Finally there is Component Level where the requirements are detailed enough to convey information about how to do something inorder to solve it. 

The author says that requirements as a part of RAM model can exist in either of these possible states: Draft Requirement, Rejected Requirement, Incompletely specified, Refined Requirement. Then the author details about the validations performed about how this model works and also describes the lessons learned as a part of that action. They conclude saying that RAM breaks down the requirements as needed eventually creating requirements on several levels of abstractions as per the organizations needs.

**Paper 2:**

[4] Khurum, Mahvish, Khurum Aslam, and Tony Gorschek. "A method for early requirements triage and selection utilizing product strategies." Software Engineering Conference, 2007. APSEC 2007. 14th Asia-Pacific. IEEE, 2007.

This paper presents MERTS (A Method for Early Requirements Triage and Selection) developed using established techniques for formulating product strategies along with combination of good practices. The authors of this article highlight the grouping of the requirements that companies come across in Market Driven Requirements Engineering (MDRE). They say that requirements in MDRE come from both internal and external sources like the developers, designers and different groups like the customer groups, user groups respectively. They stress that handling these large number of requirements in MDRE perspective is highly important and hence a requirements triage and selecting the ones aligned with a specific strategy. Usually in projects involving the strategic and technical manager’s decisions some key aspects are overlooked. This formed the base of this paper where the strategic and technical perspectives are combined to formulate reasonable product strategies that are good-enough for early requirements triage. The method described has two main purposes as mentioned by the authors. First one being that this acts as a step-wise guide to creating product strategies taking both perspectives into account. The other being that strategies developed using this method could be used by the product managers to perform requirements triage with a motive of selecting the right requirements for the release. 

In order to formulate the product strategies the authors performed a background research where they found out that a number of questions have to be answered. Those key questions are: 

1. Where do we want to go? It requires finding out the right balance between the long term goals and the short term objectives. Goals can be profit, growth and market share. 
2. How will we get there? This formulates the core of the strategy. Aspects such as the customer targets competitive targets are considered. It eventually depends on the officials as of which aspect they give the main priority to.
3. What to do? Specific programs or tactics to be used to achieve the mentioned goals and objectives are highlighted here. This deals with the pricing, publicity, etc.
4. Why will we be successful? This is the most important question which has to be clearly answered to produce a competitive strategy.
5. When will we get there? Roadmaps are a good way to represent targets based on time and release of the product.

The authors to know if and how the requirements triage is performed in the industry conducted a case study in two different companies. Then a brief description on how MERTS works in given in this paper. The goal of MERTS is to offer a clear understanding of how to reach to a consensus and product strategy. An assumption has been made that the requirements are detailed enough using any abstraction model and the (Requirements Abstraction Model) RAM has been referred. MERTS is carried out in three parts. Part one is Early Requirements Triage where an initial product strategy is created. This further has three more steps: 

1. Specify: Here three questions are answered which are 1. Where we want to go? 2. How to get there? 3. What will be done? Through this we can get a good understanding of what the organizations needs are and how do we align our product strategy with that? 
2. Assign weights: Then weights are assigned to each of these questions where each question can weight to a maximum of 100 points. Hence the total weight of the three question sums to be 300. Different attributes in each of the questions can be assigned weights which internally add up to a total of 100. 
3. Compare Requirements: Finally after the requirements are assigned points normalization will be done by the tool to analyse the points assigned to each requirement. 

Then the next part is Requirements Selection for Release, where the requirements are selected according to the priority and a product-technology roadmap is specified. Finally the Strategy Rationale which is nothing but the answer to the question “why would be successful”. Here a simpler description for the reasons behind each answer is written. The authors then perform an industrial evaluation and are successful where one of the companies accepted to use this model for their next product. Future work on this model is not clearly mentioned as they think that it is limited in scope.

**Paper 3:**

[5] Gorschek, Tony, and Alan M. Davis. "Requirements engineering: In search of the dependent variables." Information and Software Technology 50.1 (2008): 67-75.

The author’s main concentration in this articles stands on how organizations can improve the process of performing Requirements Engineering in a project. Two bases have been found out on which this assessment can be made, these are:

1. Requirements Process where the organizations can measure the time or effort taken to carry out this process and compare it against a set of “best practices” noted so far.
2. The initial product which is the result of conducting the requirements engineering process. We could measure this in terms of quality of the requirements of the product.

It is stated that in the attempt of improving the requirements engineering process most organizations fail to give importance to the resulting product. It is done with either minimal or no concern for that. With an aim to bring in a change to this, “dependent variables” have been found and which can be used as a basis for quality assessment of the RE process. Different levels identified in this article are: 

1. Requirements Phase: Two main attributes in this level are commonly measured. They are Requirements Phase cost/ time and quality. Where the cost can be the effort required per each requirement and the total development duration. Similarly quality can be simply put as the quality level of the requirements specification document.
2. Project: This is often compared with the project success where different factors can be, whether the project is completed within time and budget and if all the requirements are met. The two attribute remain the same for this level as discussed above.	
3. Product: In this level product success is determine by comparing them against factors like the customers being satisfied with the end product and all their requirements being met. Different attributes for this level could be on how the requirements are being selected (prioritised and error free) and the degree of impact this has on the customer.
4. Company: A company’s success lies in how the products sale in the market. Its success could be measured deviously where the success from the previous levels could change the fate of the product even though the project is completed late and over budget.
5. Society: If a particular product proves to be harmful for the society and yet fetches its company huge sums of money that is considered to be a failure. Thus organizations must make sure that a typical product must be profitable to company and at the same time be useful for the society.

All of them are inter-connected with each other. The impact of one level affects the impact of the other level creating on the company. Later on in this article the author talks about various researches made by other researchers in each of these fields. Product strategies, GAP analysis, Requirements Abstraction Model, Boston Matrix have been briefly described.

**Paper 4:**

[6] Berntsson Svensson, R., et al. "Quality requirements in industrial practice-an extended interview study at eleven companies. Software Engineering." IEEE Transactions on, preprint1 (2011).

Richard Berntsson Svensson et al. in this article make a few contributions to the field of requirements engineering wherein companies can find a right balance between the functional requirements and the quality requirements in the projects. This article deals with the comparing the Quality requirements being handled in business to business and business to consumer type of markets, its impact and the perceptions and priorities of both the Project Manager and the Project Leader and finally selecting and managing these quality requirements in the developmental activities. Quality requirements (QR) like the performance and usability of a product are equally important with the functional requirements of a system. It is equally important to fulfil the QR along with the Functional Requirements (FR) for a product to be successful. Prior to this article the authors have published a short paper involving 10 interviews which focussed on elicitation, negotiation and handling of QR in industry. In this research both customer-specific and market-specific projects have been considered along with some known challenges found in prioritizing the requirements. Karlsson in another study identified a few challenges related to QR eventually saying that interdependencies related to QR is the main issue currently existing. The results shown in this paper answer different research questions stated in this article. They are: 

1. Important Quality Aspects: With this study the authors found out that Usability and the Performance requirements are the most important for the companies in the projects. They have arrived at this conclusion using the Wilcoxon rank sum test which gives the statistical p-values.
2. Interdependencies: Prior work has been done by various authors in this area, here the authors focussed on what interdependencies deemed the most important? Eventually they found out that REQUIRES is the most important interdependency as many people think that the functionality is the prime aspect and then comes the quality aspect. Another area they focused on is to what extent are these interdependencies being elicited, analysed and documented. According to the results presented in this study 7 companies out of the dealt 11 show low extent of interdependency management as they feel this is a complex task and requires huge effort. Fulfilling the customer’s requirements is the company’s prime goal and no reflection on the QR is made as such.
3. Cost Estimates: There is no distinction made between the QR and FR in relation to the cost estimation. Study reveals that estimating QR is quite challenging as it requires deeper analysis and restricting to the performance QR often leads to detrimental effects in the estimation.
4. Dismissal of Quality requirements: When it comes to the dismissal of the QR from a heap of requirements the authors noted that there existed a difference of opinion between both the Project Leader (PL) and the Project Manager (PM). Once the QR are dismissed form a release they are not reassessed or analysed again. QR are not always quantified but usability requirements are often difficult to quantify than the performance requirements. Moreover not all the QR are suitable for quantification.

**Paper 5:**

[7] Karlsson, Joachim, and Kevin Ryan. "A cost-value approach for prioritizing requirements." Software, IEEE 14.5 (1997): 67-74.

In the context of Large Scale Requirements Engineering deciding which requirements to implements still daunts the companies. Prioritizing these requirements has been a challenging tasks and not many methods to perform this action have been developed. In this article the authors made an attempt to develop a tool which helps in prioritizing the requirements. This tool described in this paper helps in ranking the candidate requirements in two dimensions: one according to the value of the customer and the other according to the cost of implementation. They name it as the cost-value approach for requirements prioritization. For a successful software product it is necessary that we maximize the quality along with decreasing the cost of implementation and reducing the time-to-delivery. Analytical Hierarchy Process (AHP) has been used in this study to investigate the requirements of the projects. The reason for using this process as stated by the authors is that through this process requirements could be compared pairwise according to the cost and value. This process involves more redundancy thus leading to little errors.

In this cost-value approach to prioritizing the requirements 5 steps are followed: 

1. A careful inspection on the requirements is done so that they are clearly understood and completeness is attained.
2. AHP process is used on these requirements to attain the relative value of the requirements.
3. Then the software engineers use the same approach to assess the cost-estimations for each candidate requirements.
4. Next the engineer calculates the implementation costs and the relative values of each candidate requirements and then place them in a cost-value graph. This graph according to the authors is differentiated into three sub plots namely High, Medium and Low. These are discussed later on in note.
5. Finally the stakeholders use this cost-value graph as an aid to visualize the requirements. Then they prioritize the requirements and eventually decide the ones to be implemented.

Two case studies have been briefly described by the authors in this article which have used this method for prioritizing their requirements. The three sections of the cost-value graph are nothing but the requirements with a high ratio of value-to-cost are placed in High region and similarly for the other two. One main thing the authors did not consider in this approach is the dependency that exists between the requirements. Usually there exists a lot of complex dependencies between these requirements and this has to be considered too in the creation of working of this tool.    

# Seminar 2: 

### Questions

**1. Boston Matrix?**

It is an informal marketing tool used by companies for the analysis and the management of products. This tool was developed by the Boston Consulting Group in 1970's. Both market share and market growth are considered to identify where the product is currently standing and the rightful actions that have to be taken to reach the required state. Market share could be the percentage of market the organization has acheived. The impact of market share an market growth in relation to a product affecting the business of the organization can be depicted in four categories. They are: 
	

1. Dogs: This is the phase of a product lyinh in low market growth and low market share problem. They eat up most of the money the organization spends on a product and shows no sings of development or fetch money to the company.
2. Cash Cows: The products lying in this region have high market share with low market growth. This explains that the organization maintianing these products need not have to spend much on enhacing this to the present market conditions but can extract all the revenue as a result of customers using it. Best thing the companies can do with such prodcts is that milk them as longs as they can and eventually it loses its legacy.  
3. Question Marks(problem children): These are the products that grow with the increasing demands of the market but generate very low cash because of the lack of market share. Using apt approaches the organizations could turn these products into either stars or cash cows. 
4. Stars: These are the product which form the ideal combination of high market share and simultaneously growing market.
	
According to study there are four strategies for using Boston Matrix. They are: 
	1. BUild market shares
	2. Hold or maintain the same level
	3. Try to reduce the investment and simultaneously increase cash flow and profit
	4. Stop investing to remove dogs and start investing in other units which are benefitial for the organization.

### Summaries:

**Paper 1:**

[1] Van de Weerd, Inge, et al. "Towards a reference framework for software product management." Requirements Engineering, 14th IEEE International Conference. IEEE, 2006.

This paper mainly deals with software product management (SPM), the key features of it and how each of these processes are carried out in the industry. The authors of this paper present a reference framework for software product management. To start off with product management few key roles are responsible for carrying out this process. The product manager is responsible for managing the requirements, defining releases and considers the opinions of several internal and external stakeholders. Software unlike other products does not prove to be costly for the organizations as the product developed once can be developed to any number of customers and the updates to these can be made by patches and new releases. Alongside with such benefits there are a few disadvantages like handling these requirements and tracking of changes can be very complex. There is a claim made that a need of integration of research efforts in the product management domain is very important.

The need of understanding the domain of the product management has led to the development of a new framework. In order to achieve this the authors carried out field interviews and discussions with the product managers. Literature reviews on both non-software and software products and finally the creation of a draft reference framework. Then a validation on this is performed by carrying out a case study.

The basic reference framework is based upon the basic objects of product management. They are: 

1. Artifact Hierarchy: Basic artifacts can be the requirements, products and releases. A hierarchical ordering of these generates a structure of process area. Product-Portfolio identifies the scope of the work of a product management. A distinct hierarchy of levels of levels identified in this article is a subdivision of SPM into four processes: 1. Portfolio management 2. Product road mapping 3. Release planning 4. Requirements Management. 
2. Stakeholder Interaction: product manager’s deal with requirements that originate from several internal and external stakeholders involved in the project. The authors here has tried to distinguish some of the key stakeholders of the project where a few can be the 1. The Company board 2. Research and Innovation 3. Development team 4. Sales and marketing so on and so forth. The naming of the stakeholders is too generic here but can differ between companies.

Next a brief description on the reference framework and its components is given. Portfolio management deals with the decision making on the product. In this framework this is right on the top with four main processes of life cycle management and market trend identification. Product road mapping is the scientific use of resources elements and structural dependencies for the future or a period of time. Requirements Gathering often starts with gathering the requirements and then translated to product requirements and then the duplicates are removed and finally the requirements are organized as per product and core asset. After all this is done then we group these set of requirements into different release which make up the process of release planning.

**Paper 2:**

[2] Regnell, Björn, and Sjaak Brinkkemper. "Market-driven requirements engineering for software products." Engineering and managing software requirements. Springer Berlin Heidelberg, 2005. 287-308.

This paper mainly focuses on the challenges that companies face in the Market Driven Requirements Engineering Context (MDRE). In MDRE different key features are roadmapping, release planning, requirements management, etc. An industrial example of a release planning process is elaborated in this article for a clear understanding for the reader. Every organization needs to answer three basic questions in order to be successful in developing products for open market. They are: 

1. How to design and manage an MDRE process?

2. How to design and manage a MDRE repository? and  

3. How to make efficient and profitable release planning?

Software product usually exist in number of variants. But there are two dimensions for the classification of software products. They are: 1. Degree of customization 2. Hardware and Software content. Furthermore the degree of customization is divided into three levels. Generic level product is used as-is with minimal configurations to be done by the end-user. A customized product is useful after it has been developed according to the needs of a specific customer. Finally a customer specific product is the one developed solely for one particular customer. In the same way even the software/hardware content is divided into three classes namely the pure hardware products which are fixed through the hardware architecture, embedded systems consisting of both hardware platform and embedded software and pure software products which is completely comprised of software independent of the hardware. In MDRE context key characteristics are that the requirements have to informally discussed while having a continuous flow of requirements throughout the lifecycle and the organization taking risks alongside the decisions in the key activities and eventually focussing on time-to-market and return-of-investment. Whether it is MDRE or a classical bespoke project the main goal is to deliver the product at the right time and it right condition to withstand the heavy competition. Success in MDRE can be determined by the sales, market share, reviews, etc.  

Challenges faced in MDRE: A number of challenges are identified with the results based on the interviews at different companies of varying size and maturity. The most noted challenges and a brief description about each is given: 

1. Balancing market pull and technology push: a good balance between technology-driven and needs-driven requirements is a delicate challenge and has to be dealt carefully.

2. Chasm between marketing and development: Communication between the group of workers has to be enhanced which further improves the quality of the software.

3. Organizational instability and market turbulence: Key persons leaving the organizations often deal with the risk lacking necessary documentation and structure.

4. Simple tools for basic needs: Simple tools are always favoured by most of the companies as this is easy to use and at times it is challenging to find complex data.

5. Requirements Dependencies: Release planning becomes more and more complex as the dependencies between the requirements keep of increasing. Efficient ways to handle these dependencies have to evolve.

6. Cost-Value estimation and release planning: Cost and value estimates have to be carefully estimated by the responsible team. Underestimation may lead to several issues like missing the deadlines, cost overruns, etc.

7. Overloaded Requirements management.

The key issue for a market-driven company is to continuously improve to overcome these challenges and stay ahead of the competitors. The MDRE process is a way of synchronizing the work of the project with the constantly evolving requirements and working with the releases. The key driving forces for communicating the goals in MDRE are product roadmapping and release plan of the product. Looking at the quality of process carried out the success of the product can be determined. There are usually two types of requirements, they are: 1. Alfa requirements and beta requirements. An alfa requirement has high inherent quality which usually exists for an ideal requirement.  A beta requirement are the ideal forms of requirements that should be rejected. The decision outcomes can be used to define the metrics to characterize a product and decision quality. If there is a correct selection ratio then the requirements are selected and rejected if not met.

In the context of market analysis and requirements management we come across the concepts of Road Map and Release Plan. A brief overview and the author’s understanding are given below. To withstand the heavy competition is evident that the companies must foresee the future and understand the user’s needs and prepare a plan accordingly. A typical roadmap is a document which outlines these details, to be specific it could contain details like the list of product releases for the next five years. Four types of roadmaps can be developed. They are: 

1. Science or Technology Roadmap 2. Industry Technology Roadmap 3. Corporate Roadmap 4. Product or Portfolio Management Roadmap

A release plan is a result of these roadmaps where a list of requirements are taken, then prioritized and it is made sure that there is a stable working product at the end of each release. 

**Paper 4:**

[3] Bjarnason, Elizabeth, Krzysztof Wnuk, and Björn Regnell. "Are you biting off more than you can chew? A case study on causes and effects of overscoping in large-scale software engineering." Information and Software Technology 54.10 (2012): 1107-1124.

Scope management is most crucial part of the market driven requirement engineering. Several research studies have proven that scope creeps in the very large project can affect the project success but no research has been focused on the issues and factors that are responsible for concept of over scoping. This particular article focuses on understanding the factors responsible for over scoping, what the results of over scoping are and how does agile requirement engineering concepts have an impact on over scoping. From the related work it’s evident that over scoping is considered as one of the major risk factor in the whole requirement engineering phase. Communication gaps and other non-technical concepts impact the scope of the project. A case study is conducted by formulating the hypotheses to find the answers to the research questions. From the interviews few causes were taken into consideration like continuous requirements inflow via multiple channels, no overview of software resource availability, unclear vision of overall goals. Effects of over scoping are communication gaps, quality issues, expectations of the customers are not met and delays. It has been identified that agile RE practices also impact the over scoping in many ways that been proven from the case study results.

From the study it is found that over scoping can affect the overall project development as the RE is considered to be one of the most crucial part of decision making. The study suggests various different factors of the over scoping and effect of the over scoping have been mentioned. This particular paper could be helpful for the organisations to understand the concept of over scoping and its effects and also plan the project scope especially for market driven requirement engineering.

Scoping in the market driven is a continuous process and exists throughout the project scope of the project has to be manged or else may lead to over scoping which may affect the whole project therefore well said “the project bites off more than it can chew”. Scoping definitely most challenging part requirement engineering and a project management risk in most of the software projects. Over scoping also leads to more over scoping and the project enters into the vicious cycle. The most predominant factor could be communication gaps which in turn causes more over scoping. The literature finally draws the attention of scoping as a major challenge in market driven fast moving requirement engineering.

**Paper 6:**

[4] Carlshamre, Pär, et al. "An industrial survey of requirements interdependencies in software product release planning." Requirements Engineering, 2001. Proceedings. Fifth IEEE International Symposium on. IEEE, 2001.

Incremental systems have gained more importance in the recent times. Prioritisation of the requirements plays a major role in the increment development. Less research is done in the area of requirement interdependencies. This research paper focuses on the visualisation of requirement interdependencies. Five different cases were considered to find out the requirement interdependencies like small size companies, medium size companies, a telecommunication system, a software research institute and medium size company. Few examples were taken to find out the interdependencies by using the relationship like OR, AND, TEMPORAL, CVALUE, ICOST.

At the beginning of the each and every interdependencies are explained. It was observed that no particular conflicting dependencies were found in all the cases. It concludes that the conflicting dependencies are eliminated. Dependencies play a major role in the release planning in the incremental development but they are not mentioned directly. This particular study has concluded that singular requirements have no relationship with any other requirements. Requirements having relation with other requirements are easily identified. Clusters of requirements are used in case of incremental development.

In this particular study singular requirements are calculated using a specified formula, the highly dependent requirements have been identified .It has been stated that if there are more than 20% dependent requirements may lead to potential problems for the incremental development. An interdependency could be measured by using the coupling which is similar to the coupling in the design phase. Coupling measures the strength between the entities and low coupling means high modularity. Different functions have been generated to calculate the requirements coupling and release coupling.

From the present paper draws the attention to most important aspect of release planning that is the interdependencies, it has specified the concept of requirement coupling and release coupling could be most important while considering the interdependencies during the release planning. It also evident that visualisation techniques as a powerful means for partitioning the requirements. For this very particular reason dependencies are most important to consider during the release planning.

# Seminar 3: 

### Summaries:

**Paper 1:**

[1] Wnuk, Krzysztof, Björn Regnell, and Lena Karlsson. "What happened to our features? Visualization and understanding of scope change dynamics in a large-scale industrial setting." Requirements Engineering Conference, 2009. RE'09. 17th IEEE International. IEEE, 2009.

The article [1] by Krzysztof Wnuk et al. presents an industrial case study in large scale context on a technique called the Feature Survival Chart visualizes the scope changes being implemented by the companies in a project for a particular release. With a huge database of requirements associated for a typical large scale project scoping refers to the selection of a subset of these requirements for a typical release. This is often considered as a crucial activity for achieving economic benefits. Another issue is that companies find it hard to visualize these bunch of requirements and prioritise the requirements for a release. Another drawback is that the present requirement management tools do not support to carry out this activity. Hence as a remedy the authors of this article present this technique of Feature Survival Chart (FSC). 

One of the companies being investigated in this study follows a stage-gate approach to software development. There are Milestones and Tollgates to control the progress of the project. They set up 4 milestones for the requirement analysis and design before the implementation starts. Two keywords are defined in this article namely Primary flow and Secondary flow where primary flow addresses the highest priority functionalities in the release and Secondary flow resembles the additional requirements flow in the release which the company handles. The FSC chart has been developed by the authors along with some industrial professionals like the project manager, requirements manager and the Key Performance Indicator manager. The criteria considered by the authors in analysing the projects is the length of the project, features considered in the scope of the project, possibility to visualize and analyse these requirements. 

A FSC chart depicts the scope changes over time where time is on X axis and the features in the project are shown on the Y axis. The whole lifecycle of each and every feature can be depicted using this chart. The author states that the features on the top of the graph that have been a part of the release right from the start to the end are named as the survivors. Then there are three different stages where the requirement is depicted as in scope of the release, de-scoped from the release and the primary and secondary flows. 
A set of Scope tracking mechanisms have been used in order to find the interesting criteria like the volatility of the scoping process from the FSC chart. A defined set of five scope tracking measurements are presented in this article. They are: 

1. Time-related scope tracking measurement: This is the positive or negative scoping of the features per time-stamp i.e. the features coming into the release or removed from a release respectively.
2. Feature-related scope tracking mechanisms: These measurements are mainly related to the factors associated with features of a product. Some of them are: 
2.1 Time to feature removal: This can be the time from which a feature has been included in the project till the time it has lasted in the scope of the release. Through this certain analysis can be made as of how the requirements selection is taking place. Sometimes you have few features that will be introduced very late in the release and would be de-scoped towards the end of the project. Such actions could be rectified through data mining and introspections.
2.2 Number of state changes per feature: This could be similar to the discussion made in time related measurements. In this technique we see the different states as discussed earlier a typical feature could exist in. How professional interpret the data from this is that the whole set of features going to minimal number of state changes throughout a release shows a stable decision making process.  

This tool proved to be of effective use to the practitioners involved in this study as they believe that the volatility of the scope is confirmed using this tool for analysing various aspects of the quantitative characterization of features. Few threats have also been mentioned like the generalization of the results as only few companies are considered which do not represent all the companies developing large scale products. 

**Paper 2:**

[2] Wnuk, Krzysztof, Tony Gorschek, and Showayb Zahda. "Obsolete software requirements." Information and Software Technology 55.6 (2013): 921-940.

Market Driven Requirements Engineering deals with requirements of very large number. There is rapid requirements change and it is very crucial for the software companies to handle this efficiently in order to stay in the competition. Obsolete requirements is well known in the software industry but not much research has been done to address at least the basic concepts in this phenomenon. Hence in this article the authors have made an empirical investigation with 219 respondents spread across the globe. 

Firstly we will discuss about what obsolete software requirements are and then go through how the authors carried out a survey aimed at gathering data from various industrial professionals on what this thing exactly is. Various graphs have been used to convey the collected data in an effective way. Then we'll go through the different kinds of threats the results are prone to as addressed by the author. 

In Market Driven Requirements Engineering (MDRE) incoming requirements come at a very fast pace and the rate of change is very high. Companies need to identify them as and simultaneously classify these as of which are obsolete or outdated. This process of rapidly identifying such requirements is a complex task. The background for this study comes from requirements management where the primary responsibility is to integrate the data created in the requirements elicitation into the overall project flow. If any change occurs during the lifetime of the project this task can prove challenging for large software systems. In literature seldom consideration for managing the obsolete requirements is mentioned. Alongside scope creep, requirements creep are considered as two of the five core risks during the execution of requirements phase. It is stated in the article that the longer it takes to implement a requirement the higher is the risk of change. Researchers often relate Obsolete Software Requirements (OSR) with volatility. A proper definition given to an OSR is 
**"An obsolete requirement is a software requirement that is no longer required for the current release and which has no value or business goals for the potential customers or users of a software artifact for various reasons."**

To find the interesting criteria in this field the authors planned to carry out a survey that would reach a large number of people. It consisted about 15 open and close ended questions with questions being both multiple-choice and single-choice questions. The research questions addressed in this article are 9 and these are derived from core basics like the asking for the definition of OSR and the kind of impact it creates on the companies. Some of them investigate on finding out the various types of requirements getting obsolete, finding out if OSR's are related to software context. Some included in finding out if there are any practices followed for handling the OSR's.

Next we will discuss research questions and the summarised information on findings of the authors in this article. For the identification of correct Obsolete Requirement definition the author has analysed the answers given by the respondents and then identified the keywords from each of them and eventually framed a definition. Around 30% of the people stated it as it is no longer required and 21% of them stated that it is of no potential use for the users. 

For finding out the potential impact of OSR 45% of the respondents valued it as Somehow Serious and 39% of them classified that it has serious impact. Another interesting criteria found out was that the respondents working with bespoke projects have graded OSR as less serious ones. This could be because of the lack of experience for them working in large scale projects. The authors next concentrated on finding out what type of requirements generally become obsolete. From the results it was clearly evident that the OSR's belonged to the categories of the misunderstood requirements and inconsistent requirement and ambiguous requirements. The respondent’s domain, company size and the methodologies they follow have minimal effect on the results furnished in this article.

More than 50% of the respondents say that there is only manual way to find out the OSR's and this is the primary method. Some of them mentioned that they could be identified by execution of test cases based on requirements which seems to be interesting and carry out further research. Once these requirements have been identified some means has to be used to handle them, but then over 50% of the respondents say that they keep them but assign them as "obsolete" and write reasons for that while some say that they would move them to a separate column named as Obsolete requirements. During Requirement Validation or Requirements changing or requirements analysis phase it is good to handle the obsolete requirements. 

There are few existing practices for managing the OSR's. According to the answers by the respondents they are:
1. Reviews of requirements and requirements specifications
2. Using tools and "marking requirements as obsolete"
3. Requirements traceability
4. Discussing and prioritizing requirements with frequent customer interaction
5. Moving OSR's into a separate section in the Systems Requirements Specifications (SRS)

While these are some other processes and methods are also listed in this article where are some them are as listed below:
1. Projective analysis through modelling: It studies the complexity pertaining to systems of systems and requires a skilled process modeller to analyse these requirements and align with the model paradigm.
2. Requirements-based test plans.
3. Commenting out obsolete code and updating requirements documents accordingly.
4. Using requirements validation techniques.

### Seminar 4: 

#### Questions: 

**1. What tools are available for requirements management?**

Requirements Management is a complex task that needs the support of at least a small suitable tool like the flip charts or index cards. Offline application or suites are the most widely used tools for requirements management and specification. The main advantage being the ease of use. However there are some deficiencies like not treating a requirement as a separate entity, poor traceability, no support of parallel documentation editing, etc. 

On the other hand there are Word processors which are offline applications mostly used for developing requirements management specification documents
Then there are Spreadsheet Software, Presentation software, Visual Modelling tools, Issue Tracking Software, etc.

Some examples of these tools are [1]: 

1. [Cognition Cockpit (7-4) by Cognition Corporation](http://cognition.us/) 
2. [codeBeamer Requirements Management (7.6) by Intland Software GmbH](http://intland.com/codebeamer/product-overview/)
3. [IBM Rational DOORS (9.6.1.2) by IBM](http://www-03.ibm.com/software/products/en/ratidoorfami)
4. [Polarion Requirements (2015) by Polarion Software](www.polarion.com/products/requirements/index.php)
5. [Caliber (11.4.2) by Borland (Micro Focus)](http://www.borland.com/en-GB/Home)

**2. Any particular tools for agile requirements management?**

Similarly they are tools for agile requirements management. Some of them are listed below [1]:

1. [HP Agile Manager (2.30) by Hewlett-Packard](http://www8.hp.com/us/en/software-solutions/agile-project-management-software-development/index.html)
2. [Jira Agile (6.6.80) by Attlassian](https://www.atlassian.com/)
3. [Rally (2015.1) by Rally Software Development Corp.](https://www.rallydev.com/)
4. [VersionOne (15.0.9) by VersionOne](https://www.versionone.com/)

**3. Thesis on finding challenges of Continuous Integration in the Context of Requirements breakdown:**

[2] Debbiche, Adam, and Mikael Dienér. "Assessing challenges of continuous integration in the context of software requirements breakdown: a case study."

Continuous Integration (CI) is the concept where the teams get all the code together in one place everyday. The thesis is mainly focussed on assessing the challenges of continuous integration and requirements breakdown and their influence on the whole process. For the software companies to withstand the heavy competition it is crucial for them to adopt agile practices as they put more emphasis on the customer satisfaction and collaboration. CI is often related to the number of check ins made daily. A typical check-in can be build of the software provided that all the tests are passed. CI has been originated from the eXtreme Programming agile method where the goal of each developer is to commit code several times a  day and then build and test the software.

The author has made good effort in introducing the knowledge required to understand the thesis for all the readers. The readers will go through Agile Software development, Requirements breakdown, continuous integration, etc. The fulfil the purpose of the study the authors have carried out a case study at Ericsson by thoroughly examining a case the comppany is currently working on. Following that they carried out 13 semi-strucutured interviews of the employees of that company. The research mainly focussed on finding the challenges of impementing CI process and then the influence of requirements breakdown on CI.

CI at Ericsson takes place in the following procedure: One team starts working on a featureand then pushes all the changes into the work branch. After the completion of the feature the changes are pushed to the Latest Local Version where it is tested. Then the pre-test build is generated for the successfully tested product which is later on integrated to something called Latest Stable Version. Similarly Requirements breakdown at Ericsson is done with the Operational Product Owners who are responsible for the featuring of Product Backlog and deciding the order of requirements execution. Then a cross-functional team uses this data to create the sprint backlog. And it is largely dependent on the cross-functional teams where the requirements are broken down. 

The different challenges as found out by the authors in the fields of CI and requirements breakdown are as follows:

Challenges in CI: 

1. Mindset: Companies while migrating to CI often face challenges with the midnsets of the developers. 7 out of 13 interviewees clain that developers are always positive about the concepts of CI.
2. Tools and Infrastructure: Many tools are required to carry out the CI in an efficient way. These include tools for reviewing code, visualizing test results, running automated test cases, etc.
3. Testing: According to the authors findings testing challenges is because of the lack of automated tests along with a stable test framework for the developers.
4. Domain Applicability 
5. Understandability
6. Code Dependencies
7. Software Requirements 

Some challenges identified for requirements breakdown are with the requirements abstraction i.e. finding the right level of abstraction for the requirements, alignment of requirements with tests to be properly integrated with the mainline, Customer Value and guiding principles. Now that we have seen different challenges faced in each of these domains the author tried ot find out the influence of one upon the other. 

Breaking the requirements led to the development of smaller units and these units are proving challenging for the companies to carry out the testing. Hence these must be combined to form features. Using CI on demand product delivery is possible but the number of integrations done before that has to generalised and finalised.

#### References:
[1]A. Birk and G. Heller, "List of Requirements Management Tools | The Making of Software", Makingofsoftware.com, 2016. [Online]. Available: http://makingofsoftware.com/resources/list-of-rm-tools. [Accessed: 11- Jan- 2016].
