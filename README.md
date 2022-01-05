# -ESILV---Python-for-data-analysis---project-2022

 We have succeeded in creating a dataframe that is very easy to visualize in order to better understand and appropriate it
 Then we go from a dataframe that is not cleaned like this one:

![image](https://user-images.githubusercontent.com/91729640/148255999-2994c9b8-c3ba-419a-b851-7620fe1eee8d.png)

Has a dataframe that is perfectly readable to analyze the information it contains:

![image](https://user-images.githubusercontent.com/91729640/148274270-cbd95c9c-27cf-403c-a436-2048f84dfbd6.png)

So we manage to create a world map that lists the cases of use of drugs
![image](https://user-images.githubusercontent.com/91729640/148274573-0231cfc2-36c1-44cd-8647-3f728de7dd86.png)

We were able to create visualizations such as a graph taking into account the age, alcohol consumption and gender of individuals:
![image](https://user-images.githubusercontent.com/91729640/148274984-c8c9b9b0-92f3-459e-ab04-ec245869b4a4.png)

We also compared the parameter of education and ethnicity of the cases with their alcohol consumption:
![image](https://user-images.githubusercontent.com/91729640/148275381-3fdb107e-e821-469a-98e3-03154011cbb9.png)

## Legal Drug Use
### Vizualisations

Here are the most interesting visualizations of the legal drugs that we will analyze next:
![image](https://user-images.githubusercontent.com/91729640/148275688-26196540-7a6b-4f41-b770-df4643be4f6b.png)
![image](https://user-images.githubusercontent.com/91729640/148275709-66a03963-0b66-46bb-aa62-c6799a7b707f.png)
![image](https://user-images.githubusercontent.com/91729640/148275736-f48b0f79-ef24-4285-bd5a-880922d327cd.png)
![image](https://user-images.githubusercontent.com/91729640/148275749-5de47dce-d997-4e15-b583-45e1f20e0b7d.png)
![image](https://user-images.githubusercontent.com/91729640/148275788-05507629-8692-4a7a-8807-2a1ee6fa2acf.png)
![image](https://user-images.githubusercontent.com/91729640/148275807-df1a8d4e-c064-4478-869f-3fd54ce11d8d.png)
![image](https://user-images.githubusercontent.com/91729640/148275818-c4b7e8d0-1064-4dc0-a609-405130e3c9c4.png)
![image](https://user-images.githubusercontent.com/91729640/148275850-be1d03da-65ca-49ca-962d-aee36a97c875.png)

### Analysis & Conclusions 

Alcohol use showed a slight positive correlation with education level, such that higher education was associated with more frequent drinking. Specifically, those with a university degree or higher (i.e., master's or doctorate) drank the most alcohol. In addition, frequent drinkers tended to have higher impulsive sensation seeking (SS) scores, such that a majority of non-drinkers (never drank or drank more than a decade ago) had an SS score close to -1.0 while frequent drinkers (drank one week or one day ago) tended to have a score between 0 and 0.25.

Unlike alcohol, nicotine showed a marked difference in consumption between the sexes, with men consuming more nicotine than women. In addition, nicotine use was positively correlated with both the BIS-11 impulsivity score and SS. However, this relationship was slightly more pronounced in SS.

We examined the relationship between Benzodiazepine and various personality measures. Benzodiazepine use frequency showed a positive correlation with neuroticism (Nscore), impulsivity and SS scores. This correlation was strongest in the Nscores. These results align with other research that has suggested a relationship between benzodiazepine sensitivity and neuroticism with those with higher neuroticism showing higher sensitivity to Benzos 

Interestingly, there was a strong negative correlation between Nscore and Conscientiousness (Cscore). To better understand how this relationship was related to drug use, we examined nicotine and benzo use. Not surprisingly, those who used both nicotine and benzo tended to have higher Nscores and lower Cscores, while those who used no drugs had high Cscores and low Nscores

Translated with www.DeepL.com/Translator (free version)

Translated with www.DeepL.com/Translator (free version)

## Illegal Drug Use

### Vizualisations

Here are the most interesting visualizations of the illegal drugs that we will analyze next:
![image](https://user-images.githubusercontent.com/91729640/148276266-b39dc8c1-efe5-4ad2-8e6e-8fa8db1df27f.png)
![image](https://user-images.githubusercontent.com/91729640/148276286-56ea21a9-81f8-41ee-8f11-cab94da1e32e.png)
![image](https://user-images.githubusercontent.com/91729640/148276322-a63c4d3e-52fd-4ab6-a195-9bfdfded2785.png)
![image](https://user-images.githubusercontent.com/91729640/148276352-9e9db929-5b39-46a9-9374-c8af173663ca.png)
![image](https://user-images.githubusercontent.com/91729640/148276361-3d468841-08b9-4080-af7b-05ecb53f0a82.png)
![image](https://user-images.githubusercontent.com/91729640/148276372-57e306b3-fa5e-4278-8246-a8a77a1268b2.png)

### Analysis & Conclusions
In both cannabis and legal highs, men used the drug more frequently than women. In addition, the frequency of cannabis, legalh, and ecstasy use was negatively correlated with age, so that younger individuals used them more frequently than older individuals.

All illegal drugs were positively correlated with WS. Individuals who never or rarely used any of the illegal drugs showed SS scores of -0.5 to -1.0, while frequent users' scores ranged from 0.5 to 1.5. This relationship was most pronounced among legalh.

Cannabis, ecstasy, and mushrooms also showed a positive correlation with openness to experience (Oscore), with most occasional and infrequent users' scores ranging from 0 to -0.5 while the most frequent users had scores between 0.5 and 1.0.

Finally, I would like to emphasize how, given that the SS scores showed the greatest correlation with drugs, as a measure of personality, it may be the most robust measure for drug use and/or abuse. This personality score can help us better understand those individuals most at risk for substance abuse or addiction in general, which can provide physicians and therapists with a clearer and more nuanced understanding of this patient population.

## Predictions

In order to make our predictions, we need to determine whether or not each case in the dataframe is addictive or not in order to make a prediction afterwards. In the case of nicotine, for example, we have created a last column that presents by 1 or 0 the addiction or not of the person. This column is called Nicotine_User. We therefore create these four variables in the form of columns for each drug whose addicts we want to predict, i.e. for LSD, mushrooms, cannabis and methamphetamine.
![image](https://user-images.githubusercontent.com/91729640/148282996-355d564c-88fb-4328-b8b0-1cc78291a2e5.png)
![image](https://user-images.githubusercontent.com/91729640/148283008-760e8568-5227-4ad9-9530-e53e4f0589b2.png)
![image](https://user-images.githubusercontent.com/91729640/148283023-ae33a2bb-30d3-42a9-b92d-c3e80acc27f4.png)
![image](https://user-images.githubusercontent.com/91729640/148283036-4788a94a-25c7-4c51-a21f-def3614c2dea.png)

To predict we use four prediction algorithms: Logistic regression, Random Forest Classifier, Ridge Classifier and the Support Vector Machines. To classify the prediction algorithms we will take as a parameter the accuracy.


### Nicotine

Here is the accuracy of the different predictions :

![image](https://user-images.githubusercontent.com/91729640/148283281-53a9f2a2-2e97-4b5f-b5ec-eca5ff910da6.png)

We create the confusion matrix of the system that predicts the best (in this case Random Forest):

![image](https://user-images.githubusercontent.com/91729640/148283855-a6001e61-f70d-42fb-ac8b-e15582c9f073.png)

### Methanphetamine

Here is the accuracy of the different predictions :

![image](https://user-images.githubusercontent.com/91729640/148284317-279f8d28-6599-485f-b494-cfd96b237b8a.png)

We create the confusion matrix of the system that predicts the best (in this case Logistic Regression):
![image](https://user-images.githubusercontent.com/91729640/148284743-f9d28cbf-3d73-4886-9437-5868890b8d9e.png)

### Mushrooms

Here is the accuracy of the different predictions :

![image](https://user-images.githubusercontent.com/91729640/148284840-08bcc4bb-550d-4819-a152-c6594ffbd26a.png)

We create the confusion matrix of the system that predicts the best (in this case Random Forest):

![image](https://user-images.githubusercontent.com/91729640/148284949-b49d59df-f12c-49c4-82ab-71783267a965.png)

### LSD

Here is the accuracy of the different predictions :

![image](https://user-images.githubusercontent.com/91729640/148285253-a3e94ff1-9f0a-4dd8-9b5f-3a448711b671.png)

We create the confusion matrix of the system that predicts the best (in this case Ridge Classifier):

![image](https://user-images.githubusercontent.com/91729640/148285384-5fc0189a-0ba0-4c86-a881-4fcfe4569df2.png)

## Conclusions

In the end, we see that the Random Forest Classifier method is the best performing prediction method. A graph to visualize the prediction shows us where we can observe the accuracy of Random Forest:

![image](https://user-images.githubusercontent.com/91729640/148285813-733b4d39-1f96-446b-8e43-2585751afb07.png)

Some visualizations of these predictions show information that is consistent with our initial dataframe visualizations. Indeed, we notice in the graph below that Random Forest relies the most on the LSD parameter to make these predictions of mushroom addicts which is consistent with the correlation matrix of the dataframe where we notice that LSD and mushrooms are highly correlated:

![image](https://user-images.githubusercontent.com/91729640/148286055-175f1ca9-a41e-496e-8613-b5c61bd2d87b.png)

![image](https://user-images.githubusercontent.com/91729640/148286071-7475d011-98f0-4911-aa25-e235b1eff9db.png)




















