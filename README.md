# GitHub Actions Python Logging

This project demonstrates how to set up logging in a Python script and configure GitHub Actions for continuous integration, including log retention and failure alerts.

## Features

- Python script with logging and exception handling
- GitHub Actions workflow with log retention for 14 days
- Email alert for workflow failures using SMTP

## Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/github-actions-python-logging.git
   cd github-actions-python-logging
Add Secrets to GitHub Repo
EMAIL_USERNAME: Your email (e.g., Gmail)
EMAIL_PASSWORD: App password
Push to Main Branch
git add .
git commit -m "Initial commit"
git push origin main
View Logs in GitHub Actions Go to the Actions tab in your GitHub repo to inspect log outputs.


