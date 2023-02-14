---
sidebar: auto
---


# Training & Experiments Tutorials

This section seek a hub with the key learning skills in my research and development activities:

## Training Section

<MarkdownCard image="/MARL.jpg">

  Veiga, J. T., *et al* (2023)

###  **Multi-agent reinforcement learning (MARL)**

Intelligent agents and autonomous agents is a sub-area of artificial intelligence where these agents decide, in a reactive or proactive, about a course of action, reasoning on the available information about the world (including the environment, the agent itself, and other agents). In MARL, the RL is coupled aiming to share variables and parameters that will be considered requirements for model validation.

[[Cooperate](https://wa.me/+5511992451218)]

</MarkdownCard>

<MarkdownCard image="/MAOP.gif">

  Veiga, J. T., *et al* (2023)

###  **Multi-Agent Oriented Programming (MAOP)**

Agent-oriented programming (MAOP) was proposed in Boissier et al. (2013), seeking to support the MAS paradigm at the programming level. This technique is still a recent approach and they are usually used by tricks in traditional languages ​​such as Java, C++, Python, etc. In this material, I will talk a little about MAOP semantics, its challenges and I will present recent experiments for designing MAS scripts.

[[Cooperate](https://wa.me/+5511992451218)]

</MarkdownCard>

<MarkdownCard image="/DataAnalytics.gif">

  Veiga, J. T., *et al* (2023)

###  **Data analysis, processing and transformation**

Data analysis in the context of this work will be used for validation of models, generation of graphs and large amount of data from multiple simulations in parallel. It is expected in this project to analyze scenarios considering random planning, optimization of machine learning and deep learning techniques for agent feedback.

[[Cooperate](https://wa.me/+5511992451218)]

</MarkdownCard>

<MarkdownCard image="/DigitalTwin.jpg">

  Veiga, J. T., *et al* (2023)

###  **Digital Assets and Process Simulation**

- Aerospace simulations in the military context require detailed models and suitable for the study context,consequently the optimization of paths for air spaces,
can be treated as a complex problem, which involves different models for simulation, analysis and validation.
- In the Manufacturing Systems, was presented the digital twin (DT) as a virtual representation of an object or system, the models is updated from real-time data, and uses simulation, machine learning and reasoning to help decision-making. These cases it can be supported by both discrete event or continuous-time simulations.

[[Cooperate](https://wa.me/+5511992451218)]

</MarkdownCard>

<MarkdownCard image="/swArchitecture.jpg">

  Veiga, J. T., *et al* (2023)

###  **Software Architectures and Assets Models**

Modeling and Simulation (M&S) is widely used in the aerospace industry to create trusted components for analysis and data generation as close to the real environment.
In this project it is intended to advance in the studies and modeling skills acquired during the master's degree, however these are adequate for the study subjects, as for the modeling of dynamic behavior of assets, modeling of the simulation environment of other components, such as environments, components and others of importance for validation of the study hypothesis.

[[Cooperate](https://wa.me/+5511992451218)]

</MarkdownCard>

### Training 01 - Prediction of Species in Deforested Area

This material is a summary of Ebook-01 (Species Prediction for Reforestation in Deforested Areas) creates a fictitious case study on "Data Analysis" consultancy to generate a list of predictions for "Reforestation" of deforested areas.

* Context:
  > A certain company that monitors "Deforested Areas" consulted me to carry out a study regarding the presentation of solutions for optimizing the choice of "Protection Environments" and "Deforested Areas" based on a forecast that is based on the species of trees "Nearby".
  Based on the information received, I used the CRISP-DM method for construction and "STRUCTURING" of the solution in "Data Analysis" and "Generation of a POC" with first results.

* The method chosen to deal with the problem:

> a) Business Understanding: This initial phase focuses on understanding the objectives, then you can convert this knowledge into a problem for data mining.

  * a.1) Presented objectives: Generation of information for reforestation based on the population in the vicinity of the deforested area.

  * a.2) Conversion of knowledge into a problem to mine data:

> b) Data Understanding: The data understanding phase starts with an initial data collection and proceeds with activities for familiarization and understanding, identifying problems, checking data quality, discovering first insights, detecting interesting sets and FORMULATING HYPOTHESES.

> c) Data Preparation: Steps that precede the final construction of the "Poc Solution" - that is to leave the model input prepared - data that will be fed into the modeling tool from raw data. These tasks are executed in cycles until the desired result is obtained, including: Generating Tables, Registers, Selecting Attributes, Cleaning Data, Building New Attributes, Transforming data for the modeling tool.

> d) Modeling: In this step, "Modeling Techniques" are used, applications are selected, parameters to validate the idea. Modeling and data preparation are closely linked, at this stage problems such as missing data are perceived and "New Ideas for Model Construction" are generated.

> e) Validation: At this stage, the model has already been "Built" with good quality. Before implementing it is necessary to test, review the execution steps for construction so that it reaches the initial objective. It can be checked if there is any question that considers data from results and tests for decision making.

> f) Implementation: Creation of the model, end of the project, normally here the presentation of how to use the generated "artifact" is organized for customer orientation. Determine what actions will need to be taken to use the created templates.

* Use of the chosen method in the context of the presented problem:
    [[Buy Ebook](https://wa.me/+5511992451218)]

## Tutorial Section

### Example of Using the Decision Tree Algorithm in Python

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.5.1/katex.min.css">

<link rel="stylesheet" href="https://cdn.jsdelivr.net/github-markdown-css/2.2.1/github-markdown.css"/>

#### Brief Description:

This studies content puporses a experiment demonstration with summarized references about "Decision Tree Algorithm". It is expected that students or enthusiasts of these technologies will be able to replicate the tests and understand in a practical way about the presented technologies.


+ A decision tree is a tree structure similar to a flowchart where an internal node represents a resource (or attribute), the branch represents a decision rule, and each leaf node represents the result [1].


![DecisionTree](docs/.vuepress/public/DecisionTree.gif)


+ Decision tree is one of the predictive modeling approaches used in statistics, data mining and machine learning [2]. The figure above, "Decision Tree for Rain Forecasting", deals with a classic example where the "Highest Node - Initial" will be the initial data for sorting. Each of the nodes in the tree represents partitioning based on "choice attributes". This tree view happens recursively, allowing new internal nodes to emerge based on the dataset that will be tested.

+ In this example, we performed a demo that checks the probability of Sun or Rain, so the new "Humidity" and "Wind" nodes indicate decisive factors that describe weights on the arcs based on choice parameters. The nodes subsequent to the main node are called "leaves", ie (decision after simulating all features) and branches represent the decision rules or conjunctions of features that lead to the respective class labels [2].

#### Demonstrating a hands-on test with Python libraries:

##### i) Initially we will import some libraries in Python:

``` python
import matplotlib.pyplot as plt
from sklearn import datasets
from sklearn.tree import DecisionTreeClassifier
from sklearn import tree
```
  + [Matplotlib] is a software library for creating graphs and general data visualizations, made for and from the Python programming language and its NumPy math extension [3].
  + [Scikit-learn] is an open source machine learning library for the Python programming language [4], it has tools for data analysis, such as DecisionTreeClassifier - it is a class capable of performing multiclass classification on a dataset [ 5].
  + [Tree] allows you to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data resources.

##### ii) Importing the database for model training:

  + In this example we will use the Iris database. This is perhaps the best-known database found in the pattern recognition literature (See Duda & Hart, for example). This dataset contains 3 classes of 50 instances each, where each class refers to a type of iris plant [7].

``` python
iris = datasets.load_iris()
x = iris.data
y = iris.target
```
 + Then the data is passed in the DT classifier

 ``` python
cfl = tree.DecisionTreeCLassifier()
cfl = cfl.fit(x,y)
```
##### iii) Initial data view:

  + In this example, the proposal will be the visualization and first environmentalization with the Python libraries.

  ![DecisionTree](FIGURA com RESULTADO do TREINAMENTO)

  + Note that the Generated Tree intends to classify species according to "petal size" [8] and species count for each constraint found X =< size.
   + The code above tries to make the decision tree more interpretable by adding resource names [8].

  + After rounds and elimination of nodes, considering the suitable result, you can export the figure for presentation to project members.

##### iv) How to visualize decision trees using Graphviz (extra):

 + Graphviz is an open source graph visualization software. Graph visualization is a way of representing structural information such as abstract graph diagrams and networks. In data science, one use of Graphviz is to visualize decision trees [9].
 ![Gravitz](FIGURA com exportacao gravitz)

 + Gravitz is used in this experiment as a support tool to save the generated graph in .png. The code below will work on any operating system as python generates the dot file and exports it as a file called tree.dot[9]:

``` python
  import graphviz
  data = tree.export_graphviz(clf, out_file = None,
                              deature_names=iris.feature_names,
                              class_names = iris.target_names,
                              filled=True)
  graph = graphviz.Source(data, format='png')
  graph
```

### Discussions about the experiment performed:

Decision trees are widely used to solve classification and regression tasks. In classification problems, tree models categorize or classify an object using target variables containing discrete values. On the other hand, in regression problems, the target variable takes on continuous values ​​(real numbers), and tree models are used to predict outputs for unseen data [2]. This experiment will help you to know how to make a visualization based on your model, using the Iris database [7].

### If you liked this content, contact us:

I hope you enjoyed this content, we intend to improve the quality in the future, being open to possible partnerships. If you have difficulty replicating or achieving different results, please let me know.

I am available to collaborate on projects or carry out possible consultancy. Below where you can find me:

[[Know More](https://wa.me/+5511992451218)]

See you soon, Jackson T. Veiga

### References:

[1] https://www.spiceworks.com/tech/artificial-intelligence/articles/what-is-decision-tree/

[2] https://towardsdatascience.com/decision-tree-in-machine-learning

[3] https://matplotlib.org/

[4] https://scikit-learn.org

[5] https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html?highlight=decisiontree#sklearn.tree.DecisionTreeClassifier

[6] https://scikit-learn.org/stable/modules/tree.html

[7] https://archive.ics.uci.edu/ml/datasets/iris

[8] https://towardsdatascience.com/visualizing-decision-trees-with-python-scikit-learn-graphviz-matplotlib-1c50b4aa68dc

[9] https://graphviz.org/
