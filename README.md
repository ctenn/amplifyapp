# Notes App 

A Notes app React web application with user authentication, a database, and storage deployed with AWS Amplify.

My first attempt at creating a full-stack web application. Following along to this [tutorial](https://aws.amazon.com/getting-started/hands-on/build-react-app-amplify-graphql?trk=gs_card)! :)

## What it does

A Notes app that allows users to create, delete, and list notes. Notes can also be associated with an image.

## How to use

Deployed at [https://master.d1n5zmtuxdpkye.amplifyapp.com/](https://master.d1n5zmtuxdpkye.amplifyapp.com/)

To run it locally, run `npm start` and open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Things I learnt

- Creating and configuring a React application
- Continuous deployment with AWS Amplify
- Installation and configuration of Amplify CLI
- Using the Amplify CLI and libraries to configure and add user authentication allowing users to sign up with two-step verification, sign in and reset their password
- Using a scalable GraphQL API configured with an Amazon DynamoDB database allowing users to create and delete notes
- Adding file storage using Amazon S3 allowing users to upload images and view them in their app

## To do

- Add social providers to user authentication [(docs)](https://ui.docs.amplify.aws/components/authenticator#socialproviders)
- Add styling to the app
