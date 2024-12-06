

# IoT-Based Recirculatory Aquaculture System for Water Quality Management

This project presents an **IoT-based Recirculatory Aquaculture System (RAS)** for efficient and sustainable water quality management in aquaculture. The system employs a combination of sensors, data analytics, machine learning, and automation to optimize aquaculture practices and ensure the health and productivity of aquatic life.

## Abstract

Global warming and its effects on agriculture have led to the rise of aquaculture as an alternative livelihood for farmers. However, challenges in managing water quality often hinder success. This project aims to address these challenges using an IoT-driven system that automates monitoring and management processes to maintain optimal water conditions.

### Key Features
- **Sensors**: Monitors pH, turbidity, temperature, and TDS levels in real time.
- **Automation**: Automated filtration, aeration, and water circulation to maintain quality.
- **Data Analytics**: Sensor data is analyzed using machine learning (quadratic regression) to predict dissolved oxygen levels.
- **Cloud Integration**: Data is transmitted to the ThingSpeak platform for real-time visualization and analysis.
- **User Interface**: A local application built with React, Node.js, and MySQL provides real-time monitoring and controls.

## System Architecture

1. **Physical Design**:  
   - Sensors: pH, TDS, turbidity, and temperature.  
   - Actuators: Oxygen pumps, water pumps, and filters.
   - Microcontroller: Arduino Mega for data collection and control.

2. **Network Design**:  
   - Sensors integrated with the Arduino Mega using I2C communication.  
   - Wi-Fi module (ESP8266) for data transmission to the cloud.

3. **Logical Design**:  
   - React-based GUI for real-time monitoring and visualization.  
   - Node.js and MySQL backend for data processing and storage.  
   - Communication: REST APIs and MQTT protocol.

## Data Analytics

- Machine learning models predict dissolved oxygen levels to preemptively identify potential issues.  
- Insights generated from sensor data aid in optimal system operation and water management.

## Experiment and Results

- The system was tested under varying conditions to validate performance.
- Parameters like TDS, pH, and temperature were effectively managed within optimal ranges.
- Results demonstrated improved fish health, water quality stability, and sustainable aquaculture practices.

## Tech Stack

- **Hardware**: Arduino Mega, ESP8266, sensors, and actuators.
- **Software**:  
  - Frontend: React, Chart.js  
  - Backend: Node.js, MySQL  
  - Cloud: ThingSpeak  
  - Machine Learning: Quadratic regression for DO prediction

## Links and Media

- **Research Paper**: [IoT-Based Recirculatory Aquaculture System](https://drive.google.com/file/d/1HV-2MJIcpb7T-Jt412H4ThOhSRyXHhsM/view?usp=sharing)
- **Demo Video**:  
  Watch the system in action on [YouTube](https://www.youtube.com/playlist?list=PLvIKovsEUP5oEnbTDDrP6dU-rE4tYMDMv).  

## Screenshots

### 3D Model
![System Overview](https://github.com/deveshanurag/EDP-IOT-Based-RAS-System-for-Water-Quality-Management/blob/main/edp-pic/4.png)
![System Overview](https://github.com/deveshanurag/EDP-IOT-Based-RAS-System-for-Water-Quality-Management/blob/main/edp-pic/5.png)
![System Overview](https://github.com/deveshanurag/EDP-IOT-Based-RAS-System-for-Water-Quality-Management/blob/main/edp-pic/7.png)

### Sensors
![Sensor Data](https://github.com/deveshanurag/EDP-IOT-Based-RAS-System-for-Water-Quality-Management/blob/main/edp-pic/fig-3-sensor.jpg)

### Edge Devices
![Edge Devices](https://github.com/deveshanurag/EDP-IOT-Based-RAS-System-for-Water-Quality-Management/blob/main/edp-pic/fig-1-edge.jpg)

### Filters
![Filters](https://github.com/deveshanurag/EDP-IOT-Based-RAS-System-for-Water-Quality-Management/blob/main/edp-pic/filter.jpg)
![Filters](https://github.com/deveshanurag/EDP-IOT-Based-RAS-System-for-Water-Quality-Management/blob/main/edp-pic/sponge%20filter.jpg)

### Real-Time Dashboard
![Dashboard](https://github.com/deveshanurag/EDP-IOT-Based-RAS-System-for-Water-Quality-Management/blob/main/edp-pic/WhatsApp%20Image%202024-05-06%20at%2022.54.58_44a01cf6.jpg)

## Authors

- **Devesh Kumar**  
  *Computer Science and Engineering, PDPM IIITDM Jabalpur*  
- **Divyanshu Srivastava**  
  *Computer Science and Engineering, PDPM IIITDM Jabalpur*  
- **Gupta Abhikumar**  
  *Computer Science and Engineering, PDPM IIITDM Jabalpur*  
- **Gaurav Choudhary**  
  *Smart Manufacturing, PDPM IIITDM Jabalpur*  
- **M. R. Kishor Naidu**  
  *Computer Science and Engineering, PDPM IIITDM Jabalpur*  
- **Priyank Bhaskar**  
  *Electronics and Communication Engineering, PDPM IIITDM Jabalpur*  
- **Anurag Kerketta**  
  *Design, PDPM IIITDM Jabalpur*  

## Acknowledgments

This research received support during the **Engineering Design Fabrication** course, instructed by **Professor Munesh Singh**, at **PDPM IIITDM Jabalpur**.

## License

This project is licensed under the [MIT License](LICENSE).



