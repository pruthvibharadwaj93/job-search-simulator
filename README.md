# Job Search Simulator

Modeling the process of applying to jobs through the LinkedIn jobs section. 

***MOTIVATION***

The model's aim is to understand the job search process in a more systematic manner and to enable answering questions like

1. How long will it take for one to get a job offer when different strategies are adopted?
2. What is the uncertainty involved in the estimated timeline?
3. How does the job offer timeline change when application success rate or interview success rate drops?

***DESIGN***

I am assuming the different steps of the process (like no.of applications, application success rate etc) to be random variables (green blocks)
Each of the random processes will be modeled using a prior-posterior distibution pair whose parameters will be determined based on my experience. 
There will be an option to change these parameters so that it can generalise to someone else's experience. 
The overall structure of model is akin to a probabilistic graphical model.

A daily snapshot of the simulator design is displayed below


![Algorithm flowchart](https://github.com/user-attachments/assets/8e4b2f8e-63a2-47eb-8fc4-3d65aa2ed989)
