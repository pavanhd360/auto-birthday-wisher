Auto Birthday Wisher 🎂
This Python script automatically sends birthday wishes to your friends and family from a CSV file.

⚙️ Setup & Installation
To run this project, you need to set up your environment variables to securely handle your login credentials.

1. Create a .env file
In the root directory of the project, create a file named .env.

2. Configure Credentials
Add the following lines to your .env file:

Code snippet
MY_EMAIL=your_email@gmail.com
MY_PASSWORD=your_app_password
3. Generate an App Password
Important: Do not use your regular email password. For security reasons (and to bypass 2FA), you must generate an App Password:

Go to your Google Account Settings.

Navigate to Security.

Under "How you sign in to Google," select 2-Step Verification (must be turned on).

Scroll to the bottom and select App passwords.

Give it a name (e.g., "Python Birthday Wisher") and click Create.

Copy the 16-digit code and paste it into your .env file as MY_PASSWORD.
