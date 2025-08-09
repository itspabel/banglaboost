# Tutorial: banglaboost

BanglaBoost is an *AI-powered* web application designed to **enhance and transform Banglish/Bengali text**. It allows users to effortlessly improve their writing by **rewriting text in pure Bengali, translating it to English, or fixing grammatical errors**. The app integrates with the Gemini AI service to perform these intelligent text manipulations, offering a user-friendly interface with customizable tone and style options.


## Visual Overview

```mermaid
flowchart TD
    A0["Gemini AI Service Integration
"]
    A1["User Interface (UI) Management
"]
    A2["Application Configuration
"]
    A3["Text Processing Modes
"]
    A4["Tone & Style Filtering
"]
    A1 -- "Triggers" --> A3
    A1 -- "Presents controls for" --> A2
    A2 -- "Provides API key to" --> A0
    A3 -- "Generates prompts for" --> A0
    A0 -- "Delivers results to" --> A1
    A4 -- "Applies styles to" --> A3
    A3 -- "Retrieves selected tones from" --> A4
```
