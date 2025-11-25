# UAPMIS – Urban Air Pollution Monitoring Information System

UAPMIS is an urban air pollution monitoring information system designed to provide a clear and user-friendly interface for managing air quality sensors and analyzing environmental data. The system allows the user to add sensors and their details manually or
through a public API. Also, the user can monitor air pollution data such as NO2, O3, SO2, CO, temperature, relative humidity, and pressure. In addition, the system provides the ability to subscribe to changes in air pollution measurement parameters such as PM2.5 and PM10.

A key feature of the system is the generation of the green route, which is created from the existing air pollution sensors in the system. The green route calculates and displays a route on a map with the least amount of air pollution for all the users. Built using **React.js** on the front‑end and **Node.js** on the back‑end, the system integrates geospatial data and routing logic to help users make healthier navigation choices.

## 🚀 Features

### **1. Sensor Management**

* Add and manage air quality sensors.
* Input sensor details manually or through a public API.

### **2. Real-Time Monitoring**

Track key environmental parameters in real time, including:

* **NO₂** 
* **O₃** 
* **SO₂**
* **CO**
* **PM2.5 & PM10**
* **Temperature**
* **Relative humidity**
* **Pressure**

### **3. Green Route Navigation**

* Computes the *least polluted travel route* between two points.
* Uses geospatial data and real-time sensor measurements to avoid areas with higher pollution levels.

## 🛠️ Tech Stack

* **React.js**
* **Node.js**
* **PostgreSQL**

**Additional technologies used:**

* Integrated **Mapbox API** together with **Turf.js**, which was used to determine the pollution sensor radius. This radius was then applied as an obstacle in the Mapbox routing engine, allowing the system to calculate cleaner, less polluted routes.

## 📸 Screenshots

<img width="1000" height="500" alt="Screenshot 2025-11-25 175737" src="https://github.com/user-attachments/assets/ac004104-2572-4c0c-85a5-77fd85a69371" />
<img width="1000" height="500" alt="Screenshot 2025-11-25 175713" src="https://github.com/user-attachments/assets/a9fdca4d-962a-4f92-a449-99902ced8337" />
<img width="1000" height="500" alt="Screenshot 2025-11-25 180046" src="https://github.com/user-attachments/assets/2cd19589-5b9c-433c-96f4-3cd3bca6b510" />
<img width="1000" height="500" alt="Screenshot 2025-11-25 180024" src="https://github.com/user-attachments/assets/6171cc34-d300-4f84-ae69-4dd29e167599" />
<img width="1000" height="500" alt="Screenshot 2025-11-25 175956" src="https://github.com/user-attachments/assets/d3a1171a-46c8-424f-bd52-d5f0597ead6a" />
<img width="1000" height="500" alt="Screenshot 2025-11-25 175933" src="https://github.com/user-attachments/assets/3f5f892a-d5fb-418a-b421-f26c461d2588" />
<img width="1000" height="500" alt="Screenshot 2025-11-25 175848" src="https://github.com/user-attachments/assets/6cf9f971-7b3d-4a58-9634-163ce2e98c74" />
<img width="1000" height="500" alt="Screenshot 2025-11-25 175803" src="https://github.com/user-attachments/assets/00d415c8-2fc6-4432-ae47-867018b7c0a2" />
<img width="1000" height="500" alt="Screenshot 2025-11-25 180116" src="https://github.com/user-attachments/assets/8b639e3c-18d0-4097-82fc-f60d3d444e5d" />
