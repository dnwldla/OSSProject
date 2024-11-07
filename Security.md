## PhishGuard Security Configuration

We used the GPT API to detect voice phishing through conversations by analyzing the patterns and language used in the dialogue. Since the API requires a secret key for authentication, we took extra precautions to keep this sensitive information secure. To prevent the secret key from being exposed in version control systems, we added the key file to the .gitignore file. This ensures that the key is not tracked or uploaded to any remote repositories, protecting it from unauthorized access while still allowing us to use the API for our project.
