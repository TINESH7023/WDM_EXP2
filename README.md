### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### DATE: 
### AIM: To generate associate rules for the employee dataset using Apriori Algorithm.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:
### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

```
@relation buying
@attribute age {L20,20-40,G40}
@attribute income {high,medium,low}
@attribute stud {yes,no}
@attribute creditrate {fair,excellent}
@attribute buyscomp {yes,no}
@data
L20,high,no,fair,yes
20-40,low,yes,fair,yes
G40,medium,yes,fair,yes
L20,low,no,fair,no
G40,high,no,excellent,yes
L20,low,yes,fair,yes
20-40,high,yes,excellent,no
G40,low,no,fair,yes
L20,high,yes,excellent,yes
G40,high,no,fair,yes
L20,low,yes,excellent,no
G40,high,yes,excellent,no
20-40,medium,yes,excellent,yes
L20,medium,yes,fair,yes
G40,high,yes,excellent,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:

Buying

![305724398-2f1617ee-3b8b-4949-b559-84d13dddd2a3](https://github.com/JaisonRaphael/WDM_EXP2/assets/94165957/82681429-a685-41a3-81a5-0f1295f16b88)

Banking

![305724436-266846bb-2880-480e-adc4-890296873b17](https://github.com/JaisonRaphael/WDM_EXP2/assets/94165957/8846c6b0-0b66-46fc-beed-40ba08256f0a)

Employee

![305724571-56b295a7-e46b-4de7-9ea3-b5a0a33c46b5](https://github.com/JaisonRaphael/WDM_EXP2/assets/94165957/e6487cb2-091c-4f40-a5ac-c1f1989d419b)



### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:

Buying

![305724610-0022d356-e579-46e1-b924-9e1082c7ad2f](https://github.com/JaisonRaphael/WDM_EXP2/assets/94165957/68fc1a7c-5c8e-4117-b76f-c0267f5399b3)

Banking

![305724635-50c20e96-1339-4eab-8bb2-01aa447ede07](https://github.com/JaisonRaphael/WDM_EXP2/assets/94165957/5012ccf2-db4d-48e0-8d84-67b2c53710b7)

Employee

![305724653-56610c1b-150b-4a63-b76f-6863f802def4](https://github.com/JaisonRaphael/WDM_EXP2/assets/94165957/3a3823ea-0f8d-4d58-ad0c-c5ce52e0dd80)


### RESULT: 
Thus, generation of association rules using apriori algorithm is executed succesfully.
