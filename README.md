
<h1 align="center"> 🦠 Random Walk Analysis 🦠 </h1>

This was a data analysis heavy experimental physics project I did during my last semester of undergrad. I observed and recorded videos of particles with a microscope (shown below) in luquid and tracked the coordinates over time. I performed statistical data analysis to experimentally determine Avogadro's Number ( $6.02 \times 10^{23}$ mol $^{-1}$). I tracked 1µm polystyrene in 3 solutions: water, 10% & 25% concentration glycerol. I was able to replicate the Nobel Prize winning experiment performed by Jean Perrin, who was awarded the Physics Nobel Prize in 1926 for this work. 🥇 <br>

### ⬇️ Snipshots of the particle I recorded & tracked ⬇️

<p float="left">
  <img  width="350" height="250" src="https://github.com/hina0830g/portfolio/blob/main/Portfolio_images/particles.gif"/>
  <img  width="350" height="250" src="https://github.com/hina0830g/portfolio/blob/main/Portfolio_images/glycerol.gif.gif" /> 
</p>

(Pretty cool, right?)


<h2 align="center"> Code </h2>

- [**Brownian_Analysis.ipynb**](https://github.com/hina0830g/Random_Walk_Analysis/blob/main/Brownian_Analysis.ipynb)
General analysis of the tracked coordinates Reads arrays of coordinates and calculates the distances the particle traveled + mean squared displacement. This code also visualizes the path and the movement of the particle in the liquid and runs liner regression on mean squared displacement (function of time, in seconds). 


<h2 align="center"> Results / Conclusion </h2>

The summary is explained in my [final presentation](https://docs.google.com/presentation/d/1zoPF6esKpLIvcKp6EGz1OubzBa34gI1Ysxdli4kYFGo/edit?usp=sharing), with further data analysis along with error analysis is available in my [project report](https://drive.google.com/file/d/1kL2-4DdOWwz1NXxwDG3-ltJBXtw6vsh3/view?usp=drive_link). Using 3 solutions, The value of Avogadro's number I found was $(1.34 \pm 0.03) \times 10^{24}$ mol $^{-1}$.
