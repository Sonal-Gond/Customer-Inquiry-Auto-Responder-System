
# Customer-Inquiry-Auto-Responder-System
Project Overview
This project is an automated customer inquiry handling system built using n8n.
It receives customer form submissions, validates them, stores them, sends automatic email responses, notifies the team on Slack, and handles errors.

Features :
1. Webhook receives form data (name, email, inquiry type, message)
2. Validates data and checks for duplicates
3. Stores in Google Sheets with timestamp
4. Sends personalized auto-reply email based on inquiry type
5. Notifies team on Slack with inquiry details
6. Includes comprehensive error handling
7. Logs all activities
