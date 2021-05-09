# ✨ abracadabrahacks-2021 🔮

## Team Members

- Alex Damis
- Peter Dorsaneo
- Adam Fernandes
- Dylan Ochoa
- Marco Spilimbergo

## Our Goal

**Mintsta**: the world's first Instagram NFT minter. We wanted to create an avenue for Insta users to mint their posts into NFTs.

## How We Minted Instagram Posts

1. Instagram's API allowed us to obtain a user authorization's to access their information, which we traded in for short & long term tokens to access posts.
2. We utilized Postman to send an HTTP `GET` request to obtain a user's Instagram posts.
3. We leveraged Minty to mint the post's image, and collected the remaining metadata in a `.json` file which pointed to the minted picture.
4. We pinned the NFT and its metadata on Pinata, which could then be accessed from anywhere where the IPFS protocol worked. (Brave browser natively handles IPFS.)

## Resources

Here is a non-ranked, non-exhaustive list of resources we used during the hackathon.

- [Minty](https://github.com/yusefnapora/minty)
- [Pinata](https://pinata.cloud/)
- [Brave Browser](https://brave.com/)
- [Instagram API](https://developers.facebook.com/products/instagram/apis/)
- [Postman](https://www.postman.com/)
