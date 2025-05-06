---
title: Question Management
has_children: false
nav_order: 11
layout: page
---

# Question Management

## Creating Annotation Questions
In your systematic review protocol, you will have specified certain information you want to extract from each of your studies, such as ‘Were animals randomised to experimental groups?’ or ‘What concentration of drug treatment was used?’. In SyRF you can annotate your studies with this information using annotation questions.

To design annotation questions for a stage of your project, go to ‘Question Management’ under ‘Project Settings’ and below ‘Membership’ on the left-hand navigation bar of your project. (OLD IMAGE BELOW - THIS IS JUST A PLACEHOLDER UNTIL FINAL SITE IS UP)

![alttext](figs/Fig_Question_design.png)

### Question Editing
At present, questions can be added, edited and deleted. Individual questions can also be changed in order. This is primarily due to our database structure. These editing and order features have been implemented in the latest release.

## Question Categories
Annotation questions are entered into the following categories depending on what information they ask about:

### Study Level Questions
Enter any question that is relevant to the overall study. e.g., Do the authors provide a study protocol that is available to you? (Yes or No checkbox).

There will be some questions to which you can add a child question (i.e., sub-question), such as new questions you create yourself or to the Control Procedure under the Treatment section. You can identify this by the plus symbol (insert screenshot here), where the hover over message ‘Add child’ appears.


### Disease Model Induction Questions
There will be some system (i.e., core) questions relating to Disease model induction procedure label and its child question asking whether there was a Control procedure. These questions cannot be edited or deleted as they are system (i.e., core) questions. You can identify system questions by the symbol (insert lock symbol here screenshot from SyRF) next to them. In the same way, you can identify which questions you can edit by the symbol (insert pen thingy symbol here screenshot). 

You can add extra questions using the ‘Add Question’ button below (e.g., control questions, non-control questions or both questions). When adding a question, you will be required to select whether questions related to Control animals, Non-control animals (treatment group animals) or both. 


#### CONTROL QUESTION
Define questions that are specific to the Model control. 

e.g. Do the control animals receive Sham surgery? (Yes or No checkbox)

#### NON-CONTROL QUESTION
Define questions that are specific to the Model. 

e.g., What type of surgery was carried out to induce the model? (Dropdown list with defined options)

#### BOTH
Define questions that are relevant to both Model control and Model animals

e.g., What anaesthetic was used for both the model and sham surgery? (Dropdown list with defined options)

### Treatment Questions
There will be some system (i.e., core) questions relating to treatment. These questions cannot be edited or deleted as they are system (i.e., core) questions. You can identify system questions by the symbol (insert lock symbol here screenshot from SyRF) next to them. In the same way, you can identify which questions you can edit by the symbol (insert pen thingy symbol here screenshot). 

You can add extra questions using the ‘Add Question’ button below (e.g., control questions, non-control questions or both questions). When adding a question, you will be required to select whether questions related to Control animals, Non-control animals (treatment group animals) or both. 

#### CONTROL QUESTION
Define questions that are specific to the Treatment control

e.g., What is the vehicle given to the control animals? (Dropdown list with defined options)

#### NON-CONTROL QUESTION
Define questions that are specific to the Treatment group

e.g., Specify the dose of treatment drug given in mg/kg (Decimal input box)

#### BOTH
Define questions that are relevant to both Treatment control and Treatment animals

e.g., What route of drug or vehicle administration is used in the experiment? (Dropdown list with defined options)  

### Outcome Assessment Questions
There will be some system (i.e., core) questions relating to each outcome assessment procedure in the study. These questions cannot be edited or deleted as they are system (i.e., core) questions. You can identify system questions by the symbol (insert lock symbol here screenshot from SyRF) next to them. In the same way, you can identify which questions you can edit by the symbol (insert pen thingy symbol here screenshot). 

