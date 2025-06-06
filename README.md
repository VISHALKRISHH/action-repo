# action-repo

This is the trigger repository used to generate GitHub events like:

- Pushes
- Pull Requests
- Merges

These actions are captured by a GitHub webhook and sent to a Flask-based webhook server for processing.

## 📌 How It Works

- A GitHub webhook is configured in this repository
- On push/PR/merge, an HTTP POST is sent to the webhook endpoint
- The webhook server parses the payload and stores it in MongoDB

## ⚙️ Setup Instructions

1. Fork or clone this repo.
2. Add or edit files and push changes to trigger events.
3. Or create and merge pull requests.

## 🔗 Webhook URL

> Replace with your actual URL: https://your-ngrok-url/github

