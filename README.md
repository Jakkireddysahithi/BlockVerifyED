# Blockchain Based Education Records Verification:
System Manual:
The System Manual provides technical details about the system architecture, configuration, and deployment.

1. Introduction and Overview:
Project Overview:Enable educational institutions to issue and verify certificates on a blockchain, ensuring authenticity and preventing fraud.
Audience: Educational Institutions, Students, Employers to conduct background check.
Scope: The Online Student Certification System is built to help educational institutions create, manage, and validate student certifications in a digital format. This web-based platform focuses on providing a secure, efficient, and user-friendly approach to handling academic credentials.
By transitioning from traditional paper certificates to digital ones, the system minimizes administrative efforts while streamlining the verification process for all stakeholders.
3. System Architecture:
Detailed Architecture: Describe each component of the system in detail, explaining how they work together to meet project objectives.
Technologies Used:React, NodeJS,Hardhat,IPFS,IPFS Companion.
Data Flow:
![image](https://github.com/user-attachments/assets/d59d04fb-cce4-4d9d-9c1b-0661b42a288d)

5. System Requirements:
Hardware Requirements: 4GB RAM
Software Requirements: NodeJS, ReactJS,Hardhat, IPFS, IPFS Companion, Metamask.
6. Installation and Setup:
Create a Smart Contract , deploy.js

Install Hardhat.
npm install --save-dev hardhat

Compile the contract:
npx hardhat compile

Deploy Contracts:
npx hardhat node

npx hardhat run scripts/deploy.js --network localhost

Copy the deployed contract and add to the .env file.
Code for connecting to metamask, IPFS file storage, Storing details of student and issuer. Validation and ReactJS is used for the front end.
npm start.
