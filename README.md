# AI-models-for-bug-prediction

## Introduction:
Software Bug Prediction is an important issue in software development and maintenance processes, which concerns with the overall of software success.   This is because predicting the software faults in earlier phase improves the software quality, reliability, efficiency and reduces the software cost. Bug prediction also involves risk analysis, quality of code  etc.

-------------------
## Research and discussed methodologies or approaches:
In this project, Different approaches are studied and discussed. Some of them are:<br>
1. Performance Analysis using Software features at Component(file) level:
2. Rule based approach for Quality of a Software.
3. Bug prediction at method level
4. Bug prediction using Abstract syntax tree(AST)
5. Risk code analysis Using Control flow graph(CFG)
6. Vulnerabilities detection in Software
7. Predicting Bug risk with git metadata
8. Bug hotspots based on commit history.

---------------

## Software metrics or features description:
 A software metric is a measure of software characteristics that are quantifiable or countable. It includes McCabe metrics, Halstead features , simple static code measures.
 REFER:
 --------------
## Packages Used:
- Different packages are explored in this project such as pycallgraph, radon, multimetric, gitrisky etc..
- Radon and multimetic comes handy for extracting software metrics from the software repository.
- ---------------

## Proposed Work or approaches:
In this project, we evaluate some approaches such as
a.Software bug prediction at component level.
b.Rule Based approach for bug prediction
c.Bug prediction based on git commits and metadata.
d.Software vulnerability detection for Risk Analysis.
### a.  Software bug prediction at component(file) level:
- Software code is composed of several components. If we know which components are likely to be defective, we can increase testing cost-effectiveness.
- In this approach, predictive models can be created to identify components likely to be defective by using past software releases and bug fixes as training data for learning machines.
- REFER
### B. Rule Based approach for bug prediction:
- In this approach, software features or metrics are calculated and sets some threshold values to those metrics and checks whether the values are present in acceptable range for successful project. Otherwise, it needs to be redesign.
- According to Halstead features,
 	 if a software is successful if its 
  		1. Halstead total operators + operands n < 300
  		2. Halstead Volume < 1000
  		3. Halstead difficulty < 50 
 	 	4. Halstead efforts < 500000
           5. Halstead time < 5000,     
Otherwise, it needs to be redesign
- REFER: 
### C. Bug prediction based on git commits and metadata:
- Git tracks changes to a codebase as a series of ‘commits’.
- we can utilize git utilities such as git log, git diff, git blame.
- We identify all commits which fix bugs and figure out what each bugfix commit modified
- REFER:
### D. Software vulnerability detection for risk analysis:
- vulnerabilities can pose serious risk of exploit and result in system compromise, information leaks, or denial of service. 
- The idea is to detect CWE(Common Weakness Enumeration) by leveraging labelled large dataset
- we tokenize the program that need to be tested to feed to the model.
- REFER: 
## ISSUES TO CONSIDER:
- Class imbalance
- Data Availability
- Dimensionality Curse
- Temporal behavior
<b> We solve these isses by possible fixes</b>





REFER - 
## Usage


-----------------
## Features:
- Support multiple programming languages
- Easy to run python notebook file
- Trained to model is targeted for specific software or developer.


## Results and conclusion:
- The Bug prediction project used to predict the likelihood of bugs in a project but it does not guarantee it.
- There is no single approach or solution that can applicable to any situation.
- Software bug prediction at component level is more reliable because it depends on historical data of a specific software. 
- Finally, There is no universal solution for bug prediction for all projects. Every software has its own implementation and functionalities. And every developer has their own style of writing code. So bug prediction model can be trained targeting a specific software or a developer.


-----------------------
### Developer
- Prudhvi (TCS Intern)

------------

### Authorization
###### Tata Consultancy Services

