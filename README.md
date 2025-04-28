# Deploy node.js app in Google Cloud Run

> This project demonstrate how to deploy node.js sample app in Google Cloud Run

## 🚀 Features

- ✨ Google cloud acount setup
- ⚡ Cloud Run
- 🔒 How to deploy app using Google cloud SDK from local

## 🛠 Tech Stack

- Node.js
- Express
- Google Cloud(Cloud Run)

## 🧑‍💻 Local Setup
- Create free account in google cloud if not already have
- Login to Google cloud console, create a new project, or can use existing one
- Link billing account to project if not already linked
- Create/Enable Cloud Run api from Google cloud console (this is one time activity and has to be done for first time)
- Install and setup google cloud cli(Google cloud sdk) in local as per OS
- Create simple node.js app in local
- Run from terminal - gcloud auth login (authenticate to google cloud)
- Run from terminal - gcloud config set project PROJECT_ID (set project id)
- Run from terminal - gcloud run deploy (follow the instructions basically you will get prompt to enable API for artifact registry, cloud run and cloud build, provide input as yes,you will get prompt for region as well, choose any region)
- Once deploy you will get a url, run in browser and check
- Voila its done now
Note: Make sure to delete all resources once done from Cloud Run, Cloud Build and Artifacts Registry

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/rupachowrasia/gcp-cloud-run-deploy-using-nodejs.git

# Move into the project directory
cd gcp-cloud-run-deploy-using-nodejs

# Install dependencies
npm install

# Run the app
npm run start
