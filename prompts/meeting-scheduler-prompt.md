# Meeting Extraction Prompt

## Purpose

Extract meeting details from emails.

## Prompt

```text
Analyze the email and determine whether it contains
a meeting request.

If a meeting exists, extract:

- Event Title
- Date
- Time
- Duration

Return the output in JSON format.

Email:
{{email_body}}
```