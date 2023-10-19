# PetCuddleOTron

<img width="713" alt="Architecture" src="https://github.com/Denish-Pasupuleti/PetCuddleOTron/assets/24259706/603fe8df-d0f2-4f17-9379-6887ec59d01d">  

An implementation of a serverless reminder application.  

The application will load from an S3 bucket and run in the browser communicating with Lambda and Step functions via an API Gateway Endpoint.  

Using the application you can configure reminders for 'pet cuddles' to be sent using email.

STAGE 1 : Configure Simple Email service  
STAGE 2 : Add a email lambda function to use SES to send emails for the serverless application  
STAGE 3 : Implement and configure the state machine, the core of the application  
STAGE 4 : Implement the API Gateway, API and supporting lambda function  
STAGE 5 : Implement the static frontend application and test functionality  
