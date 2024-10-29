# Client-Transaction-Revenue-Tracking-Solution-with-Microsoft-Power-Platform
A streamlined solution using Microsoft Power Platform to track client transactions and revenue, integrating Power Apps, SharePoint, Power BI, and Power Automate for real-time insights and efficiency.
## Project Overview
Power Platform Solution for Client Transaction & Revenue Management
The project addresses a common business challenge: optimizing the tracking and management of client transactions and revenue. By leveraging Microsoft’s Power Platform, the solution integrates Power Apps, SharePoint, Power BI, and Power Automate to enhance collaboration, efficiency, and actionable insights.
## Solution Components
### 1.	Power Apps (Canvas App):
A custom-built Canvas App provides three main screens to streamline data entry, updates, and access across devices, enabling team members to manage client transactions from any location.
<br/>
o	Home Screen: Embedded Power BI tiles offer an overview of client transactions and revenue insights, with a "Refresh Data" button, integrated with Power Automate, to instantly update visualizations with new records from SharePoint.
<br/>
o	Entry Screen: Facilitates accurate data entry for new client registrations, with initial data stored in a collection before being saved in SharePoint.
<br/>
o	Edit Screen: Supports editing existing records through a pen icon, allowing users to update and save changes easily. Deletion options ensure seamless record management, and changes are reflected immediately.
<br/>
The app utilizes various controls, Power FX functions, and user/admin-specific features to ensure efficient data input, access, and modification.
### 2.	SharePoint:
Acts as a centralized storage solution for transaction data, providing collaborative, up-to-date access. Temporary data storage within the app uses collections, streamlining the workflow before final transfer to SharePoint for secure, long-term storage.
### 3.	Power BI:
Power BI drives the data visualization and analysis, connecting to SharePoint to deliver critical insights on client transactions, revenue trends, and other metrics for data-driven decision-making.
### 4.	Power Automate:
Power Automate is integrated into the Canvas App to enable automatic Power BI data refreshes, allowing users to see the latest updates without accessing the main report. This “single window” approach creates a seamless experience for data input and real-time visualization.
### Project Benefits
The flexibility and scalability of the Power Platform enhance team efficiency, collaboration, and data-driven decision-making. Using collections as temporary storage streamlines the workflow, enabling easy data manipulation before secure transfer to SharePoint. This setup maximizes productivity, ensuring effective use of resources and a streamlined user experience.

This is the Home Page of the app where Power BI tiles are displayed. A "Refresh Data" button is integrated with Power Automate to update the visualizations with new records from the SharePoint list. To add a new entry, click the "Registration" button.
![image](https://github.com/user-attachments/assets/89f34392-09b0-414d-972b-1f70c08b9cc4)

Fill in all the required details and click "Submit." 
![image](https://github.com/user-attachments/assets/44775fea-76b5-44d4-9b82-aa34fc02536d)

After submitting, you have the option to either edit or delete the entry. 
![image](https://github.com/user-attachments/assets/004d47ea-6e41-4e2c-82ec-45449a2e615a)

You can continue adding more records as needed. 
![image](https://github.com/user-attachments/assets/ca9c02c0-9f95-4e55-aa95-20fd76043c32)

To edit a specific record, click the pen icon. 
![image](https://github.com/user-attachments/assets/db4119bc-72ff-48ae-a195-b1d7e072dd9f)

Modify any necessary details and click "Save" to update the entry.
![image](https://github.com/user-attachments/assets/53eff80a-83e1-407b-80a3-d964e1f207bd)

To delete an entry, click the trash icon, and it will be removed. 
![image](https://github.com/user-attachments/assets/18104ae5-0bc9-4a2a-b7b0-b1b4e5aff52b)

Click "Admin" to save the data into the SharePoint list. Until this step, the data has only been stored in a temporary collection, which now needs to be transferred to SharePoint. Enter the correct password, and the data will be saved, clearing the collection and redirecting back to the Home Page where the updated visualization is displayed.
![image](https://github.com/user-attachments/assets/bed37460-c8b8-4f57-85e7-9d6731d2186b)

Click "Transfer to SharePoint List." 
![image](https://github.com/user-attachments/assets/1083b086-8c64-4746-ae80-8f41ce5eedac)

Select "Refresh Data" so that any new rows will be included in the visualization. The "Refresh Data" button is linked to Power Automate, which updates the visualization with the latest entries because the SharePoint list feeds into it.
![image](https://github.com/user-attachments/assets/fccdec34-caa6-48ca-935b-16d8bff2d3f7)

The dataset's refresh time is shown, confirming the visualization is now up-to-date. 
![image](https://github.com/user-attachments/assets/efbb0ac2-5eaf-46b2-81e2-c8e3aa1c7d6e)
