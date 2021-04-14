# ADS Project 5: 

Term: Spring 2021
+ Team # 1
+ Projec title: Predict the Default of Credit Card Clients
+ Team members
	+ Li, Qiao ql2403@columbia.edu
	+ Shu, Chuyun cs3894@columbia.edu
	+ Xia, Zhihang zx2338@columbia.edu
	+ Yu, Shuqi sy2950@columbia.edu
	+ Yuan, Serena sy2657@columbia.edu
	+ Zhang, Renyin rz2533@columbia.edu
+ Project summary: This research aimed at the case of customers’ default payments in Taiwan and compares the predictive accuracy of probability of default among different models. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. 
	
**Contribution statement**: ([default](doc/a_note_on_contributions.md)) All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 


**Note: models in bold were a focus of the contributor**
+ Li, Qiao: implemented managed communications; **SVM(fine-tuned), Weighted SVMs (fine-tuned)**; contributed to presenatation,edited final report, organization of Github files, Github ReadMes, and main.ipynb.

+ Shu, Chuyun:

+ Xia, Zhihang: Used smote method to deal with the imbalanced classes. Investigated/wrote codes of Decision Trees, Gradient Boosting with and without feature selection. Also used cross validations to tune the parameters of the three models. Wrote the content and results for my work in the final report and powerpoint.

+ Yu, Shuqi:

+ Yuan, Serena: wrote the methods for KNeighbors, SGD, MLP, LDA, and SVC models, with parameter tuning for MLP. Made EDA plots for the presentation and report, edited the final report.  Presented the presentation. 

+ Zhang, Renyin: Brainstormed about the topic and the scientific question, and found data scource online. Researched and implemented 4 different feature selection algorithms for dealing with imbalanced data. Edited the SMOTE method to just use on training set. Contributed to the presentation slide on feature selection and issue with imbalanced data.

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
