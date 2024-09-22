# Trends at a Glance

This repository showcases how I leverage **Microsoft Dynamics** and third-party metric data to track hold times for chats vs. phone calls. By utilizing **Power Automate**, I automate the collection of this data from a SharePoint folder and integrate it into **Power BI** to provide actionable insights on a monthly and daily basis.

## Tools and Technologies:
- **Microsoft Dynamics**: To collect chat and phone call data.
- **Third-party Metric Exports**: To compare chat vs. phone hold times.
- **Power Automate**: Automating the export of data whenever a new file is uploaded to SharePoint.
- **Power BI**: Visualizing trends and producing business insights.
- **SharePoint**: Storing the incoming data files.

## Key Features:
- **Monthly and Daily Trends**: View chat vs. phone hold times over time to spot trends and identify patterns.
- **Automated Data Export**: Power Automate workflow to automatically update the dataset when new files are uploaded.
- **Power BI Reports**: Trend visualization to help with informed decision-making, executive reporting, and employee feedback.

Explore the different sections of this repository to understand how each part of the process is automated and visualized.

# Power Automate Flow: Data Export from SharePoint

This Power Automate flow is triggered whenever a new file is uploaded to the specified SharePoint folder. The flow then automatically exports this data into a format readable by Power BI.

## Steps:
Here’s the full flow process:

1. **Trigger**: New file uploaded to SharePoint.
2. **Action**: Retrieve the file content.
3. *Optional*: Parse data from the file (if necessary).
4. **Action**: Refresh the Power BI dataset to reflect the new data.
5. *Optional**: Notify stakeholders of the update.

See this accompanying Document for a visual representation of the flow:

[View PDF Mock Setup/Workflow Document](https://github.com/therightboat/Trends-at-a-Glance/blob/main/PowerAutomateExample.pdf)

[View PDF Example Power BI Results with Internal Infromation Redacted](https://github.com/therightboat/Trends-at-a-Glance/blob/main/PowerBIResultsExample.pdf)


## Power Automate:
