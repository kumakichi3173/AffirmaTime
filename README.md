
# AffirmaTime – 10-Minute Daily Reset App 
(Retool + ChatGPT)
https://saorishigehisa.retool.com/apps/2d7dac48-3692-11f0-83a4-a7eaa3711a20/AffirmaTime/empathy

AffirmaTime is a self-care and affirmation web app built with Retool and OpenAI’s ChatGPT. It helps users unload stress through a 10-minute guided session, receive supportive affirmations, and log their emotional status through daily ratings and a calendar view. The app blends Retool’s custom components, built-in Chat UI, timers, and GPT prompts to encourage emotional awareness and positive reflection.

## Overview

The app begins with a **10-minute timer** during which users are invited to freely type their thoughts, stressors, or feelings into a ChatGPT-powered input area.

During this period, **ChatGPT responds empathetically** — validating emotions and offering helpful, logical insights tailored to the user’s situation. This phase is designed to allow users to offload mental clutter without judgment.

Once the timer expires, the assistant **gently transitions into “affirmation mode.”**  
From that point on, ChatGPT focuses solely on supportive, forward-looking messages, encouraging users to stop overthinking, reframe their mindset, and carry positive energy into the rest of the day.

This time-boxed method ensures users can express what’s weighing on them, receive comfort and advice, and move on with clarity and confidence, without spiraling into negativity.

## Key Features

-  10-minute timer for structured emotional unloading  
-  GPT responds with empathy and logic during the first phase  
-  Affirmation-only mode after the timer ends (custom system prompt)  
-  Retool chat component displays messages in a warm, conversational UI  
-  Daily rating + reflection log  
-  Calendar view to track emotional trends and affirmations over time  

## Philosophy

This app blends guided introspection with AI-powered encouragement to help users release stress intentionally — and stop dwelling past after the timer.

## Requirements

- OpenAI API Key (GPT-3.5 Turbo or GPT-4)  
- Retool account (free tier supported)  
- Optional: Google Sheets or Retool Database for data storage

## TODO

- [ ] Integrate ChatGPT to summarize bullet points based on user records
- [ ] Add a button to allow users to add more bullet points
- [ ] Prevent users from returning to this page after 10 minutes have passed
- [ ] Create a database for concerns and solutions
- [ ] Allow export to an Excel sheet via the calendar on the final page
- [ ] Enable users to rate their feelings on the last page and view their history
