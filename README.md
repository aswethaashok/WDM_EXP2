### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### DATE: 13-08-2024
### NAME: SWETHA A
### REGISTER NUMBER: 212223220114
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

## Buying Table
![image](https://github.com/user-attachments/assets/5b6ca2e7-f81b-4bb5-9014-57e0c9f92072)

## Banking table
![image](https://github.com/user-attachments/assets/bef5d55b-1b91-48e8-ac62-4719ca82de4d)

## Employee table
![image](https://github.com/user-attachments/assets/6ceaecf4-a927-46d7-8225-0d7332a5088a)


### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:

## Buying Table
![image](https://github.com/user-attachments/assets/39443df2-4cee-423d-b24a-5b1295dfca18)

## Banking table
![image](https://github.com/user-attachments/assets/9f1b7b1a-4dc7-450e-8fa1-90caafb0aea3)

## Employee table
![image](https://github.com/user-attachments/assets/d5ef1b3f-bcdb-435e-aeec-4250fc9e2bc1)

### RESULT: 
Thus, generation of association rules using apriori algorithm is executed succesfully.
