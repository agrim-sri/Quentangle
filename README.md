## **Quentangle**

## Secure Client Key Generator
This project provides a tool for securely generating client keys using randomness sourced from the QRN service, and further processed with the WireGuard tool wg.

## Features:
* __Quantum Randomness:__ Leverages the QRN Service to fetch quantum-generated random data, ensuring top-tier entropy.
* __Key Generation:__ Integrates with wg (WireGuard's tool) to produce client private and public keys.
* __Client Management:__ Collects basic client details like name and email during the key generation process.

## Prerequisites:
* Python 3.x installed on your machine.
*  requests library installed. You can install it via pip:
*   ip install requests
*  e WireGuard tool wg should be installed and accessible from the command line.

## Configuration:
Set up your API key from the QRN service as an environment variable named QRN_API_KEY for security purposes. Alternatively, you can replace the placeholder in the code, but this method is not recommended for public repositories.
