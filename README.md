# Data science with Python 2022 #

## Predict football world cup2022 ##

### overview ###
It is a prediction project for the 2022 World Cup. How many goals will each team score and what is the average percentage of goals scored
The objective is to predict the goals scored by each team in the 2022 World Cup.

<img width="1088" alt="Screenshot 2566-10-17 at 19 44 34" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/84a5a3da-95ff-46c5-872b-ed1087e4d794">

#
* Tool
    * Anaconda
    * Jupyter lab
* Installation
    * Python v.3
    * Python libraries:
       * sklearn.
       * Pandas.
       * numpy.
       * seaborn.
       * matplotlib.
       * os.

# Methodology #

## Data understand 
Information taken [https://www.kaggle.com](https://www.kaggle.com)

as an Csv file
<img width="953" alt="Screenshot 2566-10-18 at 19 01 23" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/ff526fbd-3761-41fc-a087-dedb0b413044">

#
## 1. Check if any value is missing 
<img width="1058" alt="Screenshot 2566-10-18 at 19 09 10" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/89d0ac30-7b5f-4f3a-b7ba-bf32a14f7b65">
<img width="1055" alt="Screenshot 2566-10-18 at 19 34 54" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/8399462b-3800-4636-93c8-79fc87d300a5">
<img width="1052" alt="Screenshot 2566-10-18 at 19 37 55" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/c89e03e9-ed78-4a97-b5cb-7742a0b2469a">

#
## 2. The sum of 'score'for each team 
<img width="1057" alt="Screenshot 2566-10-18 at 19 39 36" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/82f6501d-c76c-484e-b791-6998f713f5d8">
<img width="1061" alt="Screenshot 2566-10-18 at 19 46 06" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/c93b5523-5cc6-4876-8571-bf6fc7317d80">
<img width="1050" alt="Screenshot 2566-10-18 at 19 52 24" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/d0b77b7d-bf14-40be-a5d8-b4c11b700f5c">

### Plotting
<img width="1056" alt="Screenshot 2566-10-18 at 19 48 48" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/c8de822a-2d82-487b-a7ec-c9758b0b9dc4">

#
## 3. The sum of 'score' inside the penalty area for each team 
<img width="1053" alt="Screenshot 2566-10-18 at 19 55 56" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/d70dffca-98d1-4f1f-84f8-0a85b84a78d8">
<img width="1052" alt="Screenshot 2566-10-18 at 19 56 56" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/1adeb0b7-326c-4e80-b24c-3a61581e9b8c">
<img width="1054" alt="Screenshot 2566-10-18 at 19 58 59" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/a4f6a765-c78c-4857-98af-8c3c74782ece">

### Plotting
<img width="1062" alt="Screenshot 2566-10-18 at 20 00 33" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/18b98cb5-665f-4d48-883b-b6614fe0bd5e">

#
## 4. The sum of 'score' outside the penalty area for each team
<img width="1055" alt="Screenshot 2566-10-18 at 20 02 27" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/07ad7425-38ed-4a88-aa76-8e52caae90e8">
<img width="1063" alt="Screenshot 2566-10-18 at 20 03 23" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/8f66db8b-347a-4073-88e1-8af8b500c4d5">
<img width="1055" alt="Screenshot 2566-10-18 at 20 04 08" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/58768a2b-1801-4827-9c85-f41fe54441b9">
<img width="1054" alt="Screenshot 2566-10-18 at 20 06 17" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/1d408dd9-b0d8-4827-87e6-8435d328091a">


### Plotting
<img width="1057" alt="Screenshot 2566-10-18 at 20 05 46" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/ec2fe2f7-f33a-47c4-8666-5be91cbf7a7e">

#
## 5. The sum of 'Yellow cards' for each team
<img width="1049" alt="Screenshot 2566-10-18 at 20 08 12" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/b64b7b1f-dbfd-4d15-975f-638689d6466c">
<img width="1065" alt="Screenshot 2566-10-18 at 20 09 44" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/94617318-49a2-4cf5-8d27-316881116410">
<img width="1069" alt="Screenshot 2566-10-18 at 20 10 22" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/7e777699-4c57-4da9-b954-9b2f5dc200a1">

#
## 6. The sum of 'Red cards' for each team 
<img width="1067" alt="Screenshot 2566-10-18 at 21 07 30" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/1381b2af-4e49-4d97-ad71-b183a53da429">
<img width="1062" alt="Screenshot 2566-10-18 at 21 09 28" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/69d4681c-9b36-47ac-887d-978759d94723">
<img width="1058" alt="Screenshot 2566-10-18 at 21 10 27" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/94fb090f-0eec-4a81-ad0d-07c3a18c1af2">
<img width="1055" alt="Screenshot 2566-10-18 at 21 17 38" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/3e62b0fb-2ffb-42f2-b1cd-c09e7f7032c4">
<img width="1050" alt="Screenshot 2566-10-18 at 21 18 16" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/57b23bae-5ec1-4a97-8142-546cb28d0b1f">


### Plotting
<img width="1065" alt="Screenshot 2566-10-18 at 21 12 24" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/fb014aa2-6104-4960-b314-bb222becdb93">
<img width="1061" alt="Screenshot 2566-10-18 at 21 19 42" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/3f8e30f2-aaca-4319-9ff7-24181b47945e">

#
## 7. The average of ‘attempts’ for each team








