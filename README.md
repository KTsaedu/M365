# M365
Search for and Delete Chat Messages in Teams
Overview
This guide outlines the process for searching for and deleting chat messages in Microsoft Teams using eDiscovery (Premium) and the Microsoft Graph Explorer. It was developed to address numerous discrepancies and inconsistencies found in the official Microsoft documentation titled “Search for and delete chat messages in Teams.”

Motivation
While attempting to follow the official Microsoft Knowledge Base Article (KBA) in my job, I discovered significant errors and a lack of clarity. This motivated me to write a clearer and more user-friendly set of instructions. This guide aims to help administrators find and remove sensitive or inappropriate content or respond to data spillage incidents where confidential or malicious information has been released through Teams chat messages in Microsoft 365.

Prerequisites
Access to Microsoft 365 Compliance Center
eDiscovery (Premium) permissions
Microsoft Graph Explorer access
Steps
Access eDiscovery (Premium)
Navigate to the Microsoft 365 Compliance Center.
Select eDiscovery (Premium) from the left-hand menu.
Create a Case
Click on Create a case and provide a name and description.
Open the case once created.
Search for Messages
Go to the Searches tab within the case.
Click on New search and configure your search criteria (e.g., keywords, date range, users).
Review Search Results
Review the search results to identify the messages that need to be deleted.
Delete Messages Using Microsoft Graph Explorer
Open Microsoft Graph Explorer.
Use the appropriate API calls to delete the identified messages. Refer to the Microsoft Graph documentation for detailed instructions.
Conclusion
This guide provides a streamlined process for searching and deleting chat messages in Teams, addressing the gaps and errors in the official documentation. By following these steps, administrators can effectively manage sensitive or inappropriate content in Teams.

Contributions
Feel free to contribute to this guide by submitting a pull request or opening an issue.
