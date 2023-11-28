# Description:

The Auto_reply_gmail_api_app is a Node.js-based application leveraging Google APIs. It serves as a tool to manage email responses for Gmail users during their absence, automating replies to incoming emails while they're on vacation.

# Key Features:

Node.js Clusters Support: Utilizes Node.js clusters to enhance performance and scalability.
Email Monitoring: Monitors a specified Gmail inbox for new emails.
Automated Replies: Generates and sends replies to emails lacking prior responses.
Label Management: Adds a specific label to the replied email and archives it accordingly.
Interval-Based Checking: Executes the aforementioned tasks in a random interval between 45 to 120 seconds.
Libraries Used:

1. Googleapis: Imported from the googleapis module, enabling seamless interaction with various Google APIs, notably the Gmail API.
OAuth

2: Leverages the OAuth2 class from the google.auth module, facilitating application authentication, access token acquisition for Gmail API requests, and managing token refreshes and request retries as needed.
