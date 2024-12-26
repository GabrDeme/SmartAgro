# SmartAgro

**SmartAgro** is a mobile application designed to be an accessible platform for analyzing and managing agricultural data by collecting information from sensors in planting systems.

## Overview🌱

**SmartAgro** was created to address the challenge posed by our mentor: the lack of an optimized environment control system to support strategic decision-making in agricultural production management.

## Solution   

**SmartAgro** offers a comprehensive solution with features designed to improve the management of agricultural activities. Through intuitive tools and data analysis, the platform facilitates planning, monitoring, and execution of field operations.

### Objectives

- **Receive data from agriculture sensors**: Receive real-time data from sensors in planting systems and present it in an accessible and visually clear manner.
- **Help on Strategic decisions**: Utilize the collected data to support users in making strategic decisions through analysis.

---

### Functional Requirements

- **Login**: Secure user authentication using email and password.
- **User Registration**: Register users with encrypted credentials.
- **Password recuperation**: Registered users can reset their password with email sending messages.
- **User information edition**: Users can change their data.
- **Planting plataforms listings**: Display planting plataforms information related to the user.
- **Dashboards**: Exhibit informations using graphics selecting the parameter.
- **Data Exhibition**: Ensure information presentation, by date selection.
- **Planting plataforms Creation**: Provide functionality to create a new bay by entering its name, type, location, general information, and ideal levels.  
- **Planting plataforms Editing**: Enable users to edit details of existing bays, such as name, type, location, and ideal levels.  
- **Planting plataforms Redirection**: Redirect users to a specific bay from the Notifications screen when relevant data is highlighted.  
- **Logout**: Securely log users out of the platform.  

### Non-Functional Requirements  

- **Weather Forecast**: Display weather forecasts for the location of each bay.  
- **Notifications**: Provide updates on the latest data from bays, highlighting deviations from ideal levels.  
- **Alerts**: Show an overall status alert for all bays on the Home screen.  
- **Harvest Time Estimation**: Inform users of the estimated harvest time for crops in each bay.  
- **Real-Time Data**: Display current-day metrics for all bays.  
- **Offline Access**: Allow users to access the most recent synchronized data even without an internet connection.  

### Business Rules  

- **Authentication**: Ensure users are authenticated before accessing any system features.  
- **Data Retention**: Store bay metrics for up to one month for analysis; archive or delete them afterward.  
- **Notification Priority**: Prioritize notifications about deviations from ideal levels over other updates.  
- **Change Logging**: Record any edits to bay data with the user information and timestamp of the change.  

### Constraints  

- **Hardware Compatibility**: Support Android 5.0+ for the mobile application.  
- **Internet Requirement**: Require internet connectivity for real-time updates and weather forecasts; offline functionality limited to synchronized data.
  
---

### Development Team 👥

- [Gabriel Demétrio](https://www.linkedin.com/in/gabriel-dem%C3%A9trio-a06820275/)
- [Maurício Marques]([https://www.linkedin.com/in/paulohgo/](https://www.linkedin.com/in/maur%C3%ADcio-marques-p/))
- [Pedro H. Alves](https://www.linkedin.com/in/pedro-henrique-alves-de-freitas-287b85276/)
- [Wender de Castro]([https://www.linkedin.com/in/richardrichk/](https://www.linkedin.com/in/wender-de-castro/))

---

### Architecture Overview

The architecture of **SmartAgro** is divided into two main layers:

- **Frontend**: Developed using .Net MAUI for a dynamic user interface, styled with SyncFusion.
- **Backend**: Built with ASP.NET Core to provide a robust API. SQL Server is used as the database for efficient storage of user data and planting plataforms. And also uses Mobile Storage to ensure the using of the mobile application

The frontend communicates with the backend through API calls to handle user interactions, which are then processed and stored in SQL Server, ensuring a fluid and responsive user experience.

## Technologies 🛠

- **Frontend**:
  - .NET MAUI
  - SyncFusion
- **Backend**:
  - C#
  - ASP.NET Core
- **Database**:
  - SQL Server

---


