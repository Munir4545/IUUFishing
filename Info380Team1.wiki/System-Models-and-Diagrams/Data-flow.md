## **Dataflow Diagram**
 This data flow represents the flow of raw real time IUU fishing data from its cleaning process using a temporary database, to how the user views the data based on their role access.


**External Entities**
- Satellite
- Ship Tracking
- GPS
- User
- Administrative Overhead
- Viewable data

**Processes**
- Data transfer to tracking system
- Automated data cleaning
- Data storage
- Login/authentication process

**Data Stores**
- Physical temporary database
- Cloud database

**Data Flows**
- Satellite data, vessel information, and tracking information is collected and transferred into the tracking system

![image.png](/.attachments/image-113a46e3-ef20-4988-9cd3-77f4e708bfd3.png)


**Related backlog items**
#51