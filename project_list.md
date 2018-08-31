# Project List

Please file your top THREE choices as an issue (will go over in class) by Wednesday () morning at 11:59 AM (i.e., right before noon).  Please list them in the order that you prefer them.  You will be informed as to your project during the next Capstone class on Friday 8 Sep.  If you do not file an issue by then, I will assume you do not care which project you are on and I will place uncommitted students on whichever projects still need people.

REMEMBER TO ADD "PROJECT" TO THE BEGINNING OF YOUR ISSUE TITLE!

Along with your selections, please include any qualifications or specific reasons for interest that you have for those specific projects.   Remember that you are "interviewing" for the project against others, especially if you have selected popular projects.   Students who respond early also show enthusiasm for the projects, which goes a long way to showing that they actually want to do them.

I will attempt to place you in one of your top three choices.  Last semester, every student got into one of their top three (and a majority into their #1 choice), although I do not make any guarantees.

Note: Some of you may be working on private projects.  Please file an issue on this repository (as above) but note that you have already been assigned to a project.  List the project and the name of the POC (e.g. faculty member or supervisor).  If we have not discussed you being placed on a private project, do not put yourself on one.

## Industry

### NetApp

In application development, RESTful APIs are an increasingly popular method of
exposing functionality to users. This popularity has led to an effort known as the OpenAPI
Initiative, which has formed to standardize how REST APIs are described and documented.
Developers at NetApp have designed a RESTful API for our proprietary operating
system known as ONTAP. Our API specification is in accordance with the OpenAPI standards,
which allows others to more easily read, explore, test, and consume our API. This, in turn, makes
it simple for anyone to develop applications and scripts that are built on ONTAP!
These aren’t the only benefits of adopting the OpenAPI standard—doing so also brings a
large ecosystem of tools built around OpenAPI. For this Capstone project, NetApp is looking to
leverage the code-generating tool known as Swagger-Codegen. This tool can take any API
specification written according to the OpenAPI standard and procedurally generate code
designed for any number of purposes and written in any number of different programming
languages.

In this project, students will work with the Swagger-Codegen tool to generate an API
client library for Python. This procedurally-generated library will enable simple management of
Data ONTAP with Python. Over the course of this Capstone project, students will utilize several different
programming languages and concepts, including:

* Working with HTTP to interact with RESTful software applications.
* Writing in Java to extend the Swagger-Codegen tool to utilize the unique functionality of the
ONTAP REST APIs.
* Implementing object-oriented coding principles to design abstract templates used for
procedural code generation.
* Leveraging the strengths of the Python programming language and the functionality of the
ONTAP API to create a new Python library to be used by developers here at NetApp!

(POC: Tim Banyas, Software Engineering Manager, NetApp)

### General Dynamics / Viz

Lightweight Open Web Analysis

Most web analysis systems are proprietary and heavyweight, meaning that most of their algorithms is hidden and unable to be validated.  It leads to a misunderstanding of the answers.

This project proposes to develop a lightweight open system that does web analysis in the most straightforward and modular way.  It will not hide the implementation and make it available for understanding.  It will be able to be selected as needed and not the heavy-weight requirements.  This will be used not only for proper validation, but also as a platform to make web analytics more inclusive.  It should allow for the processing of data without an integration of required hooks that forces users to be locked in simply because of the effort needed to change.

The application should be developed to provide reusable components that can be used in many types of web analysis as well as other forms of analytics.

(POC: Mike Bigrigg, General Dynamics Viz and University of Pittsburgh, Computer Science)

### Bombardier

Bombardier’s Communication Based Train Control System (CBTC) – CITYFLO650, utilizes an offline data capture tool to view system performance. The tool is used to visualize the state of all objects in the system as they occur in real time, in a playback mode in real and x2,x4,x8 timescales. Currently there are 38+ projects world-wide, generating data daily.

The purpose of this project is to create a more modern tool chain to visualize this data, and prepare it for analysis by site personnel. The tool chain should enable rapid site geographic creation, intuitive visualization of site conditions, and above all meet reliability metrics for visualizing data from Safety Related Software Subsystems.  Existing tool chain that is used for visualizing diagnostic data is VB6, and while very stable, requires virtualization in order to run on modern computing systems. Data format and logging is very stable, so the visualization tool is allowed to change as availability of items on the market change.

This project is to propose and deliver a functional prototype using a more modern tool set (e.g. Unity, Android, iOS SDK, .net, Java) to allow for the parsing of this data and display in the same manner of the existing set of projects.  Finally, as systems grow in geographic size, the ability to scale and represent this data in a meaningful way will need to be evaluated and discussed.

**NOTE: NDA and/or IP agreement will need to be signed for this project**

(POC: Muneeb Alvi, Bombardier)

### Queue Engineering Project for nortic.se

**NOTE: This project will be done in conjunction with students from Blekinge Tekniska Högskola, Blekinge, Sweden**

The customer is a local company in south of Sweden, http://nortic.se/, they are selling tickets to different events small and big.

For a popular event there is high demand for tickets, and once all the tickets are sold the “black” market will pop-up where tickets are sold between private persons instead through the company. To prevent one buyer to buy all the tickets and then sell them for a higher price, a limit is set for how many tickets you can buy. To control this and have a fair system a queue is used.

However, this queue can be hacked and users may “cut in line”, and then the system will be unfair.

This project intends to build a queue that is safe and fair on order to manage online ticket purchases.

The project teams will in cooperation with the customer detail the requirements, propose solutions, design, implement and test the system and by the end providing the customer with a functioning queuing system.

(POC: Nina Dzamashvili Fogelström, Department of Software Engineering, Blekinge Tekniska Högskola)

## CS Faculty Projects

### Impact of Artifact Evaluation on CS Scholarly Work

**NOTE: This may involve switching your class number from CS1980 to CS1950.  It will still count for your capstone.**

Many areas of computer science rely almost entirely on empirical evaluation that uses software, data sets, benchmarks, scripts, and a myriad of other artifacts to evaluate new ideas and compare with past innovation. This project aims to study the effectiveness of Artifact Evaluation (AE) in improving the quality of the software tools and methodologies underlying experiments in scholarly publications. The student will survey the ACM Digital Library for conferences in the last 5 years that have carried out AE, gather bibliography information and associated metrics (e.g., citation counts), create relational and graph databases for the information, conduct queries on the information to statistically analyze the data, and produce graphs of the results and make them public accessible on the web.

Required Skills and profiles

* Analytical skills

* Strong programming skills

* Background in MySQL and neo4j desirable

(POC Supervisors: Bruce Childers and Panos K. Chrysanthis)

### A Comparative Study of Approaches for Predicting Patient’s Outcome

**NOTE: This may involve switching your class number from CS1980 to CS1950.  It will still count for your capstone.**

Gene expression sequencing techniques give the ability for scientists to analyze the genetic makeup of different individuals and the molecular mechanisms related to a disease or phenotype. When combined with clinical data such as demographics, disease state, or clinical tests, this data allows for a comprehensive analysis of how genetics cause our health conditions or outcomes. One issue complicating this analysis is the sheer size of the human genome, which makes more complicated analysis algorithms unable to handle the full gene expression dataset. Built upon the Preferential Diversity scheme, we have established a computational methodology to select a subset of important genes for a particular study and disease of interest, that we use for downstream analysis of cause and effect relationships between genes and clinical outcomes. For this project, a student will apply our methodology to publicly available expression data, and compare our approach with other algorithms suitable for these analyses in both ability to predict a patient’s outcome as well as the ability to learn interesting information from the dataset.

Required Skills and profiles

* Analytical skills

* Strong programming skills

* Background in AI/ML/DB desirable

(POC: Dr. Panos Chrystanthis, Computer Science department)

### Cancer Database Evolution on the Cloud

**NOTE: This may involve switching your class number from CS1980 to CS1950.  It will still count for your capstone.**

UPMC Hillman Cancer Center is conducting a Specialized Program of Research Excellence (SPORE) in Skin Cancer. The overall goals of the SPORE are to improve our understanding of molecular and immunologic mechanisms of cancer progression and response to immunotherapy and to validate prognostic and predictive biomarkers for personalized treatment. To this end, large amounts of clinical and genomics data from several sources must be organized and maintained in a way that allows for efficient and secure access as well as user friendly interactions (add, search, select) with the underlying data. In this project, a student will extend the database of the cBioPortal with the data types being generated by the Pittsburgh SPORE Melanoma project. This will be a combined web application and database project with the focus being on usability and security of the database system.

Required Skills and profiles

* Database/SQL skills

* Strong programming skills

* Background in AWS desirable

(POC: Dr. Panos Chrystanthis, Computer Science department)

### QuACC: QUality Analysis of Cryptocurrency Codebases

While cryptocurrency is a burgeoning field at the moment, many projects are of poor quality or are not well-tested.  QuACC performs automated analysis of various cryptocurrency codebases (currently, Bitcoin, Ethereum, Bitcoin Cash, Monero, and Litecoin).  Knowledge of Python, C, C++, and/or static analysis is helpful.  Previous knowledge of cryptocurrency and blockchain technology is not strictly necessary but interest in it is essential.

(POC: Bill Laboon, Computer Science department)

### Segregating Private from Non-Private Data in A Web Service

**NOTE: This may involve switching your class number from CS1980 to CS1950.  It will still count for your capstone.**

The project involves adding user privacy to social media and data sharing services through the use of encryption and hardware protection mechanisms based on Intel's SGX processor extensions. The research angle is looking at how to separate private vs. non-private data in a hosted web service, and protect private data through the use of encryption performed on a client (or 3rd party) hosted proxy service. The privacy protections allow users to access and share personal data and content with other users of the system, while preventing the hosting service itself from being able to access data that the users do not wish to make available.  The project would involve working with the Flask, Bootstrap and React frameworks as well as optionally working with C in an embedded environment.

(POC: Dr. Jack Lange, Computer Science department)

## Non-CS Faculty Projects

### Sterile Compounding Augmented Reality

Training in sterile compounding is a component of pharmacy education and training across the country. Similarly, training for appropriate hand washing required to enter surgical environments are required of medical students. The resources required for this training can be prohibitive due to the time, personnel, and space requirements. Coordinating the resources, trainee experiences, and feedback required in appropriate training is a universal problem for schools, hospitals, and institutions that provide customized pharmacy sterile compounding and surgical procedures in healthcare. Our solution is to create an augmented reality platform to train users in simulated clinical environments using custom hardware controllers and software to model and teach clinical procedures and concepts. See Summary Video for Prototype and past student experiences - http://bit.ly/araug2018. Experience in Unity, Tensor Flow, and machine learning is ideal. Students without experience in these area will be expected (and can look to benefit from) extensive self-directed learning as it directly applied to the project. End of any project should have working coding+documentation, additionally:
1. Hosted/working demonstration of working code; e.g website, exe file, Unity file, etc OR
2. Video (youtube/screencast) walkthrough of working code to address user needs (POC: Dr. Ravi Patel, School of Pharmacy)

### Pitt Civics Mobile App

Pitt Civics is a collaborative coalition of civic-minded Pitt students, staff, and faculty that strives to generate accessible pathways for civic growth for Pitt students.  We seek creative student mobile developers to help us develop a gamified virtual civic learning platform—embracing civic competencies across academic disciplines—that is intended for and open to all Pitt students, and includes content modules dedicated to historic and modern understandings of democratic values, capacities to engage diverse perspectives and people, and commitment to collective civic problem solving.  **NDA or IP agreement may be required** (POC: Ron Idoko, University of Pittsburgh Public Service program)

### CampusGruv

CampusGruv is a campus community engagement app composed of a network of visually engaging 'campusfeeds' that allow for more dynamic interaction between the members - students, alumni, faculty, staff, local businesses, etc. - of respective campus communities.  We are currently seeking creative student developers interested in assessing and redesigning elements our iOS platform.  **NDA or IP agreement may be required** (POC: Ron Idoko, University of Pittsburgh Public Service program)

### Healthy Living App

**NOTE: This project may require signing an NDA or IP agreement**

**NOTE: This project will be done as part of a group with Information Science students**

This semester we are seeking students to develop a working prototype for a Healthy Living mobile application.  Students selected for this team-based project will work directly with a business analyst and the key stakeholder, Dr. Jackic, Director of the Healthy Living Institute at PITT.  Some of the key features of the application require a user to:

* Track caloric intake

* Supply nutritional information on foods

* Create a recipe bank

* Provide instructional videos for exercise

* Show progress through weight-based graphs

* Establish a one/one health coach connection

There are a few openings available on the team for students with skills either in front-end design, web server management, and database management.  The team will consist of no more than 5-6 students (including both CS and IS students).

(POC: Leona Mitchell, Information Science department)

### Sheep and Goat Tracker

An app to track all information pertaining to a sheep and goat production enterprise:  breeding, birthing, weighing, scoring, treating, etc. An app that can make calculations to convert raw data into performance data. For example, to compare weaning weights of lambs and kids, all weights have to be adjusted to a common age. They also have to be adjusted for the sex of the lamb/kid, its type of birth and rearing (single, twin, or triplet), and the age of its dam. It is desirable to convert many performance measures to ratios for easier comparison. It is desirable to be able to summarize information from multiple years and to calculate whole flock/herd statistics.

An proof-of-concept application was made for this in Spring semester using Ruby on Rails.  This would continue development of that proof-of-concept to add additional features, improve quality, etc. (POC: Susan Schoenian, Sheep & Goat Specialist, University of Maryland)
