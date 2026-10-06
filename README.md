# WhatsApp Booking Agent

A multilingual WhatsApp agent that books appointments automatically. Built with n8n and the Meta WhatsApp Cloud API.

## What it does

A customer writes on WhatsApp. The agent understands the request, replies in the customer's language, books the appointment in Google Calendar and notifies the owner.

**Languages:** German, Arabic and Lebanese-dialect Arabizi (Arabic written in Latin letters).

## How it works

1. **Webhook:** receives incoming WhatsApp messages via the Meta WhatsApp Cloud API
2. **AI intent detection:** works out what the customer wants (booking, question, other)
3. **Reply:** answers in the customer's language and asks for missing details such as date and time
4. **Calendar:** creates the appointment in Google Calendar
5. **Notifications:** informs the owner by email (Gmail) and Telegram

## Why I built it

Many small businesses lose leads because messages go unanswered outside opening hours. The goal: no lead gets lost, and no manual step between message and booking.

## Stack

n8n Cloud · Meta WhatsApp Cloud API · Google Calendar · Gmail · 

## Status

Working prototype, tested end to end with real messages in all three languages. Next step: voice message support.

## Screenshots

(Add screenshots of the n8n workflow here)

## Author

Sherin Chreiteh · [LinkedIn](https://www.linkedin.com/in/sherin-c-8074ba3a8)
