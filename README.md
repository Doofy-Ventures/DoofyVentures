DOOFY VENTURES TOKEN (DVT) Smart Contract
This repository contains the Solidity code for DOOFY VENTURES TOKEN (DVT), an ERC20 token built on the Binance Smart Chain (BSC). The contract introduces features such as sales fees, a burn mechanism, and customizable exemptions for specific addresses.

Features:
ERC20 Standard: Implements the fundamental ERC20 functions for transferring, minting, and approving tokens.
Burn Mechanism: A configurable burn mechanism that burns 1% of each transaction's value from the sender's balance until a maximum burn limit of 25% of the total supply is reached.
Sales Fees: A sales fee can be applied to transactions involving a decentralized exchange (e.g., PancakeSwap). The percentage is configurable up to a maximum of 25%.
Exemption System: Specific addresses can be exempted from the sales fees or excluded from the burn mechanism.
Admin Controls: The owner of the contract has full control over:
Setting and updating the sales fee percentage and sales fee wallet.
Exempting certain addresses from sales fees.
Whitelisting addresses that will not participate in the burn process.
Contract Details:
Token Name: DOOFY VENTURES TOKEN
Symbol: DVT
Decimals: 18
Initial Supply: 10,000,000,000 DVT
Functions:
Transfer Function: Transfers tokens between accounts while applying the appropriate burn percentage and sales fee.
Burning: Burns tokens from the sender's balance during transactions based on a 1% rate, with a maximum burn of 25% of the total supply.
Admin Functions:
Set the sales fee percentage (up to 25%).
Set the sales fee wallet.
Exempt specific addresses from the sales fee or burn mechanism.
How to Use:
Deploy: Use any Solidity compiler, such as Remix or Hardhat, to compile and deploy the contract to a supported network like Binance Smart Chain.
Configure: Use the owner functions to set the sales fee, manage exemptions, and update the sales fee wallet as needed.
Interact: Utilize the standard ERC20 functions such as transfer, approve, transferFrom, etc., for interacting with the token.
