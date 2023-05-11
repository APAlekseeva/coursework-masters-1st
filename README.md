# coursework-masters-1st
Code &amp; input data for the 1st year coursework on master's programme

Topic: Modeling and Analysis of Processes in Online Assessment

Based on the output data (external-43799.xml) from programming contest, an event log will be generated. 
Output data contains the information about participants, tasks, submissions and their testing logs. 
Together, the analysis of the original data and the converted event log will help answer the following questions:

1. What are the patterns in the sequence of problem solving by the participants? 
2. What do the trajectories of problem solving look like for the most successful participants, that is, those who solved the largest number of problems? Is there something in common in the trajectories of unsuccessful participants?
3. At what points did the participants most often have difficulty in creating a successful submission? What actions led to their occurrence?

Three different types of event logs are considered:
1. Original data: all eight possible verdicts. No postfix in model names
2. "Soft" data: all verdicts, which are not returning directly "wrong answer", are considered as success. Postfix "soft" in model names
3. "Hard" data: all verdicts, which are not "OK", are considered as failure. Postfix "hard" in model names.

Two words about naming the models and files:
- model name contains its type (i.e. "dfg.png")
- for petri nets also the name of the miner is given in postfix: none for alpha or "ind" for inductive (i.e. "petri_net_ind.png")
- for non-original dataset its type is given in postfix (i.e. "process_tree_hard.png")
