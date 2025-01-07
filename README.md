4e0a87e29b3a1ace54ec8b1393e8b69f548c423d# TON DNS Smart Contracts

Smart contracts of ".ton" zone.

`nft-collection.fc` - DNS resolver and domains minter.

Implements NFT collection interface with offchain NFT collection metadata.

Item index is sha256 hash of domain name and is out of order (`get_collection_data` always return `next_item_index = -1`).

`nft-item.fc` - Domain.

Implements editable NFT item interface with onchain NFT metadata.

Auction functionality is built into the domain item.