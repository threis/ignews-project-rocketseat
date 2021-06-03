# Project Ignews - Rocketseat course

This project was made in Ignite course (Rocketseat).

## Install:

Use command ``` yarn ``` or ``` npm install ``` to create the project dependencies

It's also necessary create account to Stripe, Github, FaunaDB and Prismic CSM to use this project


Configure the file ``` .env ``` with environment variables below:
```
#Stripe

#This is a secret API Key provided by Stripe
STRIPE_API_KEY=

#This is a public API Key provided by Stripe
NEXT_PUBLIC_STRIPE_PUBLIC_KEY=

#This is a secret API Key provided by Stripe Webhook
STRIPE_WEBHOOK_SECRET=

#Provide the URL to Stripe send the success request
STRIPE_SUCCESS_URL=

#Provide the URL to Stripe send the cancel request
STRIPE_CANCEL_URL=
```

```
#GitHub

#This is a Client ID provided by Github
GITHUB_CLIENT_ID=

#This is a Client Secret Key provided by Github
GITHUB_CLIENT_SECRET=
```

```
#FaunaDB

#This is a Secret Key provided by FaunaDB
FAUNADB_KEY=
```
```
#Primic CMS

#This is a URL provided by Prismic CMS
PRISMIC_ENDPOINT=
#This is a Client Secret Key provided by Prismic CMS
PRISMIC_ACCESS_TOKEN=
```