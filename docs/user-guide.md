# User Guide

## Project Name
RPA Email Automation

---

# Introduction

RPA Email Automation is an unattended automation solution designed to process operational emails, extract attachments, generate reports, and send automated notifications.

This guide explains how end users can execute and monitor the automation process.

---

# Key Features

- Automatic email processing
- Attachment extraction
- Report generation
- Notification email delivery
- Logging and exception handling

---

# Workflow Overview

The automation performs the following steps:

1. Read incoming emails
2. Validate email subject and sender
3. Download attachments
4. Process report data
5. Generate summary reports
6. Send notification emails
7. Update logs

---

# Folder Structure

input/      -> Incoming files
output/     -> Generated reports and logs
workflow/   -> UiPath workflow files
config/     -> Configuration files
docs/       -> Documentation

---

# How to Execute the Process

## Step 1 — Open UiPath Studio

Open the project in UiPath Studio.

---

## Step 2 — Open Main Workflow

Navigate to:

workflow/Main.xaml

---

## Step 3 — Run the Process

Click:
Run

The automation process will start execution.

---

# Input Requirements

The process expects:
- Operational emails
- Excel/PDF attachments
- Valid report format

---

# Output Details

Generated outputs include:
- Processed reports
- Consolidated summaries
- Notification emails
- Execution logs

Output location:

output/ProcessedReports/process_report.xlsx

---

# Configuration Settings

Configuration values are maintained in:

config/Config.xlsx

Users can update:
- Email subject filters
- Folder paths
- Recipient email addresses
- Output locations

---

# Logging Information

Execution logs are stored under:

output/Logs/DaliyReportlog<month>.txt


Logs help track:
- Process execution
- Errors
- Validation failures
- Processing status

---

# Error Handling

The automation handles:
- Missing attachments
- Invalid email formats
- Report validation failures
- Email notification failures

---

# Best Practices

- Ensure Outlook is configured properly
- Validate attachment formats
- Avoid changing folder structure
- Monitor execution logs regularly

---

# Troubleshooting

## Issue: Emails Not Processing

Possible causes:
- Incorrect subject filter
- Outlook connectivity issue
- Invalid sender

---

## Issue: Attachment Not Found

Possible causes:
- Missing attachment
- Unsupported format
- Incorrect email content

---

## Issue: Notification Email Failure

Possible causes:
- Outlook configuration issue
- Invalid recipient address

---

# Support Information

For deployment or execution support:
- Verify configuration settings
- Review execution logs
- Validate folder permissions

---

# Disclaimer

This project is a sample/demo automation solution created for learning and portfolio purposes only.