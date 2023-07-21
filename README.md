# Student performance Predictor.

This project tries to develop an end to end application that predicts a students particular subject marks based on certain decisive parameters and scores in other subjects.
The dataset used for this project had 1000 student data along with the following attributes.

<img width="355" alt="Screenshot 2023-07-21 134715" src="https://github.com/Genesis801/MLProject/assets/44739430/0a4f5bc1-56ac-44ff-b5a6-f03d2d084f99">

Extensive EDA was performed to find out the relationships between various attributes. And critical insights were gathered from the data.

The Demographics of the data is shown in the figure below.
![image](https://github.com/Genesis801/MLProject/assets/44739430/a6f309ea-f057-409b-9851-8ae52034f712)


First, an analysis was done to check the marks distribution between various genders.

![image](https://github.com/Genesis801/MLProject/assets/44739430/2addf3a7-94d1-4518-9c44-462bd4d4b9b6)

Inference was: Females tend to perform better than males.

Then, analysis was done based on the students lunch category, i.e how did students perform based on their standard lunch or free (subsidized) lunch.

![image](https://github.com/Genesis801/MLProject/assets/44739430/c09fd266-407b-4f9a-953b-2a9c00f19d00)


Inference was: Students with standard lunch plan performed better.

Then, Analysis was done to check how parental level of education plays a factor in Child's marks in an exam.

![image](https://github.com/Genesis801/MLProject/assets/44739430/54f44cc2-e0f4-441f-a905-2ff2bc82028a)

It was observed that parent's education level did not play a significant impact on the child's marks. But parents of male students who had a masters degree they performed better than the others.

Then we tried to analyze the marks of a candidates based on their race/ethnicity

![image](https://github.com/Genesis801/MLProject/assets/44739430/d742ad66-7293-44f1-96a3-3dc5a5768f1a)


Group E students have scored the highest marks. Group A students have scored the lowest marks. Students from a lower socioeconomic status have a lower avg in all course subjects.

Once the Exploratory Data Analysis Part was completed and the had an insight on the data. The Prediction model was built using modular programming approach.

<img width="960" alt="image" src="https://github.com/Genesis801/MLProject/assets/44739430/25d191fa-46f1-4398-b656-014da9fc2eea">

The app was built on a FLASK Boilerplate. And the user had the privilege to insert data in an interactive way. Here the maths marks were used as a test for the marks prediction goal.

<img width="960" alt="image" src="https://github.com/Genesis801/MLProject/assets/44739430/91122001-de03-4ae3-aa01-85cc76f1f430">

After inserting the data in a customized fashion the above figure shows how the output came for the project. The model accuracy obtained for the prediction task was 96.73%.
The entire Application was then deployed using AWS Elastic Beanstalk and a continuous Deployment pipeline was created using AWS Codepipeline.


