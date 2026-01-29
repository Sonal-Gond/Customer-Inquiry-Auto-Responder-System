# Customer-Inquiry-Auto-Responder-System
Project Overview
This project is an automated customer inquiry handling system built using n8n.
It receives customer form submissions, validates them, stores them, sends automatic email responses, notifies the team on Slack, and handles errors.

Features :
Webhook receives form data (name, email, inquiry type, message)
Validates data and checks for duplicates
Stores in Google Sheets with timestamp
Sends personalized auto-reply email based on inquiry type
Notifies team on Slack with inquiry details
Includes comprehensive error handling
Logs all activities
