## How it works

1. **WhatsApp Trigger:** receives incoming messages via the Meta WhatsApp Cloud API
2. **Message parsing:** extracts sender and text
3. **AI agent (Anthropic Claude):** understands the request, keeps chat history per phone number and replies in the customer's language
4. **Calendar tools:** checks availability and creates the appointment in Google Calendar
5. **Lead extraction:** pulls structured lead data (JSON) from the conversation
6. **Consent check:** saves the lead to Google Sheets only if the customer agreed
7. **Reply:** sends the answer back via WhatsApp

## Stack

n8n Cloud · Meta WhatsApp Cloud API · Anthropic Claude · Google Calendar · Google Sheets

## Status

Working prototype built in n8n Cloud. Currently paused.





