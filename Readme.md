# Attestify

This project demonstrates creating and interacting with gated attestations using the Ethereum Attestation Service (EAS) and Lit Protocol. It also showcases an **Anon Aadhaar** demo for a decentralized identity use case.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- [npm](https://www.npmjs.com/) installed

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sugashsm/attestify.git
   ```
2. Navigate to the project directory:
   ```bash
   cd attestify

   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Add your private key to a `.env` file:
   ```plaintext
   PRIVATE_KEY=your_private_key
   ```
5. Start the CLI demo:
   ```bash
   npm start
   ```

---

## Features

### Gated Attestations

1. Use the CLI to create a gated attestation.
2. View the encrypted attestation on [EAS Scan (Sepolia)](https://sepolia.easscan.org/).
3. Click "Resolve Attestation" to decrypt and interact with the attestation.

---

## Anon Aadhaar Demo

### Steps:

1. Open the demo setup page: [Anon Aadhaar Quick Setup](https://anon-aadhaar-quick-setup.vercel.app/).
2. Switch to **Test Mode**.
3. Use the provided link to generate a QR code.
4. Save the generated QR code as a file.
5. Upload the QR code and click **Generate Proof**.
6. Copy the proof attribute from the displayed data.

### Create and Verify Attestation:

1. Start the CLI demo and select **Create Gated Attestation**.
2. Choose the **Anon Aadhaar** condition.
3. Minify the proof JSON using a tool like [JSON Minifier](https://codebeautify.org/jsonminifier) to remove white spaces.
4. Submit the minified proof.
5. Resolve the attestation.

---

## Resources

- **Ethereum Attestation Service (EAS):** [Official Documentation](https://docs.easscan.org)
- **Lit Protocol:** [Official Documentation](https://docs.litprotocol.com)

---
