# E-Voting using Blockchain

This project is a blockchain based decentralized web application that allows users to vote for their preferred candidates in an election. It is built using MERN Stack, Solidity and so many other things.

## Installation and Setup🔧

To run the script in your vs code open a terminal tab and navigate to the code directory. And run the below commands in a terminal tab:
```
 cd client
 npm i
 npm start
```
On another separate terminal tab run:
```
 npm i->npm run dev
```
You will also need to create an env file as the given .env.sample file env.sample and add the port number, mongodb atlas database information for running the codebase.

### Python Script(required for face authentication)🐍

To install the necessary packages for the Python script, use the command `pip install opencv-python, numpy, os, face_recognition`. Add photos to `/Face` with the same username in use. To add a URL for photos, go to `/server/Controller/encoded.py` line 6.

### Want to Enable/Disable Face Authentication ?🤔

Default value is false to enable/disable change `isFaceRecognitionEnable` in `Client/src/Data/Variable.jsx`.(Python Modules required)
