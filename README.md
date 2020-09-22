# Ising-notes
Notes on Ising Networks for Deep Hierarchcical Reinforcement Learning

### Problem Formulation (Now)  
- What are you trying to solve? The alignment between hierarchies? Why is that an issue?  
- How can you demonstrate that this is a problem? Consider a toy problem and run tests on it. Identify the failure case arising due to hierarchies.  
- Upto what degree will the toy problem be significant to real world problems. A closer link between them is essential to convince the community.  

### Literature Draft (September)  
- Literature Review(3+ pages for Hierarchical Reinforcement Learning)  
- Review of Physics papers on Ising Simulations (3+ pages, it needs to be written in an intuitive way)  
- Introduction and Strenghts/Weaknesses of various approaches (not much work is done here so elaborate)  
- Short blog summarizing the capabilities of Ising Models  

### Toy Implementation (October-November)  
- Test on a toy problem (Mazelab and custom Gridworlds are a good choice)  
- Elaborate the details- Aim of the experiment, why this problem, setup, how was it done, what were the strenghts and weaknesses of the setting  
- Highlight the findings- First explain what has to been assessed and why. Then emphasize on results and their key findings, give an intuitive explanation, layout the details, etc.   

### Main Implementation (November-December)  
- Test on DM Control Suite, StarCraft II, Mazelab and Grdiworld  
- Elaborate the details- Clearly highlight the aim, why these problems, explain the setup, how were the experiments carried out, what were the strenths and weaknesses and any difficulties (must explain all the details for the implementation details section)  
- Highlight the findindgs- First explain what has to be assessed an why. Now emphasize on results and their key findings, give intuitive explanations, layout the details, etc. [You must not explain the images/tables but the reason for their occurence]  
- Comparison with SOTA- Rewards and increasing the number of hierarchies, completion rates, state visitations/distance covered, etc.  


### Ablation Study (December)  
- This needs to be detailed as the experiments/parameters are at large-scale.  
- Must highlight the following- what you wish to assess, what you are ablating, what did you oberve and why is this signficant w.r.t the algorithm.  
- Variation with temperature, variation with number of hierarchies, with and without Ising models, etc.  
- Spins achieved by hierarchies, distribution of rewards, distribution of spin states, time evolution of ising with time evolution of agent in environment, selection of spin states with actions, etc.  

### Intuition of Ising Models (December)  
- Intuition behind Ising Models- A deeper intuition is required from layman's point of view. Explaining the algorithm and findings may not help as the community is not aware of Ising Models. A seperate section on Intuition is essential for this purpose.  
- Illustrations of the model with proper reasoning for its usage, strenghts and weaknesses is essential.  

### Theoretical Treatment (December-January)  
- Mathematical justification of the model and its use in RL is essential.  
- Answer the following-  
  - Can the change in spin states quantify the change in decision/energy? More specifically, the system reaches thermal equilibrium with zero energy occuring from spins.  
  - Does the system converge to an optimal policy? If yes then is the optimal policy the one with minimum disagreements?  
  - How does the system guarantee to minimize disagreeements?  
  - What happens in the case of infinite hierarchcies? This is important since most practical problems consist of long sequences of hierarchies. Theoretically, the system must settle to thermal equilibrium at infinity as the large number of spin states lead to frequent disagreements and changes in spin values. [Quantify this]  
  - What is the net information gained by the system from minimizing disagreements? [Information Theory]  
  
### Draft Work (January)  
- Collect all the written portions into a single document in the form of a manuscript  
- Make sure to add everything that is relevant  
- The draft should be self-contained and highlight everything related to the details of the study  
- Edit and re-read to improve the language  