You can add extra questions using the ‘Add Question’ button below, e.g., What is the behavioural test used to measure outcome? (Dropdown list with defined options).

### Cohort Level Questions
There will be some system (i.e., core) questions relating to each cohort (experimental group) in the study. These questions cannot be edited or deleted as they are system (i.e., core) questions. You can identify system questions by the symbol (insert lock symbol here screenshot from SyRF) next to them. In the same way, you can identify which questions you can edit by the symbol (insert pen thingy symbol here screenshot). 

You can add extra questions using the ‘Add Question’ button below, e.g., What is the sex of the animals included in the cohort? (Dropdown list with options males, females, both, unknown).

**_I have cohorts with comorbidities and I'm not clear on how to differentiate between them._**<br/>
[Check out the FAQ](https://syrf.org.uk/faq)

### Experiment Questions
There will be some system (i.e., core) questions relating to each experiment in the study. These questions cannot be edited or deleted as they are system (i.e., core) questions. You can identify system questions by the symbol (insert lock symbol here screenshot from SyRF) next to them. In the same way, you can identify which questions you can edit by the symbol (insert pen thingy symbol here screenshot). 

You can add extra questions using the ‘Add Question’ button below, e.g., Was there a habituation period? (Yes or No checkbox).

You can find more information in the <br/>
[Annotation (Wide Format) Data Dictionary](https://help.syrf.org.uk/data-export/data-dictionary/annotation-wide.html)

## Creating a New Question
To add a question, simply click the ‘Add Question’ button at the bottom of each category you want to design a question in.

When adding a question, you can enter the following details:

1.	The name of your question
2.	A description of the question, which will be displayed alongside your question in SyRF
3.	Whether the question accepts only a single answer or multiple answers
4.	Whether the question is optional or required
5.	The type of answer the question accepts (e.g., text, integers, decimals)
6.	The question type (e.g., dropdown list, checkbox) 

![alttext](figs/Fig_Question_dialogue.png)

### Question Types
There are 6 question types in SyRF:
* Dropdown lists
* Autocomplete lists
* Radio buttons
* Checklists
* Check boxes
* Input boxes

We recommend that when using checklists or check boxes, you set the default checkbox status to ‘indeterminate’.

### Allowing Multiple Answers
If you choose to allow multiple answers, you will be asked if you want these to be split into separate annotations. This refers to how the data will be presented in your output data file.

Choosing to split multiple answers into separate annotations means that, in your output file, the multiple answers will be separated into different rows. Choosing not to split into separate annotations, means that they will appear in the same row, separated by a semi-colon.

If you have nested questions, it may be best to choose to split your answers into separate annotations so that the nesting displays properly in your output file. For example, in an ‘Outcome Assessment’ category question asking ‘What behavioural tests are used?’, we would allow multiple answers and may choose to split into separate annotations’ as this allows us to ask further related questions to the specific behavioural test.

### Nesting Questions and Conditional Questions
Questions may be nested as ‘child’ questions to allow for hierarchy of conditional information entry (i.e., questions can become active, depending on answers to previous questions).

For each question you can choose to add related questions, if you want to get answers to additional questions, which are conditional on the answer to the previous question.

e.g., “What type of model is used?” (Drop down list with option of: Pharmacological or Surgical)

We could then add a related question by selecting “Add Related”, and in the form “conditionally display based on parent question”.

e.g., “What is the drug given?” (Drop down list with options of different drugs)

You could then ask further related questions, by clicking on this question and selecting ‘Add Related’ and asking for each drug selected: “What is the dose and route of delivery?” If Surgical is selected then we may ask the related questions: “What was the anaesthetic used?” or “What was the site of lesion?”.

These questions will nest under the previous question.

## Adding Questions to Stages
Once you have designed your questions, to allow them to be presented to reviewers, you need to add them to your annotation stage by going to ‘Stage Settings’ then the name of the stage of want to add your questions to and selecting the questions you want to add to the stage.


