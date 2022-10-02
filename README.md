# The square barrier potential

This repository contains examples of the content I would include in a second year quantum mechanics course. This specifically focuses on the problem of the square barrier potential.  

I believe the material should be 
- **Modern:** utlise up-to-date tools such as python to enhance learning.
- **Mixed media:** ensure that a range of materials are provided.
- **Heuristic:** give students the change to actively learn

## Preparation work
Students would be expected to prepare for their class ahead of time. This would include reading class notes, watching explantory videos and reading specific sections from course textbooks.
For this example I have chosen to begin the notes with the slightly simpler problem of the *step potential*, before moving on the the square barrier potential. I felt this introduces some of the concepts in a simpler system, so that once the students learn about the square barrier potential they are more well prepared. 


### 1. Course notes
An example of the course notes can be found here:


These aim to provide an overview of the relevant material that the students need in order to understand the topic. These are not intended to be completely comprehensive and should be complemented by reading specific chapters in the course textbooks. The notes are interspersed with a number of 'show that' questions that the students would complete as they go along. 

### 2. Videos
The notes would be complemented by a series of short video recordings explaining the scenarios. By doing this I would hope to cater for students who prefer different learning styles.
Examples can be found here: 

{% include googledrive.html id="1Hd7VVBoTSidZaURqUqa3Gv0nWKAU2EIN" %}


### 3. Background reading 
Students would be expected to read relevent sections in the course textbooks to help prepare them from the interactive session.

## Interactive session  
The interactive session would be undertaken with a lecturer and 

### 1. Small groups discussion
First students would discuss how they got on with the questions in the course notes in small groups. They would be encoraged to take it in turns to explain to each other how they solved each question, and flag up any problems they encountered. The lecturer and teaching assisant would be on hand to assist. 

### 2. Interactive demonstration 
Whilst the students will have seen the relevant course material at this point, the implications of the results may not have sunk in. In this section the students use an interactive display of the wave function solutions in a range of scenarios and are encoraged to explore how the solutions change in different regions of the parameter space. 

I have created stand-alone interacive implementations of the solutions to the step potential and square barrier potential in a jupyter notebook. This notebook is also interspersed with questions that encorage the students to think about how the parameters affect the solutions.
The Jupyter notebook can be found [here](https://github.com/TomHadavizadeh/TeachingExample/blob/master/Square_potential_barrier.ipynb) to run on your own computer or can be run online using binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/TomHadavizadeh/TeachingExample/HEAD?labpath=Square_potential_barrier.ipynb)


### 3. Applying the solutions to real problems

This section would apply the solutions to the schrodinger equation to a range of more real-life scenarios to give context to the results.

- Calculating the transmission probability of different mass particles through a fixed barrier width, e.g. electron vs. proton vs. macroscopic particle
- Scanning tunnelling microscopes: 
- Micro electronic circuits: at small scales circuits can be limited due to electrons tunnelling out of the circuits. This example would get students to calculate at what barrier widths this may become important.
- Simple model for Alpha decay: Radioactivate alpha decay can be modelled as an alpha particle sitting in a well, surrounded by a barrier created by the coulomb repulsion. Due to the shape of the potential, the amount of barrrier a particle has to tunnel through depends on it's energy. Students would try to estimate how the tunneling probability varies as a function of the alpha energy, and put this in the context of the huge differences in half life as a function of alpha energy.    

<!-- {% include youtube.html id="EMq_QbyghMU" %} -->


