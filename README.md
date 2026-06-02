# AI-Driven Cyber Threat Detection and Automated Response System Using n8n

## Project Overview
This project is a cybersecurity automation solution built using n8n. The system monitors login attempts, detects suspicious activities, and automatically triggers security responses when a predefined threat threshold is reached.

The workflow demonstrates how AI and workflow automation can be combined to improve security monitoring and incident response without requiring complex coding.

## Features
- Real-time login monitoring
- Detection of suspicious login attempts
- Automatic account blocking after multiple failed attempts
- Email security alerts using Gmail
- Telegram notifications for administrators
- AI-powered threat analysis using OpenAI
- Automated incident response workflow
- Easy integration with other security tools

## Workflow
1. User attempts to log in through the web interface.
2. Login data is sent to an n8n Webhook.
3. The system tracks failed login attempts.
4. When the failed attempts exceed the threshold:
   - Email alert is sent.
   - Telegram notification is triggered.
   - Account is blocked.
   - AI generates a security recommendation.

## Technologies Used
- n8n
- OpenAI API
- Gmail API
- Telegram Bot API
- HTML
- JavaScript

## Project Structure

ai-cyber-threat-detection-n8n

├── Cyber Threat System.json  
├── login.html  
├── screenshots/  
└── README.md

## Applications
- Cybersecurity Monitoring
- Threat Detection
- Security Automation
- Incident Response
- AI-Powered Security Operations

## Future Enhancements
- IP Address Tracking
- Device Trust Verification
- Risk Scoring Dashboard
- Security Log Database
- SIEM Integration

## Author

**Aamna Amin**  
BS Artificial Intelligence  
Pak-Austria Fachhochschule Institute of Applied Sciences and Technology (PAF-IAST)
