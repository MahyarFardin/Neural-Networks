# Topic

In this project I tried to predict whether some people have stroke or not using neural networks.

# Features

- gender
- age 	
- hypertension 	
- heart_disease: whether they have hart disease of not 	
- ever_married: if they have ever married 	
- work_type 	
- Residence_type: if they live in inside or outside of the city
- avg_glucose_level 	
- bmi 	
- smoking_status 	
- stroke

# Brife explanation of notebook

- Fist I imported needed libraries for preprocessing and feature engineering
- Second I tride to explore dataset itself to get more information about columns, indexes and nulls
- Third I tried to visualize information that dataset containes to extract the correlations 
- Forth I got dummies(*I replaced non numeric variables with numeric ones*)
- Fifth I applied my keras model (**Neural networks**)
- As the most important part, at first I randomly throw some numbers as depth and 
length to start a network and analyse it to get more information and tune it at the next steps.
 Then I found that I have over fitted my model so I applied early stops to prevent model from
 proceeding in over fitted situation. Finally I added dropouts to remove some nodes randomly(* It both makes model faster and gives better result*)
 And as a last step I evaluated the model and tried to see whether I can get more accuracy or not.
 
**This was my first project so I did not know how to tune or choose a good number for nods and layers or other parameters**

# Feedback

If you have any feedback, please reach out to us at Mahyarfardinfar@gmail.com
