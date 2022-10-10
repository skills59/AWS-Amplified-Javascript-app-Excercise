### AWS Amplified React JS, Node JS application, API Gateway and Lambda function to host RESTAPI.
This project is an AWS Amplify Application using React JS, Node JS combined with an API Gateway endpoint and a LAMBDA Function to host the REST API. In other words I used the amazon web service - AWS amplify to build a full stack application, on the front end i used react js, for the backend i used node js combined with an API Gateway endpoint and a lambda function to host the rest API

#### ***Olatunde AKA Sugardaddy LOL**

To achieve this you will need to have; NPM, git, amplify CLI and Node packages, installed on your VSCode, an Aws account, and a github account. 

STEPS

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

Next Step 
### Initiate Amplify 
### `amplify init`
make sure you run this command from the root of your app directory
>>> enter a name for the project: (awsamplifyapp) 'you can leave as default by pressing enter'
>>>enter a name for the enviroment: Dev 'you can leave as default by pressing enter'
>>>choose your default editor:(use arrow keys)
>Visual studio
Atom Editor
Sublime Text
Intellij IDEA
im
Emacs
None

'if youre using visual studio like i did make use of the arrow on your keyboard to select it'
>>>choose the type of app youre building (use arrow keys)
andriod
ios
>javascript 'for this project we used javascript'
>>>what javascript framework are you using
angular
ember
ionic
react
react-native
vue
none
>>>source directory path: src
distribution directory path:(build)
build command:npm.cmd.run-script build
start command: (npm.cmd run-script start)
using default provider: awscloudfoundation

its then going to ask you for the AWS profile you want to use kindly selet whatever profile you have on AWS 
the backend will be immidiately created from here.

Next Step 
### Create API
### `amplify add api`
This command will create a backend API but befoe then you will be promted with a few questions ike;
>>>select from the below mwneitoned service:(use arrow keys)
GraphQL
>REST API (since we are making use of the Rest API we will select this)
>>>provide a friendly name for your resource to be used as lable for this category in the project: api245435fv (this can be left on default by just hitting the enter key)
>>>provide a path: /customers/{customerId} or this project i just used customers

follow the steps to select the values needed. 

Next Step 
### Edit Backend Src and Index files to fit project. 
### `all files can be found in github repository`






Next Step 
### Pull backend enviroment dev from the cloud 
### `amplify push`

this command displays whats going on in AWS Cloud 
and asks if you want to continue








# AWS-Amplify-Javascript-Excercise
