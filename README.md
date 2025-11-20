## Created chatbots in n8n for customer support .
** website chatbot for e-commerce store created by own using claude for practice.
** whatsapp chatbot for doctors clinic to provide correct information about clinic timing and booking appointment


##
🧹 Home Cleaning Service – Automated Voice Appointment System (n8n + Retell AI + Google Workspace)

This project is an end-to-end automation workflow built using n8n, Retell AI Voice Agent, Google Calendar, and Google Sheets to streamline appointment booking for a home cleaning service.

📌 Overview

This automation ensures that when a customer submits a form on the home cleaning service website, they are automatically contacted by a voice agent. The agent gathers additional details, confirms the customer’s needs, and books an appointment — all without any manual involvement.

The goal is to provide a fast, professional, and seamless customer experience by combining form submission, automated calling, and smart scheduling.

🛠️ How It Works
1. User Submits the Contact Form

A customer visits the website and fills out a cleaning service inquiry form.

The form includes essential details such as name, phone number, email, service type, preferred date, and cleaning notes.

2. n8n Webhook Captures the Data

The form sends all submitted data to an n8n webhook.

n8n stores the information in Google Sheets for record-keeping and future use.

3. Retell AI Voice Agent Contacts the Customer

After saving the data, n8n triggers the Retell AI Voice Agent.

The agent automatically calls the customer using their phone number.

It asks follow-up questions to better understand:

Type of cleaning required

Home size

Preferred booking time

Any special requests

The agent speaks naturally and handles the conversation just like a real receptionist.

4. Appointment Booking in Google Calendar

Once the customer confirms their preferred slot, the agent sends this information to n8n.

n8n books the appointment directly in Google Calendar.

The event includes:

Customer name

Phone number

Email

Appointment time

Google Meet link (optional)

Conversation summary

5. Final Data Logging

All final details are updated again in Google Sheets for complete tracking.

The business owner or admin can review the entire flow anytime.

📂 Features

🔗 Fully automated workflow from form submission to appointment booking

🤖 AI-powered voice calling using Retell AI

📞 Real-time customer interaction

📅 Automatic Google Calendar scheduling

📝 Data saved in Google Sheets for reporting

⚙️ Customizable dialog and logic inside Retell AI

✔️ Reliable, scalable, and no manual effort required

🚀 Technology Stack

n8n – Workflow automation

Retell AI – Voice agent for calling and conversation

Google Sheets – Data storage

Google Calendar – Appointment booking

Website Contact Form – Data entry point

📈 Use Case

This automation is ideal for:

Home cleaning services

Maintenance services

Any business needing automatic customer follow-up

Appointment-based service providers

📜 Summary

This repository showcases a powerful automation system that transforms how service businesses communicate with customers. By combining form data, voice AI, and smart scheduling, the entire booking process becomes faster, more accurate, and fully hands-free.
