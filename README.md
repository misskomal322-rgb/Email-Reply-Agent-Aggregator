# Email-Reply-Agent-Aggregator
A scheduled automation workflow that fetches Gmail messages, processes them with an AI model, logs results into Google Sheets, and updates email status.

🚀 Workflow Overview

This automation runs on a schedule and performs the following actions:

Schedule Trigger
Starts the workflow at a defined interval.

Gmail – Get All Mails
Retrieves unread or targeted emails from your Gmail inbox.

Gmail – Get Mail Details
Extracts full details for each email (sender, subject, body, etc.).

AI Agent (Google Gemini Chat Model)
Processes each email using the connected Gemini Chat Model.
Examples:

Classifies or interprets email content

Generates responses

Extracts structured data

Google Sheets – Append Row
Saves AI-processed outputs and email information into a sheet.

Gmail – Mark as Read
Marks the processed emails as read to avoid duplication.

📌 Purpose

Automate email processing

Create AI-powered summaries or actions

Log structured insights into a Google Sheet

Keep inbox clean by marking messages as handled

🛠 Requirements

Gmail connected account

Google Sheets integration

AI Agent with Google Gemini Chat Model linked

Scheduler configured

✔ Output

Organized and structured data in Google Sheets

Emails automatically processed and marked as read

AI-enhanced understanding of incoming messages
