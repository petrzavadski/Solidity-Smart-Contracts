# Ethereum (Solidity) Smart Contracts 

`Solidity backend programming and ethereum core concepts.`

`Complete deceptralize application.`

## Auction

- Any person who sells something is the owner of auction.
- The auction are having owner , start and end date.
- Major mission of owner is to start and finish auction after specific amount of time.
- Anyone exclude owner can bid. The bidding is process of sending specific amount of ethereum that will be stored to mapping variable.
- Contract will correct bid due to  maximum bid plus increment.
- highestBindingBid is the selling price and highestBidder is the person who won the auction.
-After the auction come to the end the owner gets highestBindingBid and others will get there bidding money back.

## Lottery

- Organizer is collectiong money from players. And then randomly select player called winner that eventually getted rewarded and others are lossing there money.
- Anyone can send fix amount of ether (0.1 ETH) and this amount is saved in array called players. Like lottery ticket.
- Each paticipant can try unlimited number times to increase probability to win. 
- There is account that owns the loterry contract named lottery manager. 
- Lottery manager can randomly peack one winner if there is at least 3 players that were transfer there money.
- All prize-fund will be autimatically withdraw to the winner. Others will be lose there money. After this lottery will be reseted and ready to start with initial point.
