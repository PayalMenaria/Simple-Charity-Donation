# Charity Donation Pool

This is a simple Solidity smart contract for a charity donation pool with an owner-controlled withdrawal mechanism. It allows users to donate funds, while only the contract owner can withdraw them.

## Features
- Users can donate Ether to the contract.
- The contract owner can withdraw funds.
- The total donations are tracked.
- Secure access control using the `onlyOwner` modifier.

## Deployed Contract
- **Network:** Edu Chain
- **Deployed Address:** `0x4487986e370C2c17973B80A4a2A796D022F168b3`

## How to Use
1. Send Ether to the contract address to donate.
2. The owner can call the `withdraw` function to withdraw funds.
3. Use `getBalance` to check the contract balance.

## License
This project is licensed under the MIT License.

