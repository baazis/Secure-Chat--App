# Secure-Chat-App

Implementation of an end-to-end 2048-bit RSA encrypted messenger

## Problem Statement

Data security is crucial. The internet as we know it would not exist without data security; data communicated over the internet would be as vulnerable to interception as a message yelled across a crowded room. Therefore securing these messaging services is crucial using the best techniques.

## Solution

We will be building a traditional browser-based web app for Customer service which can be attached to various websites that wants communication between two users encrypted and safe live on the app. We will try to show an implementation of an end-to-end 2048-bit RSA encrypted messenger

## Process flow

We'll be utilizing Vue.js for coordinating the frontend functionality along with Node.js for integrating the backend and platform.

We will use socket.io to connect members for communication and sending messages which will be shown on the web app in real time which we will try to make using JavaScript Framework like Vuejs.

We will be adding Encryption in our messenger using asymmetric encryption cryptography(to encrypt and decrypt a message and protect it from unauthorized access or use.

## Tech Used

Vue.js - For coordinating the frontend functionality

Nodejs- For integrating backend and for modules

Socket.io- For sending messages between users

Asymmetric Encryption (Public key cryptography)(one to one)/E2E

# Clone the project to run

Run these commands on the terminal to run this chat app

1- Clone this project on ypur system

        git clone https://github.com/baazis/Secure-Chat--App.git   
2- Go to the directory

        cd Secure-Chat--App
3- Install all the dependencies

        npm install
4- Run the Web app

        npm start
5- Open localhost:3000 to see the web-app

Open the localhost from two different browsers and join the same room.

Try to join the same room from different browser, it will notify and stop the third user to enter the room.

## Using different web workers

The code given abpve uses RSA crypto web worker for implementing Encryption and providing security.

In folder `` More Crypto Workers`` I have added three more crypto web workers.

For using those web workers exchange the code of `` /public/crypto-worker.js``  with these codes.

# Outputs

![image](https://user-images.githubusercontent.com/58622363/140531172-de677f27-9da3-4418-a46a-10e23f104cf7.png)

## Two users connected Notification log

![image](https://user-images.githubusercontent.com/58622363/140531549-2457ff6f-20dd-4807-aa38-d519c65d1938.png)

## Chat between two users

![image](https://user-images.githubusercontent.com/58622363/140531807-8affe465-7b91-4370-be9c-e8222aef6f5d.png)

## Messages are Encrypted using web workers

![image](https://user-images.githubusercontent.com/58622363/140531902-28d8fd87-6522-40ac-9514-341ab954578a.png)


