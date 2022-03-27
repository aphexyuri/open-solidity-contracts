# Open Solidity Contracts
A collection of frequently used/needed Solidity contracts.

## MultiEnglishAuction
A single contract for running unlimited amount of auction.

1. Auction lasts for hours specified at start
2. Participants can bid by depositing ETH greater than the current highest bidder
3. All bidders except the highest bidder can withdraw their bid at any point in time
    
### Post Auction    

1. Highest bidder becomes the new owner of NFT
2. The seller receives the highest bid of ETH

## MultiStageERC721
An ERC721 with:

1. `PAUSED`, `PRE_SALE`, `PUBLIC_SALE` states
2. Capped supply
2. Funcitonalty for token reservations
3. Pre-sale participants list - use `setPresaleParticipants` providing an array of addresses and token allocation
4. Ability to set a once-off provenance hash
