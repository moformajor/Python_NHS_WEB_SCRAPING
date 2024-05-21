# Python_NHS_WEB_SCRAPING and Email Notifier

This Python script automates the process of checking an NHS job posting daily, recording the job details into a CSV file, and sending email notifications based on the job's closing date.

## Features
- Web scraping of job details from an NHS job posting.
- Daily automation of the job check.
- Logging job details into a CSV file.
- Sending email notifications based on the job's closing date.

## Requirements
- Python 3.x
- beautifulsoup4:Parses HTML content.
- requests:Sends HTTP requests.
- smtplib and ssl: Sends emails securely.
- csv: Reads from and writes to CSV files.
- datetime: Handles date and time operations.

## Example Execution
When the script is executed:

- It connects to the NHS job posting URL, retrieves and trim job details.
- Logs these details into a CSV file.
- If the job closing date is approaching, it sends reminder emails.
- Repeats the process daily until the job closing date is sufficiently far in the future.
- By automating these tasks, the script helps keep track of job opportunities and ensures timely reminders for application deadlines.
