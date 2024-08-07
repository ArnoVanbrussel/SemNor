# 1 Introduction To AI (p.1)
## 1.1 What is AI? (p.2)
- Philosophically: What is intelligence?
- Optimistic def.: 
	- "The area of computer science that studies how machines can perform tasks that would normally require a sentient agent."
- Skeptical def.:
	- "The area of computer science that studies how machines can closely imitate human intelligence."
## 1.2 Why do we need to study AI? (p.3)
- Brain processes info (by increasing complexity):
	- Brainstem (Heart rate, body temp) => Midbrain (Motor regulation, appetite) => Limbic (Behaviour, Emotions) => Neocortex (Abstract thought)
- Raw data -> Intelligence (through processing:)
	- Data => Information => Knowledge => Understanding => Intelligence
		Processing         Cognition       Pattern Extraction       Inference
- 1 of main reasons to study AI:
	- Automate things
## 1.3 Branches of AI (p.5)
- Ways to classify:
	- Supervised learning vs. Unsupervised learning vs. Reinforcement learning
	- Artificial general intelligence vs. narrow intelligence
	- By human function:
		- Machine vision
		- Machine learning
		- Natural language processing
		- Natural language generation
- Common classification
	- Machine Learning and Pattern recognition
		- Most popular form of AI
		- Limited to power of data
		- Data => | Preprocessing, Training, Optimization| => Machine learning model
	- Logic-based AI
		- Mathematical logic
	- Search
		- Most optimal path of many options
	- Knowledge Representation
		- Ontology is closely related
		- Taxonomy or hierarchical structure
	- Planning
		- Max return with min cost
		- Start with facts about situation and a goal
	- Heuristics:
		- Trial & error
		- Solution may not be optimal
	- Genetic programming:
		- mating programs & selecting fittest
## 1.4 The 5 tribes of machine learning (p.8)
1. Symbolists
	- Induction (inverse deduction)
	- Start with conclusions and premises to fill in missing pieces

> Deduction: I am human + All humans are mortal => I must be mortal
> Induction: I am human + ??? = I am mortal => Humans must be mortal


2. Connectionists
	- Brain = primary tool
		- Neural networks
			- Type of algorithm designed to recognize patterns

3. Evolutionaries
	- Natural selection
	- Constant mutation, evolution and adaptation of algorithms

4. Bayesians
	- Handling uncertainty using probabilistic inference
	- "a priori" reasoning

5. Analogizers
	- Find similarities between examples
	- k-nearest neighbour algorithm
## 1.5 Defining intelligence using the Turing Test (p.9)
- Alan Turing
- Can interrogator be tricked into thinking that the answers are coming from a human?
- Interrogator and 2 Respondents (1 machine & 1 human)
- Machine needs at least:
	- Natural language processing
	- Knowledge representation
	- Reasoning
	- Machine Learning
- Total Turing Test: Vision & Movement rather than only intelligence
## 1.6 Making machines think like humans (p.11)
- Levels of thought
	1. Geometric
	2. Kinematic
	3. Physical
	4. Behavioral
	5. Cognitive
- Cognitive Modeling
	- Tries to understand how humans solve problems
	- Turn mental processes into software model

## 1.7 Building rational agents (p.12)
- Define Rationality?
	- Observing a set of rules and following their logical implications in order to achieve a desirable outcome.
- Input => | Sensor, Preprocessing, Agent Function, Actuator | => Action
- Performance based on degree of success?
	- This doesn't consider the actions leading to the result
- What in situation where no "right" options, agent must still do something

> Self driving car: crash into person, saving passenger, but killing person or crash into wall, saving person, but killing passenger?

## 1.8 General Problem Solver (p.13)
- GPS - Herbert Simon, JC Show and Allen Newell
- Same base algorithm for any problem
- New language: Information Processing Language (IPL)
- Only well-defined problems

## 1.9 Solving a problem with GPS
1. Define goals: 
	1. e.g.: get milk from store
2. Define preconditions: 
	1. to get milk from store, we need transportation
	2. store needs to have milk available
3. Define operators:
	1. if transportation is car and fuel is low => need to be able to pay petrol station
	2. also pay for milk

## Building an intelligent agent

