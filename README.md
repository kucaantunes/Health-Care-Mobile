# Health-Care-Mobile

![image](https://user-images.githubusercontent.com/26171557/187051778-0952d10f-3763-4d17-868b-6a1999cd1c0f.png)


![image](https://user-images.githubusercontent.com/26171557/187051782-58e31776-3809-4d8a-97db-069904d3aa59.png)


![image](https://user-images.githubusercontent.com/26171557/187051917-f4f49e93-5339-4e3a-a8f4-148a4f77ab21.png)


Pulse measurement of the fingerprints is one of the several functionalities of AI Care being a bit related with the heartbeat detection project. It is calculating also the number of heart beatings but instead of measuring above chest, it is measuring the pulse from the fingerprint. In case the readings are too different from these two places, the patient most likely is facing a situation of cardiac arrhythmia and should see his doctor.
The application should have an alarm system that triggers a contact to the correspondent medical institution according with the national emergency system of the country in case. The user has to place his finger on the phone camera for a few seconds and check if the light is on. The measurement process is different from the one used in the heartbeat via webcam. After getting the reading, the user can press a button on the mobile Java application that will send the information to the AI Care web application, that will add this value to his profile, store in the database and report on the system the readings obtained every time the clinical record is checked.
The technologies used for the mobile application were Java, Android Studio and APIs and concerning the web application was used PHP, MySQL and JavaScript mainly.
A website was developed to obtain the information obtained from the mobile phone using the open source PubNub API, allowing the verification of the data obtained by the mobile phone. The website shown in the figure above was made with HTML, JavaScript and CSS languages, using an API that allows the passage of information between the phone and the website. The developed mobile application in java reads the heartbeat via the phone and sends the information obtained to the website.
