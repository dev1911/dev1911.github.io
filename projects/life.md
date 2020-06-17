---
layout: project
type: project
image: images/life.jpg
title: Life++
permalink: projects/life
# All dates must be YYYY-MM-DD format!
date: 2019-08-01
labels:
  - Blockchain
  - Ethereum
  - OCR
  - Keras
summary: An Ethereum based EHR system ensuring integrity of medical records
---
A web application serving as a medical record keeper ensuring integrity through blockchain.  
  
## Features / Workflow:
* Users can upload prescriptions in image format. The system will extract text out of it using OCR.  
* Once the prescription is converted to text, the server generates a hash of the document and publishes it on a ethereum blockchain.  
* When user wants to retrieve the same document, the server will match the hash of the document in the file system with the hash present in the blockchain.  
* If the two hashes are same, it means that the document is not tampered with. Else the user is alerted about the corruption of the data and is given an option to reupload the document.  
* The system also has a feature of uploading chest X-Rays and predicting whether the patient has pneumonia or not.  
* All the above functions can be carried out both by patients and doctors, which are the two types of users.  

## Tech Stack
* Django :- Server
* Tesseract :- OCR
* web3.py :- Library to communicate to blockchain
* Ganache :- Local ethereum blockchain for development 
* Solidity :- Smart Contracts  
* Keras :- ML model

Source: <a href="https://github.com/dev1911/life_plus_plus"><i class="large github icon"></i>dev1911/life_plus_plus</a>