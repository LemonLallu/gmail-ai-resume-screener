# Gmail AI Resume Screener

Agentic n8n workflow that auto-screens inbound resumes from Gmail using OpenAI.

## What it does
- Polls Gmail every minute for emails with attachments
- Routes PDF / DOCX / TXT through multi-path text extraction
- Passes resume to OpenAI recruiter agent → generates fit score (1–10), strengths, weaknesses
- Appends structured output to Google Sheets for zero-touch tracking
- Error handling with automated Gmail alert emails on failure

## Tech Stack
n8n · OpenAI API · Gmail API · Google Drive · Google Sheets

## Workflow Preview
<!-- Add canvas screenshot here -->

## Import
Download `gmail_ai_resume_screener.json` → n8n → Import Workflow
