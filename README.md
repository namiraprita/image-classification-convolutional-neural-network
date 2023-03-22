# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Spring 2023

+ Team 3
+ Team members
	+ Li, Yuanxi yl5127@columbia.edu
	+ Suniaprita, Namira ns3646@columbia.edu
	+ Zhang, Chenbohan cz2738@columbia.edu
	+ Zhang, Jingshu jz3552@columbia.edu
	+ Zhang, Zerui zz2999@columbia.edu

+ Project summary: The project involved developing two image classification models in the presence of noisy image labels. The team's efforts resulted in two models: Model I, where we evaluated multiple CNN models, including ResNet50 and Inception V3, and eventually chose Inception V3 due to its computational efficiency and accuracy. For Model II, we implemented weakly supervised learning using Inception V3 to correct labels and improve precision using accurate labels, given Inception V3's satisfactory performance and optimized training time and memory. Overall, the team observed a significant enhancement in accuracy.


**Contribution statement**: ([default](doc/a_note_on_contributions.md)) All team members approve our work presented in this GitHub repository including this contributions statement. 

+ Yuanxi Li is responsible for tunning the hyperparameters for InceptionV3 models to improve model accuracy and evaluating model performance on the test labels.
+ Namira Suniaprita developed and trained two models, Model 1 and Model 2, using the InceptionV3 architecture, and evaluated their performance on the test labels.
+ Chenbohan Zhang developed the model2 based on Jingshu's model 1 using method from Inoue et al.(2017), and is also responsible for presentation.
+ Jingshu Zhang is responsible for pre training ResNet50 for image classification.
+ Zerui Zhang helped developing model 1 and tunning the hyperparameter, and helped check to improve accuracy.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
