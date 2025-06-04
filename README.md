# 📧 Gmail Automation with UiPath

This project leverages UiPath to automate Gmail operations, streamlining tasks like sending, reading, and organizing emails. It's designed to enhance productivity by reducing manual email management.

## 🚀 Features

- **Automated Email Sending**: Compose and dispatch emails without manual intervention.
- **Inbox Management**: Read, label, and archive emails efficiently.
- **Custom Workflows**: Tailor automation processes to specific needs.:contentReference[oaicite:10]{index=10}

## 🛠️ Getting Started

### Prerequisites

- **UiPath Studio**
- **Gmail Account**

### Setup Instructions

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/sathwika66/Gmail-Automation.git
   
2. **Open in UiPath Studio**:
- Launch UiPath Studio.
- Open the Main.xaml file from the cloned repository.

3. **Configure Gmail Integration**:
- Set up Gmail activities using UiPath's GSuite or Gmail packages.
- Authenticate using OAuth 2.0 or App Passwords as per your account settings.

4. **Run the Workflow**:
- Execute the Main.xaml to initiate the automation process.

### Project Structure :

- .data/ – Contains data files used in the automation.
- .objects/ – Houses object repository items.
- .project – Project configuration file.
- .settings/ – Stores project settings.
- .tmh/ – Temporary files generated during execution.
- Main.xaml – Primary workflow file.
- project.json – Project metadata and dependencies.

###Notes:
- Security: Ensure that sensitive information, such as credentials, is securely stored and not hard-coded.
- Error Handling: Implement robust error handling to manage exceptions during automation.
