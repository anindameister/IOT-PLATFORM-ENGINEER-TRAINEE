## intership offer

- IOT PLATFORM ENGINEER TRAINEE(Development of a Connected Health System)

Publication date : 10/12/2020
Location: Lyon, France
Full time, Internship 6 months
## ABOUT THUASNE

- A pioneer in #Medweartech, at the crossroads of medicine, materials and digital technology, 
- THUASNE has been creating and distributing medical devices for more than 170 years; 
- global and innovative solutions enabling everyone to become the actor of their own health. 
- Present in more than 86 countries through subsidiaries and distributors, our company (200 million euros in sales, 2,200 employees) has made innovation and patient comfort its priority.

# DESCRIPTION OF THE OFFER

- Attached to our Innovation Laboratory based in Lyon, 
- you will integrate the innovation team dedicated to the development of an IoT solution
- and will be under the responsibility of a Project Manager Engineer.

- The objective of the internship will be to participate in the implementation of an IoT platform 
- to manage connected objects on Microsoft Azure.

- You will have as main missions

- Elaboration of the architecture of the IoT platform
- Development of a **PoC** based on Azure IoT Central and/or IoT Hub
- Integration with the entire IoT system
# REQUIRED PROFILE

- In your last year of studies Bac +5 (engineering school or university type), you are looking for a 6-month internship and have a good knowledge in the development of an IoT platform to manage connected objects on the Cloud.

- You are interested in Microsoft Azure IoT technologies (Azure IoT Hub, Azure IoT Central).

- You have strong technical knowledge in C# development, and/or JS Node.

- You are aware of project development methodologies (Agile).

- This position is particularly suitable for candidates wishing to join a dynamic team focused on the technological development of a complex and multidisciplinary product within the innovation laboratory of a large company.

- Duration of the contract: 6 months

- Type of employment: Full time, Internship

- Salary: Up to €800.00 per month

## Advantages :

Participation in Transportation
Dining voucher
Schedules :

From Monday to Friday
Training:

Bac +5 (Master / MBA) (desired)
Language:

English (Desired)
Teleworking:

No
30+ days ago

# <a href="https://www.youtube.com/watch?v=XU0llRltyFM">Agile Methodologies<a/>

![Agile Methodologies](https://github.com/anindameister/IOT-PLATFORM-ENGINEER-TRAINEE/blob/main/snaps/1.PNG)

# https://docs.microsoft.com/fr-fr/azure/iot-central/healthcare/concept-continuous-patient-monitoring-architecture

## Continuous patient follow-up architecture
- This article describes the architecture of a solution built from the Continuous Patient Monitoring application template  
- You can build continuous patient monitoring solutions using the provided application template and using the architecture described as a <a href="https://docs.microsoft.com/en-us/azure/iot-central/healthcare/tutorial-continuous-patient-monitoring">guide</a>.

## Details
- This section describes each part of the architecture diagram in more detail:

### Iot device

- basic iot device

![Iot device](https://github.com/anindameister/IOT-PLATFORM-ENGINEER-TRAINEE/blob/main/snaps/2.PNG)

- iot device+radio+short/long range to reach a gateway+mqtt/coap/http/tcp/udp to reach cloud

![Iot device to cloud journey](https://github.com/anindameister/IOT-PLATFORM-ENGINEER-TRAINEE/blob/main/snaps/3.PNG)

### Bluetooth low energy medical devices (BLE, Bluetooth Low Energy)
- Many wearable-type medical devices used in IoT medical solutions are BLE devices. 
- These devices cannot communicate directly with the cloud and must use a gateway to exchange data with your cloud solution. 
- This architecture uses a mobile phone application as a gateway.

### Cell Phone Gateway
- The main function of the mobile phone app is to collect BLE data from medical devices and report it to IoT Central. 
- The app also guides patients through device setup and allows them to view their personal medical data. 
- Other solutions could use a tablet gateway or a static gateway in a hospital room. 
- A sample open source mobile app is available for Android and iOS, which you can use as a starting point for developing your app. 
- For more information, see the IoT <a href="https://docs.microsoft.com/fr-fr/samples/iot-for-all/iotc-cpm-sample/iotc-cpm-sample/">Central continuous patient monitoring mobile app </a>.

### Export to Azure API for FHIR®
- Azure IoT Central is HIPAA Compliant and HITRUST® Certified. 
- You can also send patient medical data to other departments using the <a href="https://docs.microsoft.com/fr-fr/azure/healthcare-apis/overview">Azure API for FHIR</a> . 
- Azure API for FHIR is a standards-based API for clinical medical data. 
- The <a href="https://docs.microsoft.com/fr-fr/azure/healthcare-apis/iot-fhir-portal-quickstart">Azure IoT Connector for FHIR </a>enables you to use the Azure API for FHIR as a destination for streaming data to export from IoT Central.

### Machine learning
- Use machine learning models with your FHIR data to generate insights and support decisions made by your healthcare team. 
- For more information, see the <a href="https://docs.microsoft.com/fr-fr/azure/machine-learning/">Machine Learning documentation </a>.

### Supplier dashboard
- Use data from the Azure API for FHIR to create a dashboard of patient insights
- or integrate it directly into an electronic medical record used by healthcare teams.
- Healthcare teams can use the dashboard to assist patients and identify early warning signs of deterioration.
- For more information, see the <a href="https://docs.microsoft.com/fr-fr/azure/iot-central/healthcare/howto-health-data-triage">Create a Power BI provider dashboard tutorial</a> .

### Following steps
- The next suggested step is to Find out <a href="https://docs.microsoft.com/fr-fr/azure/iot-central/healthcare/tutorial-continuous-patient-monitoring">how to deploy a continuous patient monitoring application template </a>.









# http://youtube.com/watch?v=xxv0b1DHmU4

# questions
1. DESCRIPTION OF THE OFFER:-Development of a **PoC** based on Azure IoT Central and/or IoT Hub
2. Cell Phone Gateway:-Other solutions could use a tablet gateway or a static gateway in a hospital room. 
