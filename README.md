# [1] Technology Roadmap Guide

## 📌 Overview

This document aims to enhance the understanding of technology roadmap establishment by comprehensively covering the concept of a technology roadmap, its actual construction methodologies, and experience sharing.

## 📚 Table of Contents

1.  **Understanding Technology**
    *   Definition of Technology
    *   Types of Technology
    *   Criteria and Sensing of Promising Technologies
    *   Technology Levels
    *   Data Needed for Sensing Promising Technologies
    *   Examples: Gartner Hype Cycle & MIT Innovation Technology
2.  **Technology Roadmap Overview**
    *   Definition and Necessity of Technology Roadmap (TRM)
    *   Components of a Technology Roadmap (TRM)
    *   Characteristics of a Technology Roadmap (TRM)
    *   Definition and Necessity of Technology Roadmapping
    *   The Innovation Funnel
    *   Future Prediction Methodologies
    *   Relationship between Technology Roadmapping and Future Prediction Methodologies
3.  **Technology Roadmapping Methodology**
    *   Data Analysis Based Roadmapping
        *   Starting Point and Methodology
        *   Exploratory Data Analysis (EDA)
        *   Steps in Data-Based Technology Roadmapping
        *   Objectives of Data-Based Roadmapping
        *   Information Required for Roadmapping
        *   Data Collection, Refinement/Visualization, Clustering, Interpretation, In-depth Analysis, Evaluation
        *   Data Verification and Time-Cost Issues of Technology Trend Analysis
        *   Evaluation Criteria of Analysis Results
    *   Workshop-Based Roadmapping
        *   Necessity of Workshops
        *   Technology Evaluation Workshops
        *   S-Plan (Level 1~2 Trend/Technology Derivation)
        *   T-Plan (Level 3 Technology Derivation)
        *   Workshops with Consumers (Customers)
        *   Workshops with External Technology Experts
        *   Digital Non-Face-to-Face Workshops
4.  **Experience Sharing Related to Technology Roadmapping**
    *   When Internal Information Is Well Understood vs. When Only Publicly Available Information Is Used
    *   The Necessity of Technology Roadmapping for Mass Production R&D Organizations
    *   Industrial Expandability of Data-Based Technology Roadmapping
    *   Importance of Consumer Opinion
    *   Technology Roadmap Configuration and Required Knowledge/Skills for Data-Based Roadmapping

## 💡 Detailed Contents

### 1. Understanding Technology

*   **Definition of Technology**: The totality of knowledge, experience, know-how, physical entities, and procedures necessary to produce items and services that increase human utility by using science.
*   **Types of Technology**: Classified functionally into basic, standard, applied, cutting-edge, proprietary, known, core, emerging, and scouting technologies, etc.
*   **Criteria for Promising Technologies**: May vary by researcher or organization and consider the importance of technology, the capabilities of the company, timeliness, and impact.
*   **Technology Level**: Classified into strategic technology (Lv1~2) and TRM technology (Lv3~4).
*   **Data Needed for Sensing Promising Technologies**: Competitor R&D activity data (patents, papers), news, media information, R&D funding data, etc.
*   **Gartner Hype Cycle & MIT Innovation Technology**: Utilized to grasp future promising technology trends.

### 2. Technology Roadmap Overview

*   **Technology Roadmap (TRM)**: A comprehensive plan including the anticipation of future markets and projecting necessary technologies and products to be developed to meet future demand, in order to select the best technical alternatives.
*   **TRM Components**: Consists of external environment/driver, internal strategic direction, function/product/system classification, technology roadmap, and other considerations.
*   **TRM Characteristics**: Mostly confidential/secret data, a communication tool, must be revised at least once a year.
*   **Technology Roadmapping**: A systematized process for creating a technology roadmap.
*   **Innovation Funnel**: Utilizes methodologies based on creativity, expertise, interaction, and data.
*  **Future Prediction Methodologies**: Utilizes various methods such as scenarios, expert panels, roadmapping, Delphi, interviews, literature reviews, etc. in combination.
*   **Relationship between Technology Roadmapping and Future Prediction Methodologies**: There is a close relationship, and this is used in technology/product/service roadmapping.

