#AgriSense: Precision Farming Companion

•	To implement precision agriculture (A modern farming technique that uses research data of soil characteristics, soil types, and crop yield data collection and suggests the farmers the right crop based on their site-specific parameters to reduce the wrong choice on a crop and increase productivity).
•	To implement automation of irrigation of crops through Arduino controlled IoT device.
•	Pest detection through PIR sensor.
•	To recommend optimum crops to be cultivated by farmers based on several parameters and help them make an informed decision before cultivation.
•	To recommend fertilizer and pesticide on the basis of N, P, and K values and crop.

Methodology: The project consists of two phases: Automation and machine learning. 

For Automation, we will be using IoT methodologies to automate water-based irrigation of plants when needed. We will be using arduino embedded system (uno r3) for control unit. Sensors such as soil moisturizer, temperature and humidity sensor, and if budget allows, ph sensor, npk soil sensor will also be used for collecting a vast variety of data. Arduino will then be used and programmed to control the flow of water. If moisture level drops below a certain point, a dc motor or a pump will be accelerated to provide water until the level normalizes. This automation will help farmers in automation of water irrigation based on the need and will greatly impact water ecosystem in low water resource area.
Including the aforementioned IoT application, what is further added on in here is a system used to detect the motion of predators using PIR sensors which utilise the detection of infrared that is radiated from all objects that emit heat. This type of emission is not visible to the human eye, but sensors that operate using infrared wavelengths can detect such activity. 

The data collected from the sensors will then be used and fed into a machine learning model that has been trained on existing record of suitable conditions, i.e. the pre-acquired dataset for crop yield, to help farmers use technology as a means for precision farming. The ensembling techniques used in here for model training and creaking the .pkl file are SVM, Random Forest, GradientBoostingClassifier, and KNN respectively. This data will also be used to recommend fertilizers, pesticides and crops for different soil type and conditions. In case of crop recommendation application, the user can also provide the soil data on their own and the application will predict which crop should the user grow.

Feature engineering and hyperparameter tuning will be used to estimate appropriate model and its parameters for performance efficiency.
