# Varun-Kumar-V-220701311-OAI1903-RPA-Mini-Project


# **Overview**

In today's fast-paced business environment, managing tickets effectively is vital to ensure quick resolutions and customer satisfaction. Manual ticket categorization can lead to inefficiencies, errors, and delays. This project, **Ticket Categorization Automation**, leverages **Robotic Process Automation (RPA)** with **UiPath** to automate the categorization of incoming tickets based on email content.

The system identifies keywords like "Hardware," "Software," or "Network" in the subject line, categorizes the emails accordingly, logs them in Google Sheets, and further automates the process by emailing categorized Excel sheets to the respective departments. This solution reduces manual intervention, minimizes errors, and enhances response times, demonstrating how RPA can streamline workflows in ticket management systems. The project also provides a foundation for implementing similar automation systems across various industries.

# **Features**

- **Email Reading:** Retrieves unread emails using UiPath’s `Get IMAP Mail Messages` activity.
- **Keyword Detection:** Scans email subject lines for predefined keywords (`"Hardware"`, `"Software"`, `"Network"`).
- **Categorization:** Automatically sorts emails into specific categories and logs them in respective Google Sheets.
- **Automated Reporting:** Sends categorized Excel sheets to the relevant department (e.g., Hardware, Software, or Network) through Gmail, improving communication and efficiency.
- **Error Reduction:** Minimizes human errors in ticket categorization and enhances workflow efficiency.
- **Time Efficiency:** Automates repetitive tasks, speeding up the ticket management process.

# **Prerequisites**

To run this project, you will need:

- **UiPath Studio** (installed on your machine)
- **Google Account** and **Google Sheets** access
- **IMAP Email Account** (for email fetching)
- **UiPath Google Activities** package (for Google Sheets integration)