### 3. Technology Roadmapping Methodology

#### 3.1. Data Analysis Based Roadmapping

*   **Starting Point**: How to classify (clustering, classification) "technology" well through data analysis, how to visualize "technology ecosystems" well through data analysis, how to derive "accurate technology trends" through data analysis, and whether it is possible to extract "truly good technologies (competitive technologies worth benchmarking)" through data analysis.
*   **Methodology**: Unsupervised learning such as text mining, clustering, network analysis, etc.; also includes methodology to suggest 'promising technologies' by evaluating 'data' through constructing evaluation indicators, calculation by evaluation indicators, decision-making methodology, and supervised learning, etc. It is also important to identify/evaluate promising technologies by reading each item of data (patent/paper).
*   **Exploratory Data Analysis (EDA)**: In order to find and derive "new technology trends/classifications"
*   **Steps in Data-Based Technology Roadmapping**: Data Collection → Data Refinement/Visualization → Technology Clustering → Technology Group Interpretation → In-depth Analysis → Data Evaluation → Decision Making and Deriving Insight.
*   **Goals of Data-Based Roadmapping**: Provides accurate competitor technology trends (based on publicly available data), provides accurate future technology trends (the trend line must accurately show the rise or fall), provides analysis results of technology trends from various perspectives (viewpoint of vehicle, performance, competitor, technology, evaluation, etc), and provides the maximum external trend data for technology roadmapping. Selects patent/papers(technologies) from competitors and leading companies that have value and are worth benchmarking, and then provides this pool and a deep analysis of the detailed contents of each patent/paper to the researchers.
*   **Information Required for Roadmapping**: Customer complaints/opinions (VOC), policy/regulation information, competitor M&A information, competitor media information, competitor paper information, competitor patent information, expert interview results, expert workshop results, company internal R&D plan (top-down strategy), and technology roadmaps and internal R&D results that have been created yearly.
*  **Data Analysis Process**:
    1.  **Data Collection**: Policy/regulatory information, market/industry information, (of each global country) R&D investment information, media information, paper information, patent information.
    2.  **Data Refinement/Visualization**: Derivation of a literature similarity matrix using text mining (cosine similarity, Jaccard similarity, Word2Vec, Doc2Vec, etc.), and network analysis (graph theory, node/edge, direction of edge, relationship (co-occurrence, citation relationship, etc.), 1 or 2 mode network, Centrality statistic, etc.).
    3.  **Technology Clustering Analysis**: Utilizing algorithms that group together similar technical documents. Necessary knowledge of text mining and network clustering methodologies is required.
    4.  **Technology Group Interpretation**: Extract the main data characteristics (keywords, technology classification, etc.) of each technology group and label each technology group with a representative name using technical knowledge.  Requires not only data analysis such as text mining, but also technical knowledge.
    5.  **In-depth Analysis by Technology Group**: Performing statistical analysis and qualitative analysis of the data included in each technology group.
    6.  **Data Evaluation**: Evaluation: Absolute evaluation, relative evaluation ☞ relative evaluation. Patent evaluation is not an 'absolute evaluation' but rather for a 'relative evaluation' between patents within a patent pool. Evaluation indicators: quantitative, qualitative indicators ☞ uses both quantitative/qualitative indicators. Patent evaluation score = (evaluation indicator 1 + evaluation indicator 2 + evaluation indicator 3 + .....). Generally, the higher the number of independent claims and citations, the better the qualitative patents.
