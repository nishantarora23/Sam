# Getting Started with DevOpsJenkinsBot
This guide is intended to assist new developers in establishing a seamless development environment for the DevOpsJenkinsBot project, enabling them to contribute. Its purpose is to offer comprehensive insights and step-by-step instructions for an efficient setup process.

# Setup Process
- Register on the Microsoft 365 Developer Program
- Setting up Bot
- Configuring DevOpsJenkinsBot
- Setting up Ngrok
- Configuring Developer Sandbox

## Register on the Microsoft 365 Developer Program
Create an account on [Microsoft 365 Developer Program](https://developer.microsoft.com/en-us/microsoft-365/dev-program) to create the Developer Sandbox.  
**Note:** After this stage, we will use the credentials created to register for the Developer Program.

## Setting up the Bot
1. Login to 
6.  Authenticate to the [Developer Portal](https://dev.teams.microsoft.com/apps) using the credentials created in Step 1.
   - Click on **New app** and provide the name.
   - Update the **Basic information** (Short Name, Full Name, Short Description, Long Description)

## Setting up Ngrok
1. Sign Up for Free at [Ngrok](https://ngrok.com/)
2. Download the Ngrok executable for your operating system.
3. Run the command to authenticate Ngrok on your local.  
   `ngrok config add-authtoken <YOUR_AUTH_TOKEN>`  
4. Run the command to expose the DevOpsJenkinsBot local server.  
   `ngrok http -host-header="localhost:3978"`

## Configuring Developer Sandbox
1. Login to the [Developer Portal](https://dev.teams.microsoft.com/apps)
2. 
