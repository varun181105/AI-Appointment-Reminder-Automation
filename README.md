# AI Appointment Reminder Automation (n8n)

## Overview
This workflow automatically sends appointment reminder emails based on appointment data stored in Google Sheets.

## Tools Used
- n8n
- Google Sheets
- Gmail
- Wait Node

## Workflow
Read Appointment from Google Sheets → Wait Until Reminder Time → Send Reminder Email

## How It Works
1. Appointment data is stored in Google Sheets.
2. The workflow reads upcoming appointments.
3. A wait node delays the workflow until the reminder time.
4. Gmail automatically sends a reminder email to the user.

## Setup
1. Import the `workflow.json` file into n8n.
2. Configure Gmail and Google Sheets credentials.
3. Activate the workflow.

## Note
API keys are not included in this repository for security reasons.