*   **Data Verification**: Interpretation by a technology expert is needed.
*   **Technology Trend Analysis**: Technology trend analysis is "big data analysis" and can consume a lot of time and money. Thus, an analysis framework must be well crafted. Can be broken into: \[1] Analysis of a specific technology field (analysis of the technology trends of competitors in that organization's R&D area); \[2] Analysis of a specific technology field and each field of A, B, and C (analysis of technology trends in that organization's R&D area or surrounding areas); \[3] Analysis of the entire industry including a specific technology field (analysis of metal light weight technology trends in various industries, not just the automobile industry).
*   **Analysis Evaluation Criteria**: Has an in-depth technology analysis report been written to be close to the technical knowledge/level of the current researchers? Has the data been visualized to enable the current researchers to grasp the technology ecosystem of competitors at a glance? Has a report been written that can help the current researchers decide on their strategic direction by looking at the technology ecosystem of competitors? Has a technology classification (clustering-based analysis) been selected that can be agreed upon by current researchers? Has the report been written based on the "current terminology" used by the current researchers? Has the technology knowledge that the current researchers already know been formalized/systematized and visualized in a report? Has information that the current researchers do not know well been systematically written?

#### 3.2. Workshop-Based Roadmapping

*   **Necessity of Workshops**: The most important information needed for TRM is competitor internal information; However, competitor internal information is secret. Top tier consulting firms utilize such information through their networks, but the cost of consulting is very expensive. Thus, the most cost effective method to create TRM is to analyze publicly available big data, however, this is only useful from the standpoint of a follower. From the standpoint of a first-mover, information analysis is only a supplementary means. Setting independent goals and deriving technology through technical workshops is more important.
*   **Technology Evaluation Workshops**: A workshop in which the key personnel of an organization come together to set long-term goals and derive detailed technologies that correspond to these goals; A technology pool must have been formed before the workshop.  Internal and external experts come together to evaluate technologies, select promising/innovative technologies, classify technologies to be developed for short/mid/long term, and evaluate marketability/business potential/technical aspects. There is also the advantage of being able to deeply review a single technology with many people together.  Internal experts know the internal resources, infrastructure, and technology levels well. External experts have a technical trend and solution at the Level 3~4 that they are currently researching. A technical management expert knows the technical trends at the Level 1~2 well and has a wide knowledge of many technical fields, and is skilled at evaluating converged technologies.
*   **S-Plan (Lv. 1~2 Trend/Technology Derivation)**: Workshops to draw the big picture and derive strategic direction, examine various external environments/drivers at a broad level, and through brainstorming, each participant in the workshop derives (external environment/driver - product - technology) as a set (idea). The work to review these ideas internally by arranging them in a roadmap is then carried out.
*   **T-Plan (Lv. 3 Technology Derivation)**: A workshop to select technologies to develop and place them in the technology roadmap. The (environment - product - technology) sets from the S-plan are re-examined to determine the technologies to develop. The technology trends of competitors are analyzed and used as reference data for the workshop participants, then the technology roadmaps are completed by product/system/subject.
*   **Consumer Workshops**: This is a workshop to reflect consumer (customer) opinions into the technology roadmap.  Primarily, consumers are called to participate in a brainstorming session in S-Plan.  However, there are many processes required to basically reflect consumer opinions into technologies, and from the standpoint of the one creating the technology roadmap, consumer opinion is more appropriately collected through the following methods, instead of through workshops. It is possible to carry out surveys to determine consumer preference for certain products, (utilizing Conjoint analysis and AHP, etc.). By analyzing the opinions and emotions of consumers, one can analyze whether there is usability when matching products/systems/technologies and establishing a technology strategy.  However, consumers generally do not have much interest in "technology itself" but only express the "products/services" that they have. Consumer's technical insight is subjective, and a separate dimension is required to apply this to the technology development sector (using QFD, etc).
*   **External Technology Expert Workshops**: A workshop to derive insights on the future technologies using external, credible experts. Seminars may be hosted just before the workshop by inviting experts who have high knowledge/insight in technology in order to raise the technological knowledge of workshop participants. Experts can participate directly in the workshop to evaluate technologies and to assist in deriving technologies. However, participation in the actual technology roadmap drawing process is not possible (the principle being that technology roadmaps must not be made public to any organization). The personnel from component companies and cooperating companies that participate directly in technology development are also eligible.
*  **Digital Non-Face-to-Face Workshops**: Workshops are carried out exclusively through video conferences. Each organization can form groups by subject, gather at different places, and perform the workshop simultaneously with a camera in front of them. The coordinator directly monitors the process of the workshop, and must respond to technical/methodological questions in real-time.  Accurate guidelines and result formats/examples must be provided.

