**Dataflow Diagram:**
This diagrams shows the flow of data through registered fishing vessel system which detects for suspicion on IUU fishing.

**External Entities:**
- Fishing Vessels: Fishing Vessels will register there vessel, they will provide information of vessel along with owner and AIS data
- Analyst: They look over the data monitoring, cleaning, generating reports, and work with other stakeholders in determining alerting systems
- Regulators: Using data provided from analysts they determine what actions are needed to be taken these include enforcing laws, determining alerting zones, evidence compiling

**Processes:**
- Data Collection: This process begins with the collection of data from fishing vessel when they register or update their vessels information. This data includes vessel type, vessel name, vessel owner, and vessel date, vessel location, AIS data, etc.
- Data Management: This process involves managing and analyzing the stored data which is done through the data analyst.
- Reports: This process is responsible for creating various reports on suspicious fishing vessels. This includes tracking patterns of common areas where suspicious vessels are, and generate visual reports.
- Updates: This process involves taking reports generated and updating the system on alerts zone, as well as send out flagged reports to relevant stakeholders such as prosecutors, coastal guards, etc.

**Data Stores:**
- Fishing Vessel Database: This is the central database where all fishing vessels information is kept. This includes personal information, vessel type, vessel name, and vessel date, vessel location, AIS data, etc.
- Processed Data: This is contains data trends in common areas of IUU fishing along with all generated reports which is stored for future references as seasons changes.
- Alerts History: This data stores records of all alerts and interactions on various fishing vessels with authorities, recording AIS data which includes location, time, date, speed, etc. 

**Data Flows:**
- We first begin with Fishing Vessels registering and providing their data which flows into our central database 
- The collected data is stored the Fishing Vessel Database
- Data analyst then reviews the data for processing then transfers it to a processed database and to specialist to review for strategic planning of IUU zones and IUU patterns recognition
- Generated reports are then used by the Specialist and Prosecutors for strategic planning of IUU zones, evidence gathering, and pattern recognition. 
- Alerts are then sent out to local coast guards and authorities

![image.png](/.attachments/image-4b917c02-4540-470b-b34c-cbdd9fe97e50.png)

https://miro.com/app/board/uXjVKQpsIoY=/