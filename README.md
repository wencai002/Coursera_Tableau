# Coursera_Tableau

##### 1. Executive Summary. 
* For this Coursera Capstone Project, since I am living in Europe, I decide to use the dataset "london bike sharing dataset" from kaggle.com. In order to analyse the use of the bike-sharing in europe countries. So that the providers know the need of their customer more precisely and are able to predict. As we all know, the new trend is coming up, since the introduction of sharing and platform by the use of APPs and Internet to connect people and service.
* So what will be the influencing factor of using the service? Do people tend to use the bikes more during the weekend or holidays? Or is it more because of the weather/temperature/humidity/wind?
* Here is the link for teh data: <https://www.kaggle.com/hmavrodiev/london-bike-sharing-dataset/version/1#>

##### 2. Why. 
* The goal of the project is to have find a way to:
  * predict the number of bikes being used given a certain circumstance
  * find out the correlation between the features in the dataset
  * give the stakeholder a suggestion with conclusion driven

##### 3. Who. 
* Lisa: Stakeholder. Vice president of the London Bike Sharing company.
  ###### Persona
  * She is majorly responsible for the saling and marketing department.
  * Goal --> Use sale data to understand the marketing and the customer needs. Good at selling products.
  * Challenge --> not good at statistik and math.
* Steven: Stakeholder. CEO of the London Bike sharing company. 

  ###### Persona
  * He and his soundboard together will attend the presentation hold by Lisa.
  * Goal --> know the company current situation and decides on the next steps.
  * Challenge --> does have enough time to listen to the report. 5 Mins is all you have. Make him understand what you are telling by     visualization.
* Kai: SME. Writer of this report.
* Sound-board: They are the audience.

##### 4. What.
* Data Quality is quite good. Over a period of more than 12 months, every single hour the data was recoreded. There are altogether 12 columns:
  * Timestamp: self-explanatory
  * Count: number of the bikes used at that particular timestamp
  * Temperature: self-explanatory
  * Temperature-feels: self-explanatory
  * Humidity: self-explanatory
  * Wind_speed: self-explanatory
  * weather code: a number which corresponds to a specific type of weather
  * is_holiday: boolean, self-explanatory
  * is_weekend: boolean, self-explanatory
  * season: on of the four season

##### 5. How.
* storytelling for Lisa
* single presentation for Steffen
  * X: vector of all the other features excluding number of bicycles
  * y: number of bicycles
  * Data preparation (incl. cleansing, train-test-valid separation)
  * Use PCA(Principal Component Analysis) to find out the important features.
  * Try to do a supervised learning to find the correlation and the best regression. 
  * Try to do an unsupervised learning to classify/cluster the data.
  * Use Tableau to do the visualization and present the result.

##### 6. Challenges.
* It can be that there is no strong correlation. Then we might need to use deep learning. Which will have the advantage of accuracy, but the result will be difficult to interpret.
* No enough time and effort to make the report easier to interpret.

