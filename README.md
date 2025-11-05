# Email-AI-Agent
This project demonstrates an AI-driven automation built with n8n, leveraging OpenRouter GPT‑4.1‑mini and a Google Sheets database to process user chat instructions and send personalized emails automatically.

Key features:-
Chat-based user interaction: Users enter simple natural-language instructions in a conversational UI.
Lightweight memory/context: The agent keeps track of recent exchanges for better responsiveness.
Google Sheets integration: The workflow looks up recipient and content information from a spreadsheet database.
Automated email dispatch: Based on the instruction and data lookup, the agent sends a personalized email to the designated person.
No-code/low-code architecture: Built using n8n’s visual workflows for rapid prototyping and simplicity.

Why this matters:-
With this setup you can automate everyday tasks like “Send the latest sales summary to Jane,” or “Email the monthly report to manager X,” by simply chatting with the agent. It brings together conversational AI, data lookup, and email automation-all in under X minutes to deploy.

What you’ll find in this repo:-
n8n workflow JSON export
Google Sheets sample & column definitions
Environment & credential setup instructions (OpenRouter API key, SMTP settings)
Demo video link (https://www.linkedin.com/posts/rushab-kumar-jha_n8n-ai-automation-activity-7391711643392425984-br7y?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAACbHZXkBTe3PMEDpvbpYuGG9nlMdbXMi1H0) & usage guide
Notes on extending the system (e.g., adding attachments, richer memory, alternative models)

Getting started:-
Clone the repo.
Import the workflow into n8n.
Configure your Google Sheets and SMTP credentials.
Set up the OpenRouter key and point the model to GPT-4.1-mini.
Run the workflow, interact via chat UI, and watch the email get sent seamlessly.

License

MIT License — feel free to use, modify and build upon this for your own automation projects.
