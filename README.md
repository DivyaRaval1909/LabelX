# LabelX

LabelX is a Web3-based data labeling platform that allows users to create tasks, workers to complete them, and payments to be processed using the Solana blockchain.

The platform combines cloud infrastructure with blockchain technology to provide secure task management and transparent crypto payments.

---

## Project Overview

LabelX enables:

- Uploading datasets (images/files)
- Creating labeling tasks
- Assigning tasks to workers
- Verifying payments on Solana
- Secure storage using AWS S3
- Safe authentication using JWT

---

## Features

- User authentication (JWT-based)
- Role-based access (Creator / Worker)
- Secure file upload using AWS S3
- Pre-signed URLs for secure uploads
- Task creation and management
- Worker submission system
- Solana wallet integration
- On-chain payment verification
- Transaction confirmation checks
- Protection against double spending

---

## Tech Stack

- Node.js
- Express.js
- React
- AWS S3
- PostgreSQL / MongoDB
- Solana Blockchain
- Web3.js
- JWT Authentication

---

## How It Works

1. A creator creates a task and deposits payment.
2. The system verifies the transaction on Solana.
3. Workers complete the task and submit results.
4. After validation, payment is transferred to the worker’s wallet.
5. All transactions are stored in the database.

---

## Installation

```bash
git clone https://github.com/yourusername/labelx.git
cd labelx
npm install
npm run dev
```

Add environment variables:

```
DATABASE_URL=
JWT_SECRET=
AWS_ACCESS_KEY=
AWS_SECRET_KEY=
S3_BUCKET=
SOLANA_RPC_URL=
PRIVATE_KEY=
```

---

## Security Measures

- No private keys stored directly in source code
- Secure wallet integration
- Transaction confirmation verification
- Pre-signed URLs for secure uploads
- Role-based access control

---

## Future Improvements

- Escrow smart contract system
- Worker reputation system
- Fraud detection
- Multi-chain support

---

## License

MIT License