### 4. Experience Sharing Related to Technology Roadmapping

*   **Data-Based Technology Roadmapping**: The advantage is that this is the most persuasive and effective method for technology roadmapping (grasping external competitor technology ☞ utilizing it in one's own roadmapping). The disadvantage is that it is difficult to discover technologies to be developed in the long term. One cannot break free from being a fast follower.
*   **Workshop-Based Technology Roadmapping**: The advantage is that consensus can be reached among researchers with many vested interests. The disadvantage is that different results can come out depending on the location/time/members.
*   **When Internal Information Is Well Understood**: The advantage is that truly needed technologies can be proposed internally.  Unnecessary technologies (technologies already developed internally or reviewed) do not need to be proposed. The disadvantage is that the conclusion is decided according to the technology trends and flow shown in the internal information (possibility of having a result without impact).
*   **When Only Publicly Available Information Is Used**: The advantage is that because the process is done without internal information (without any internal help), the result has a strong, objective character. It is accepted even if it is a predictable result.  The disadvantage is that it may not match the internal strategic direction or flow (like a witch doctor catching a man).
*   **The Necessity of Technology Roadmapping for Mass Production R&D Organizations**: Generally, the mass production R&D organization develops technologies by focusing on product lineups within the 3~5 year period, but mid- to long-term technology roadmapping is also needed. An advantage of the mass production organization is that because technology development is linked to production, they are considered to have the ability to select technologies with high commercialization potential, and thus they are at an advantage when evaluating proposed technologies. A disadvantage of the mass production organization is that they focus mainly on improvement technologies, rather than innovative technologies, and thus it is difficult to propose technologies that match their very high level of technological knowledge/difficulty.
*   **Industrial Expandability of Data-Based Technology Roadmapping**: It is considered to be impossible. In the semiconductor industry, it is about the struggle of process. In the IT industry, customer needs differ greatly and there is a fast adoption of new technologies. It is difficult to obtain competitor information from publicly available information (patents/papers) and it is more a domain of know-how than technology development by publicly available technology literature.  However, 'service roadmapping' and not technology roadmapping, is considered to be possible (ex. mobility and IT service roadmaps, etc.).
*   **Importance of Consumer Opinion**: Technologies with clear consumer needs are important (ex. IT, consumer goods, vehicle interiors, etc). In areas where consumer needs are not clear, it is difficult to move to technology roadmapping. Consumer opinions are reflected in technology roadmaps at the 'technology strategy' level, but not usually at the 'component technology' level. Lead user workshops (from MIT) are one alternative.
*   **Technology Roadmap Configuration**: The technology roadmap includes all of the information below: Competitor strategy/technology trend, one's own strategy/technology trend, technology development direction, technology tree, technology roadmap.
*   **Required Knowledge/Skills for Data-Based Technology Roadmapping**: Technical management knowledge, basic engineering knowledge (mechanical, electrical, chemical, etc), statistical analysis (time series analysis, etc), data analysis (clustering, network analysis, literature analysis, etc), and other things such as natural language processing, database, decision-making methodology, and surveys (conjoint analysis, etc.).

## 📝 Conclusion

A technology roadmap is a crucial tool for anticipating the future and setting the direction of an organization's technology development. An effective technology roadmap can be created by properly utilizing both data analysis and workshops, and a method of approach suitable for each organization's characteristics and situation is needed. I hope that this document can raise the understanding of technology roadmap creation, and be applied in actual work.

## 🔗 Instructor Information

*   **Instructor**: Dongha Kim
*   **Linkedin**: [https://www.linkedin.com/donghakim417](https://www.linkedin.com/donghakim417)
*   **Personal Email**: eastsea17@gmail.com


<hr/>


# [2] Data-Driven Technology Trend Analysis Basics Guide

## 📌 Overview

This document covers the basics of technology trend analysis using patent data, including data collection, analysis, visualization, and practical exercises.

## 📚 Table of Contents

1.  **Instructor Introduction**
2.  **Objectives and Goals of This Special Lecture**
3.  **Technology Sensing/Analysis Process**
    *   Data Collection
    *   Data Visualization
    *   Technology Clustering
    *   Technology Group Interpretation
    *   In-Depth Analysis by Technology Group
    *   Technology (Patent) Evaluation
    *   Decision Making and Insight Derivation
4.  **Objectives of Technology Sensing/Analysis**
    *   Technology Trend Analysis Objectives
    *   R&D Strategy Establishment Objectives
    *   Technology Commercialization Objectives
5.  **Technology Roadmap (TRM) and Components**
    *   Definition of Technology Roadmap (TRM)
    *   TRM Components (External Environment/Drivers, Internal Strategic Direction, Function/Product/System Classification, Technology Roadmap, Other Considerations)
6.  **Definition of Technology Roadmapping**
7.  **Definition and Classification of Technology**
    *   Definition of Technology
    *   Types of Technology
    *   Criteria for Promising Technologies
    *   Promising Technology from a Data Analysis Viewpoint
    *   Technology Levels
    *   Data for Technology Sensing/Analysis
8.  **Technology Exploration**
    *   Level 3-4 Detailed Technology Exploration
    *   Level 1-2 Strategic Technology Exploration
    *   Gartner Hype Cycle & MIT 10 Innovation Technologies
9.  **The Technology Innovation Process (Innovation Funnel)**
10. **General Future Prediction Methods**
    *   Creativity-Based, Expertise-Based, Interaction-Based, Data (Evidence)-Based Methodologies
11. **Network Analysis**
    *   Definition of Network Analysis
    *   Data Required for Network Analysis
    *   Matrices Required for Network Analysis (Node-Edge-Weight Matrix, Adjacency Matrix)
    *   Definition of Relationship
    *   Co-occurrence
    *   Directionality
    *   Centrality Statistics (Degree, Closeness, Betweenness, Eigenvector)
    *   HITS Statistics
    *   1/2 Mode Network
12. **Patent Data**
    *   Definition of Patents
    *   Patent Life and Death
    *   Patent Application and Registration Process
    *   Patent Data/DB and Main Fields
    *   Paper Data/DB
    *   Patent Family
    *   Co-occurrence and Directionality Fields
    *   Problems of Patents
13. **Formulating Patent Search Queries**
    *   Field Selection (Keyword, CPC)
    *   Keyword Search and CPC Search
    *   NOT Conditions (Excluding Stop Words and Unnecessary CPCs)
    *   Other Considerations (Country, Data Range, etc.)
14. **Using Gephi and Practice**
    *   Introduction of Gephi and Features
    *   Setting Up the Screen and Installing Plugins
    *   Importing Data (Excel/CSV files)
    *   Obtaining Statistics and Modularity Analysis
    *   Coloring Nodes and Adjusting Layout
    *   Node/Edge Filtering
    *   Utilizing Data Laboratory
    *   Preview
15. **Document Similarity Network**
    *   One-hot vector
    *   TF-IDF
    *   Dense vector (Doc2Vec)
    *   Bibliographic coupling
16. **Introduction of Other Tools**
    *   UNICET, Pajek, etc.

## 💡 Detailed Contents

### 1. Instructor Introduction

*   **Instructor**: Dongha Kim
*   **Education**: Master's degree in Industrial Engineering, Yonsei University Graduate School
*   **Lecture Area**: Technology trend analysis/promising technology analysis through data analysis
*   **Main Career**: Technology Information Team at Hyundai NGVs (2015-Present)

### 2. Objectives and Goals of This Special Lecture

*   **Objective**: To explore technologies related to our business items by collecting/refining patent data and Clustering
*   **Goals**: To acquire the ability to explore and analyze technologies related to business items, search patent data, and conduct technology trend analysis.

### 3. Technology Sensing/Analysis Process

*   **Steps**: Data Collection → Data Visualization → Technology Clustering → Technology Group Interpretation → In-Depth Analysis by Technology Group → Technology (Patent) Evaluation → Decision Making and Insight Derivation
*   **Tools**: Gephi, VOS Viewer
*   **Core**: Understanding data, graph theory-based network analysis, clustering analysis, text mining

### 4. Objectives of Technology Sensing/Analysis

*   **Technology Trend Analysis Objectives**: Understand detailed technology composition, identify basic/application technology composition, grasp competitor R&D activities
*   **R&D Strategy Establishment Objectives**: Establish the direction of the company's R&D strategy, use as a basis for technology roadmapping, and find promising technologies.
*   **Technology Commercialization Objectives**: Adopt a step-by-step approach for technology commercialization, establish a decision-making process

### 5. Technology Roadmap (TRM) and Components

*   **Definition**: A comprehensive plan that includes projecting necessary technologies and products to be developed to meet future demand, based on predictions of the future market, in order to select the optimal technological alternatives.
*   **Components**: External environment/drivers, internal strategic direction, function/product/system classification, technology roadmap, other considerations.

### 6. Definition of Technology Roadmapping

*   **Definition**: A systematized process for creating a technology roadmap, the process of searching for and defining markets, products, and technologies.

### 7. Definition and Classification of Technology

*   **Definition of Technology**: The totality of knowledge, experience, know-how, physical entities, and procedures necessary to produce items and services that increase human utility by using science.
*   **Types of Technology**: Classified functionally into basic, standard, applied, cutting-edge, proprietary, known, core, emerging, and scouting technologies, etc.
*   **Criteria for Promising Technologies**: May vary by researcher or organization and consider the importance of technology, the capabilities of the company, timeliness, and impact.
*   **Promising Technology from a Data Analysis Viewpoint**: Utilizing evaluation of timeliness and impact for promising technology assessment.
*  **Technology Level**: Divided into strategic technology (Lv1~2) and TRM technology (Lv3~4).
*  **Data for Technology Sensing/Analysis**: Competitor R&D activities, news, media information, patents, research papers, R&D funding data, etc.

### 8. Technology Exploration

*   **Level 3-4 Detailed Technology Exploration**: Uses competitor R&D activity data (patents, papers), with a limitation on data within the past two years lacking completeness
*  **Level 1-2 Strategic Technology Exploration**: Tracks R&D trends of national research institutes and company advanced research institutes, using country specific R&D investment data to supplement the retrospective characteristics of patent/paper data.
*   **Future Technology Trends**: Utilizing the Gartner Hype Cycle and MIT 10 Innovation Technologies.

### 9. The Technology Innovation Process (Innovation Funnel)

*   **Steps**: Idea Derivation → Concept Concretization → Production, organization absorbs ideas or technology from the outside.

### 10. General Future Prediction Methods

*   **Creativity-Based**: Scenario prediction/analysis, essays, simulations
*   **Expertise-Based**: Expert panels, roadmapping, Delphi, interviews, multi-criteria decision making
*   **Interaction-Based**: Future workshops, brainstorming, conferences/forums, consumer panels, surveys
*  **Data-Based**: Literature review, extrapolation, literature analysis (patent analysis), benchmarking

### 11. Network Analysis

*   **Definition**: The analysis to identify the relationships between Nodes by structuring networks consisting of Nodes and Edges.
*   **Required Data**: Data that has a relationship (Relationship; Edge) between analysis targets (Nodes). Data where the relationship (Relationship) is defined through co-occurrence and directionality etc. can be utilized.  A network can also be drawn without a direction of an Edge. (= Undirected graph).
*   **Matrices**: Node-Edge-Weight Matrix, Adjacency Matrix.
*   **Relationship**: Primarily defined through co-occurrence, directionality, similarity, etc.
*   **Centrality**:  Degree, Closeness, Betweenness, Eigenvector (the measurement of the relative importance of nodes in a network)
*   **HITS Statistics**: Algorithms that evaluate nodes based on Hub scores and Authority scores.
*   **Network Type**: 1 Mode (single node type), 2 Mode (two node types)

### 12. Patent Data

*   **Patent**: An exclusive and privileged right granted to an inventor. In return for a disclosure of a new technology, exclusive rights to that technology are granted for a limited time.
*   **Patent Life**: Automatically made public to the general public about 1 year and 6 months to 2 years after the patent application is filed, or may be made public in 6 months if a request for priority examination is made.
*   **Patent Death**: Termination upon expiration of patent period, cancellation by patent infringement lawsuit, expiration due to unpaid registration maintenance fees, withdrawal of registration.
*   **Application/Registration**: Evaluated based on novelty, inventiveness, and industrial applicability, rejection is possible with a chance for re-examination.
*  **Data**: Structured (patent number, applicant, IPC, CPC) and unstructured (title, summary, claims, etc.) data included.
*   **Paper Data**: Citation DB, Original Text DB, Big Data DB
*   **Patent Family**: Interlinked based on priority number, redundant data should be removed
*   **Co-occurrence Fields**: CPC code etc., information on co-existing fields.
*   **Directionality Fields**: Citation/being-cited relationships.
*   **Problems with Patents**: Past data, mostly improvement technologies, possible errors in the IPC/CPC classification, and difficulties in understanding the technical content.

### 13. Formulating Patent Search Queries

*  **Field Selection**: Selection of search field, including IPC, CPC, Title, Summary
*   **Keyword Search**: Extracting core keywords, considering synonyms/similar words/derivatives/lower-level terms, and searching in title/summary/claims fields.
*   **CPC Search**: Searching through CPC codes and using a natural language-based CPC search function.
*   **NOT Conditions**: Excluding stop words and unnecessary CPC codes.
*   **Other Considerations**: Area of commercialization, data range, patent type (registered/application)

### 14. Using Gephi and Practice

*   **Introduction**: Tool for Visual Analytics, EDA, realtime visualization of graphs, has many functions.
*   **Setting Up the Screen**: Setting the Layout, Appearance, Statistics, and Filter.
*   **Data Import**: Import data from Excel and CSV files (Matrix, Adjacency list formats).
*   **Statistics**: Calculate Average Degree, Weighted Degree, and Network Diameter.
*   **Modularity Analysis**: Calculation of grouping between Nodes with high connectivity.
*  **Node Coloring**: Colors nodes based on Modularity values and attributes.
*   **Layout Adjustment**: Adjust layout by selecting desired criteria and applying the ForceAtlas2 algorithm.
*   **Node/Edge Filtering**: Filtering data based on selected criteria.
*   **Data Laboratory**: Exporting Data and adding group data.
*   **Preview**: Ability to preview the visualization.

### 15. Document Similarity Network

*   **One-hot Vector**: Representation of word frequency in a document, Doc-Term-Matrix.
*  **TF-IDF**: Method to weight word frequency.
*  **Dense vector (Doc2Vec)**: Embedding documents into a vector in order to calculate similarity.
*   **Bibliographic coupling**: Analyzes relationships by looking at shared citation relationships between documents.

### 16. Introduction of Other Tools

*   UNICET, Pajek etc.

## 📝 Conclusion

This guide helps to understand the basics of technology trend analysis using patent data, and provides an experience of the actual data analysis and visualization process. Patent data shows past technology trends, and through that it is possible to anticipate the direction of future technology development and make strategic decisions.

## 🔗 Instructor Information

*   **Instructor**: Dongha Kim
*   **Email**: eastsea17@gmail.com
