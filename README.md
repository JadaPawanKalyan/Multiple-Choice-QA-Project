# Multiple-Choice-Answering
This model is a question answering model, based on multiple choices. Given a question and a possible set of answers, choose the correct one. Traditional Machine learning techniques use a inefficient approach of sending each answer and question to the model and getting the probability score and then selecting answer with the highest score. Here for each question we have to run the model multiple times.
So, this is an architecture which in one pass of the model gets the answer. I treated this a Question Answering system but here we limited our answer space. So I used an approach to encode to all the answers into a single entity and gave the model, which is able to identify the correct using a start token and the end token. The text lying between them is the answer.

# Output
What cause many human diseases by killing host cells or disturbing their homeostasis? <br />
Choice 1: parasites <br /> 
Choice 2: bacteria <br />
Choice 3: viruses <br />
Choice 4: cancer <br />
Correct Answer: viruses <br />
Predicted answer: viruses <br />
<br />
What kind of model - which includes producers, consumers and decomposers - shows the interactions between organisms across trophic levels? <br />
Choice 1: fuel web <br /> 
Choice 2: interdepence web <br />
Choice 3: food web <br />
Choice 4: organic web <br />
Correct Answer: food web <br />
Predicted answer: food web <br />
<br />
What are the organisms that live in extreme conditions known as? <br />
Choice 1: naturophiles <br /> 
Choice 2: extremophiles <br />
Choice 3: carotenoids <br />
Choice 4: fibroblasts <br />
Correct Answer: extremophiles <br />
Predicted answer: extremophiles <br />
<br />
What are ectothermic vertebrates that divide their time between freshwater and terrestrial habitats? <br />
Choice 1: reptiles <br /> 
Choice 2: mammals <br />
Choice 3: amphibians <br />
Choice 4: arthropods <br />
Correct Answer: amphibians <br />
Predicted answer: amphibians <br />
