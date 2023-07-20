# igd-challenge
dapp that allows connected users to issue invoices as NFTs on the Sepolia testnet

# Instructions
1. Access the website via url: https://wagmi-invoices.vercel.app
2. Connect your wallet via WalletConnect on the top right of the navbar
3. Once connected, a form will appear with all the inputs required for the invoice to be issued
4. After the wallet has been connected, switch over to the Sepola testnet instead of the mainnet
5. Fill in all of the inputs and click the 'issue invoice' button to call the issueInvoice function of the smart contract
6. The 'issue invoice' button will be disabled if inputs are left empty/blank
7. A pop-up window will appear in your wallet to sign the transaction
8. Once the transaction has been confirmed on the blockchain, the invoice details will be displayed below alongside the tx link
9. The details of the invoice can be accessed directly on etherscan as well using the tokenID, which will be the name of the NFT (e.g. InvoiceToken #11)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

- I was looking into storing the NFT metadata on IPFS using Pinata and would have implemented the file upload (attach document) if I had more time to work on the project
