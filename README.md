LabelX

LabelX is a Web3-based data labeling platform where users can create tasks, workers complete those tasks, and payments are processed using the Solana blockchain.

It combines traditional cloud technologies with blockchain-based crypto payments to create a secure and transparent crowdsourcing system.

Project Objective

The objective of LabelX is to:

Allow users to upload images or files

Create labeling tasks

Enable workers to complete tasks

Process payments using cryptocurrency

Verify transactions securely on the blockchain

Features

User authentication using JWT

Secure file uploads using AWS S3

Pre-signed URLs for safe uploads

Task creation and management

Worker submission system

Solana wallet integration

On-chain payment verification

Secure transaction handling

Protection against double spending

Tech Stack

Node.js

Express.js

React

AWS S3

PostgreSQL / MongoDB

Solana

Web3.js

JWT Authentication

How LabelX Works

A creator creates a task and deposits payment.

The payment is verified on the Solana blockchain.

Workers complete the task and submit results.

After validation, payment is transferred to the worker’s wallet.

All transactions are recorded in the database.

Security Measures

Private keys are not stored directly in the server code

Secure wallet integration

Transaction confirmation verification

Pre-signed URLs for secure file uploads

Role-based authentication system

Installation
git clone <your-repository-link>
cd labelx
npm install
npm run dev


Add environment variables:

DATABASE_URL=
JWT_SECRET=
AWS_ACCESS_KEY=
AWS_SECRET_KEY=
S3_BUCKET=
SOLANA_RPC_URL=
PRIVATE_KEY=

Future Improvements

Escrow smart contract system

Worker reputation system

Fraud detection mechanism

Multi-chain support

License

MIT License
