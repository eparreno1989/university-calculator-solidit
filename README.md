# University Calculator - Smart Contract 🎓

This is a lightweight smart contract developed in Solidity designed to handle university grade calculations with built-in access control and security patterns.

## 🛠️ Features Implemented
- **Access Control:** Restricts sensitive operations (like calculating averages) exclusively to the contract administrator (`admin`) using custom conditional routing.
- **Math Safety:** Prevents EVM integer underflow errors by validating subtraction limits via `require` statements.
- **Standard Formatting:** Documented entirely in technical English using Ethereum's NatSpec syntax (`@notice`) for clear interface specification.

## ⚙️ Tech Stack & Tools
- **Language:** Solidity (^0.8.0)
- **Environment:** Remix IDE
- **Compiler:** EVM Shanghai / Paris compliant
