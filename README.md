# RPA Email Automation

## Overview
This project demonstrates an enterprise-level RPA email automation workflow developed using UiPath concepts.

The automation bot performs:
- Reading emails automatically
- Extracting attachments
- Processing report data
- Sending notification emails to stakeholders

This project simulates a real-world unattended automation process commonly used in enterprise support and reporting operations.

---

# Business Use Case

Organizations receive multiple incident summary reports via email daily. Organizations need to work on specific project tickets. Manual processing consumes time and increases chances of errors.

This automation solution:
- Reads incoming emails
- Downloads attachments
- Extracts and validates report data
- Generates ticket summaries
- Sends automated notifications

---

# Features

## Email Automation
- Read unread emails
- Filter emails by subject/sender
- Download attachments automatically

## Attachment Processing
- Extract Excel/PDF attachments
- Validate report data
- Process business rules

## Notification System
- Generate status notifications
- Send summary emails
- Attach ticket summary report

## Logging & Exception Handling
- Error logging
- Retry mechanism
- Process tracking

---

# Technologies Used

- UiPath Concepts
- Outlook Automation
- Excel Automation
- Email Automation
- Workflow Automation

---

# Workflow Architecture

1. Read Incoming Email
2. Validate Sender & Subject
3. Download Attachments
4. Process Report Data
5. Generate Summary
6. Send Notification Email
7. Update Logs

---

# Project Structure

```text
workflow/     -> Main automation workflows
config/       -> Configurable settings
input/        -> Sample input files
output/       -> Generated outputs
screenshots/  -> Workflow screenshots
docs/         -> User & deployment documents
```

---

# Screenshots

## Main Workflow
![Workflow](screenshots/workflow-overview.png)

## Email Processing
![Email](screenshots/email-processing.png)

## Notification Mail
![Notification](screenshots/notification-mail.png)

---

# Architecture Diagram

![Architecture](diagrams/architecture-diagram.jpg)

---

# Exception Handling

- Invalid attachment handling
- Missing email validation
- Retry mechanism for failures
- Error logging support

---

# Future Enhancements

- Dashboard reporting
- Multi-mailbox support

---

# Disclaimer

This repository contains demo/sample automation workflows created for learning and portfolio purposes only.  
No client confidential information or production code is included.
