# Simple Hotel Booking Application using Blockchain

Online Hotel Booking

“2016 was the first year when OTA lodging bookings exceeded total hotel website gross bookings,” further adding the forecast for the year of 2018: “hotels continue to ratchet up the pressure on online intermediaries.”

Why should we use blockchain for hotel booking ?

- Independent hotels have complained about the unfairly high commissions charged by Online Travel Agents (OTAs), such as Booking, Expedia, Agoda, Tophotels, LateRooms and more. According to hoteliers, their rates make up as much as 25% of the booking revenue per guest.
- The intermediates can be removed thus reducing the cost by about 30 %.
Even in the context of automation (automatic update of room availability on the hotel’s website), many booking phases are run manually and are thus ineffective and unreliable.
- Blockchain brings “transparency and honesty to the review system,” meaning vendors cannot pay for manipulated feedback and only genuine customers can leave remarks. There will be no fake reviews.

About the Project

This is just a simple block chain application or a simple example application for booking hotels using block chain. 
The operations involved are 
- Booking a hotel by spending some ethers
- The amount will be debited from the buyers metamask account and will be transfered to the owner's metamask account

Technologies Used

Front end : Html, Css and JS

Smart Contract Code (Business Logic) : Solidity , Truffle Framework

Block chain : Ganache

DAPP : Web3

Steps for Configuration

- Install and Launch Ganache https://truffleframework.com/ganache
- Install Truffle Framework https://truffleframework.com/docs/truffle/getting-started/installation
- Go to the poject folder and compile the project using
Cmd -> rm -r build/
Cmd -> truffle compile
Cmd -> truffle migrate --reset --all
- Run the aplication using 
Cmd -> npm run dev

Steps for Booking a Room using Blockchain

- Launch the application in a browser with Metamask extension. (https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en)
- Import any ethereum account to metamask or create a new account and add some ethers.
- Book a room by selecting room and pressing the book room button
- Metamask will ask for a confirmation to debit the price of the room from your account, make sure that you have that minimum ether in your account along with the gas cost for the transaction.
- Room will be booked, the status of the room will change and the amount will be send to the owners account.

References and Materials for Learning Blockchain Development

1. https://medium.com/@credits/how-blockchain-could-change-the-hotel-industry-2b84bd77fb93
2. https://cointelegraph.com/news/could-blockchain-booking-system-see-hotel-prices-tumble
3. https://www.mycryptopedia.com/what-is-a-whitepaper/
4. https://medium.com/@blockchain101/9-steps-for-launching-an-ico-104b62b34a3c
5.https://hackernoon.com/ethereum-smart-contracts-in-python-a-comprehensive-ish-guide-771b03990988
6. https://media.consensys.net/how-to-build-a-private-ethereum-blockchain-fbf3904f337
7. https://medium.com/karachain/why-i-am-building-a-blockchain-in-go-6395a60b24dd
8. https://www.devteam.space/blog/how-to-build-a-decentralized-application-dapps/
9. https://medium.com/@mvmurthy/ethereum-for-web-developers-890be23d1d0c
10. https://www.zastrin.com/
11. https://www.zastrin.com/courses/simple-voting-vid/lessons/1-1
12. https://www.youtube.com/watch?v=gSQXq2_j-mw
13. https://steemit.com/ 
14. https://github.com/llSourcell/Your_First_Decentralized_Application
15. https://www.youtube.com/watch?v=XdKv5uwEk5A&t=16s
16. https://github.com/dappuniversity/election
17. https://www.quora.com/What-is-the-difference-between-a-Coin-Ether-a-Token-and-a-Smart-Contract-on-Ethereum
18. https://hackernoon.com/serializing-string-arrays-in-solidity-db4b6037e520
19. https://medium.com/daox/three-methods-to-transfer-funds-in-ethereum-by-means-of-solidity-5719944ed6e9 
20. https://medium.com/coinmonks/smart-contracts-how-to-transfer-ether-ba464ec005c6 
21. https://medium.com/metamask/calling-a-smart-contract-with-a-button-d278b1e76705 
22. https://medium.com/hci-wvu/how-to-build-your-first-%C3%B0app-fe0c89d8f95f 
