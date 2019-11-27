# Dialogflow playground

A playground project to test dialogflow


## Setup

* Create a new project on [Google Cloud Platform](https://console.cloud.google.com/)

* Enable [Dialogflow API](https://console.cloud.google.com/flows/enableapi?apiid=dialogflow.googleapis.com) for your project

* Create [credentials](https://console.cloud.google.com/apis/api/dialogflow.googleapis.com/credentials) for your project

> Download the credentials JSON file

* Create a `.env` file based on `.env.example` and copy the necessary credentials from the downloaded JSON file

```
GOOGLE_PROJECT_ID="..."
GOOGLE_PRIVATE_KEY_ID="..."
GOOGLE_PRIVATE_KEY="-----BEGIN PRIVATE KEY-----\n...\n-----END PRIVATE KEY-----\n"
GOOGLE_CLIENT_EMAIL="..."
GOOGLE_CLIENT_ID="..."
```

* Create a new agent in [Dialogflow Console](https://dialogflow.cloud.google.com/#/newAgent)


## Run

```
npm start
```
