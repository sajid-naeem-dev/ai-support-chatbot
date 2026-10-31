# AI Support Chatbot

A customer support chatbot built with Python and the OpenAI API. It answers
questions using only a business information sheet, admits when it does not
know something and stays on topic.

The demo uses a fictional coffee shop called Brew Corner.

## Features
- Answers from a business FAQ (hours, menu, delivery, refunds)
- Remembers the recent conversation for follow up questions
- Does not invent information and points to the contact email instead
- Politely redirects unrelated questions

## Tech Used
Python, OpenAI API (Responses API), Google Colab

## How to Run
1. Open `ai_support_chatbot.ipynb` in Google Colab
2. Add your own OpenAI API key in Colab Secrets as `OPENAI_API_KEY`
3. Click **Runtime > Run all**

## Sample Conversation
See the saved demo output in the notebook.

## Customizing for a Business
Replace the `BUSINESS_INFO` text in the notebook with the real business
details and the bot will answer from them.

## Security
No API keys are stored in this repository.
