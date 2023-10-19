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
<img width="1097" alt="Screenshot 2566-10-19 at 12 08 55" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/d3393f7d-240b-4385-be52-912a3d2d7342">
<img width="1104" alt="Screenshot 2566-10-19 at 12 10 55" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/4ab0f473-a665-41b1-bf7e-b4ae1e9f36e3">
<img width="1099" alt="Screenshot 2566-10-19 at 12 11 41" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/7988aea9-b455-4b35-aaba-67b21df46adc">


## Plotting
<img width="1102" alt="Screenshot 2566-10-19 at 12 14 10" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/3b46755d-2947-4f79-a6cb-885eddd9c036">

#
## 8. The average of ‘on target attempts’ for each team 
<img width="1102" alt="Screenshot 2566-10-19 at 12 28 41" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/4e574fb6-82ce-4003-97fd-f86b1b1d7b9b">
<img width="1101" alt="Screenshot 2566-10-19 at 12 29 48" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/13018528-78e3-4b5c-9786-fda562fbe55b">
<img width="1104" alt="Screenshot 2566-10-19 at 12 30 28" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/37f4b6a0-9605-44bf-82a2-6e9ef5a55822">


## Plotting
<img width="1099" alt="Screenshot 2566-10-19 at 12 32 02" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/92870eff-a0b6-4eb6-9711-6bcfe85622b1">

#
## 9. The average of ‘off target attempts’ for each team
<img width="1106" alt="Screenshot 2566-10-19 at 12 34 01" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/b0ee1f3b-bea8-478b-9102-3de039cbb2b6">
<img width="1104" alt="Screenshot 2566-10-19 at 12 34 56" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/7a181a8b-b37d-41f7-9710-e0cec08b5dd3">
<img width="1107" alt="Screenshot 2566-10-19 at 12 35 34" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/1101b855-b340-4d54-99a3-b087a0bb21ff">


## Plotting
<img width="1101" alt="Screenshot 2566-10-19 at 12 37 27" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/bb5ae3a8-ab6e-474a-a372-18510785d9ca">

#
## 10. The average of ‘attempts inside the penalty area’ for each team 
<img width="1105" alt="Screenshot 2566-10-19 at 12 38 56" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/2b3f6ac7-4a91-4acc-896e-ca1ef5506f75">
<img width="1108" alt="Screenshot 2566-10-19 at 12 39 38" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/6e4fc646-beb0-430b-960b-fa2d45071c7f">
<img width="1104" alt="Screenshot 2566-10-19 at 12 41 34" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/d0827152-7657-45dd-82ab-54a22b9f1c98">


## Plotting
<img width="1100" alt="Screenshot 2566-10-19 at 12 43 23" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/a47a0717-f7ca-4cba-a043-30d3b0d42314">

#
## 11. The average of ‘attempts outside the penalty area ’ for each team 
<img width="1102" alt="Screenshot 2566-10-19 at 12 44 41" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/3bb90b21-703c-4ca2-99de-af7a36d9f948">
<img width="1104" alt="Screenshot 2566-10-19 at 12 45 26" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/a6da053b-b79f-4825-ae35-9d24570e45f4">
<img width="1101" alt="Screenshot 2566-10-19 at 12 46 10" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/89dc65c0-056d-4a5e-8233-cd4451644bc3">


## Plotting
<img width="1091" alt="Screenshot 2566-10-19 at 12 48 06" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/59cd1338-5530-4298-9183-10775b1e9d41">

## The report the goals based on ‘category’
<img width="1104" alt="Screenshot 2566-10-19 at 12 55 43" src="https://github.com/hilmanyusoh/Fundamental_Data_Science/assets/118374893/a0b67d93-4332-4327-a330-1139087a9214">











