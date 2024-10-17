


# Detection of Air Contamination using NodeMCU

This project implements a system to monitor and detect air contamination using the **NodeMCU** and **MQ-135 sensor**. It measures harmful gases such as CO, smoke, benzene, and NH3, and triggers an alarm via a mobile app when the air quality reaches unsafe levels. The system is designed to provide real-time air quality data using **IoT** technology.

## Features
- **Real-Time Air Quality Monitoring**: Detects various harmful gases like CO2, smoke, benzene, and NH3 using the MQ-135 sensor.
- **IoT-Enabled System**: The system uses **NodeMCU** with built-in Wi-Fi for seamless data transmission.
- **Mobile App Alerts**: Sends alerts through a mobile app when gas levels exceed safe thresholds.
- **Cloud Storage**: Stores sensor data on **ThingSpeak**, an IoT analytics platform, for visualization and analysis.
- **Low Cost and Efficient**: Designed to be affordable, efficient, and easily deployable for air quality monitoring in various environments.

## Technologies Used
- **NodeMCU**: An open-source IoT platform with built-in Wi-Fi, used for handling data transmission.
- **MQ-135 Sensor**: Detects harmful gases and pollutants in the air.
- **ThingSpeak**: A cloud-based platform to collect, store, and visualize sensor data.
- **Android App**: The mobile application displays real-time data and triggers alerts based on gas levels.

## Components
- **NodeMCU (ESP8266)**: The main controller that connects to the internet and communicates with the server.
- **MQ-135 Gas Sensor**: Used to measure levels of harmful gases.
- **Buzzer**: Sounds an alarm when the gas levels exceed safe limits.
- **Mobile App**: Displays the air quality data and sends notifications to users.
- **ThingSpeak**: A web service that logs data from IoT devices.

## How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/air-contamination-detection-nodemcu.git
   ```
2. **Set Up NodeMCU and MQ-135 Sensor**: Connect the MQ-135 sensor to the NodeMCU.
3. **Upload the Code**: Use the Arduino IDE to upload the provided code to the NodeMCU.
4. **Monitor Air Quality**: View real-time data on the mobile app or ThingSpeak dashboard.
5. **Receive Alerts**: Get notified via the mobile app when air quality reaches dangerous levels.

## Future Work
- **Additional Sensors**: Integrate more sensors to detect other gases like O2 and H2.
- **Enhanced Mobile App**: Add features like historical data analysis, additional graphs, and real-time notifications.
- **Extended Deployment**: Test the system in various environments for broader applications in smart cities and industrial monitoring.

## Contributors
- **K. Gogulnath** - Team Leader
- **Ajith Kumar S.** - Team Member

