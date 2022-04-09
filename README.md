# DrivenData-DengAI-Predicting-Disease-Spread
DengAI: Predicting Disease Spread

Source : https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/page/80/

**Can you predict local epidemics of dengue fever?**

![alt text](https://d1vbn70lmn1nqe.cloudfront.net/prod/wp-content/uploads/2021/06/27064803/Demam-Berdarah.jpg.webp)

Dengue fever is a mosquito-borne disease that occurs in tropical and sub-tropical parts of the world. In mild cases, symptoms are similar to the flu: fever, rash, and muscle and joint pain. In severe cases, dengue fever can cause severe bleeding, low blood pressure, and even death.

Because it is carried by mosquitoes, the transmission dynamics of dengue are related to climate variables such as temperature and precipitation. Although the relationship to climate is complex, a growing number of scientists argue that climate change is likely to produce distributional shifts that will have significant public health implications worldwide.

In recent years dengue fever has been spreading. Historically, the disease has been most prevalent in Southeast Asia and the Pacific islands.

**Problem description**

Your goal is to predict the **total_cases** label for each (**city**, **year**, **weekofyear**) in the test set. There are two cities, **San Juan** and **Iquitos**, with test data for each city spanning 5 and 3 years respectively. You will make one submission that contains predictions for both cities. The data for each city have been concatenated along with a city column indicating the source: sj for San Juan and iq for Iquitos. The test set is a pure future hold-out, meaning the test data are sequential and non-overlapping with any of the training data. Throughout, missing values have been filled as NaNs.
