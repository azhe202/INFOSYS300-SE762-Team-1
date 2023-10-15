# Customer Onboarding Automation
This is an RPA bot that scrapes customer data from online forms and collates the data into an excel sheet. This reduces the manual effort of onboarding, and ensures data accuracy and validity. 
Customer entries are stored in this [google form](https://docs.google.com/forms/d/1cvZUBP0Vo8Vy-w5j898pOsyVXV3VYtjqrnkpFijs_cc/edit#responses)

## How to run
1. Clone this repo or download the zip file.
2. Open the project in UiPath Studio. We recommend using UiPath Academic Alliance Studio 2022.4.1, as this is the version it has been tested on. Unexpected errors may occur when using other versions.
3. Install Microsoft Edge and its UiPath extension. Instructions can be found [here](https://docs.uipath.com/studio/standalone/2023.4/user-guide/extension-for-edge-chromium)
4. Open the [responses web form](https://docs.google.com/forms/d/1cvZUBP0Vo8Vy-w5j898pOsyVXV3VYtjqrnkpFijs_cc/edit#response=ACYDBNhJvN--6fXUk6jgSOAGx9NWFwVpYBhZe0nrTvaduGhPd-uEJeZl9wQeaHPr8gyqmpo) on a Microsoft Edge browser. IMPORTANT: It must be Microsoft Edge, and the responses must be open to form number 1
5. Open the file Main.xaml
6. Click Run/Debug
Microsoft Edge windows will open during the process. Do not interrupt the process. When the bot is finished, a dialogue will appear with the message 'Process complete'.

Open cust_data.xlsx to view the sorted and validated data. 

## FAQ
How does the bot work?
- The bot works by scraping customer data from online forms using Microsoft Edge and its UiPath extension. It then validates and organizes this data into an Excel spreadsheet, reducing the need for manual data entry.

What are the benefits of using this bot?
- The bot minimizes manual effort in the customer onboarding process, ensuring data accuracy and validity.
- It helps prevent data entry errors and reduces the time required for onboarding.

What software and tools are required to run this bot?
- You need UiPath Studio, specifically UiPath Academic Alliance Studio 2022.4.1 (recommended for tested compatibility).
- You also need Microsoft Edge with the UiPath extension, which can be installed following the instructions provided in the [documentation](https://docs.uipath.com/studio/standalone/2023.4/user-guide/extension-for-edge-chromium).

Can I add new customers to the form?
- Yes! Just follow this [link](https://docs.google.com/forms/d/e/1FAIpQLScm45kAn7LA41sbDRfhKIkykisubdUI7VBgbB7sxECBabjFLw/viewform?usp=sharing)

Can I modify or extend the functionality of this bot to suit my specific needs?
- Yes, you can customize and extend the functionality of the bot in UiPath Studio to meet your specific requirements.

Is there any ongoing maintenance required for the bot?
- Regularly review and update the bot to ensure it remains compatible with any changes in the online forms or data sources it interacts with.

What should I do if I encounter unexpected errors while running the bot?
- If you encounter unexpected errors, ensure that you are using the recommended version of UiPath Studio (2022.4.1) and that you have correctly installed the Microsoft Edge extension as per the provided instructions. If issues persist, you may need to troubleshoot the bot's configuration or consult the UiPath community for assistance.

## Deployment Recommendations
Currently, the bot is developed to be deployed on a per-PC basis. This can be achieved by following the run instructions on each PC.  

For a full business solution, we recommend a cloud-based deployment. Our project could be deployed on the cloud-based Orchestrator, allowing centralized management of robots, including scheduling, logging, reporting, and other functions. Deploying to the cloud will mean our robots can operate whenever and wherever. As long as there's an internet connection, they will be able to access and perform tasks, ensuring high availability and flexibility. Additionally, we will be able to monitor the robot's status, execution history, and performance metrics through a dashboard.  
To ensure our RPA processes run on schedule, we recommend setting up a time trigger. To give customers enough time to handle feedback, we recommend 9:30 AM daily as the trigger time. This means that every morning at 9:30 AM, our robot will automatically start and carry out its tasks without human intervention, making it a truly unattended robot.

## Meet the team
INFOSYS300/SOFTENG762
- Ananya Ahluwalia
- Hugo Hine
- Breanna Jury
- Avikash Naidu
- Yunyang (Patrick) Peng
- Leon Wang
- Yuewen Zheng

https://github.com/azhe202/INFOSYS300-SE762-Team-1 
