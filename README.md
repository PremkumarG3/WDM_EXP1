### EX1- Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 07/08/2025
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
## Employee Data
<img width="1258" height="943" alt="Screenshot 2025-08-07 155551" src="https://github.com/user-attachments/assets/91f4f9dc-7ea7-40da-a5f1-8ea3d737de4a" />


## Weather Data
<img width="1259" height="946" alt="Screenshot 2025-08-07 155754" src="https://github.com/user-attachments/assets/c98be76e-75a0-4711-9a2c-a477b7153f61" />


### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
## Employee Data

<img width="1222" height="735" alt="Screenshot 2025-08-07 162209" src="https://github.com/user-attachments/assets/d1675b6e-d1fc-49b6-ad90-7b1e52358380" />

## Weather Data
<img width="1227" height="735" alt="Screenshot 2025-08-07 161936" src="https://github.com/user-attachments/assets/b2c69c7c-cec9-43a7-aff8-72da331b53b3" />


### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
## Employee Data
<img width="1223" height="731" alt="Screenshot 2025-08-07 162806" src="https://github.com/user-attachments/assets/5cfb9e02-02ea-4105-8875-db693e8021c7" />

## Weather Data
<img width="1223" height="731" alt="Screenshot 2025-08-07 162020" src="https://github.com/user-attachments/assets/70067b79-1c92-4bcf-b0d6-652349b8e7b5" />

### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
## Employee Data
<img width="1231" height="727" alt="Screenshot 2025-08-07 161207" src="https://github.com/user-attachments/assets/efdb66cf-e758-4bbd-9875-52ca9057a88c" />


## Weather Data
<img width="1222" height="731" alt="Screenshot 2025-08-07 162038" src="https://github.com/user-attachments/assets/b0c3acac-ae36-4784-9cad-0491613fb655" />

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
