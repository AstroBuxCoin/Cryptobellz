# 1 token = 1 yaml file
# assetId: policyId + hex-coded token name
# file name: assetId of the token that want to be verified
# all URL needs to be HTTPS

project: Astro Bux Coin $ABX

# among: DeFi, RealFi, GameFi, Meme, Bridge, Metaverse, Wallet, NFT, Oracle, AI, Launchpad, DAO, Stablecoin, Social, Media, Risk Ratings, Index Vaults, DePIN, Other
categories:
  - DeFi -Bridging -SoFi -Ecommerce 

# needs to be the same as decimals in Cardano Token Registry or CIP-68
decimals: 9

# optional, among: website, twitter, discord, telegram, coinMarketCap, coinGecko
socialLinks:
  website: https://astrobux-landing.web.app/
  discord: https://discord.gg/CKqBzgfP
  twitter: https://x.com/astrobuxcoin?s=11

verified: true # default true, if a token violate verification policy then switch to false

# the following fields are not required
# for `number`, it's token number with no decimals. For example, if your token has a max supply of 50,000,000 tokens with 6 decimals, the value needs to be 50000000 × 10^6 = 50000000000000
# for URL, it must also return the token number without decimals
maxSupply: 40000000000
# or
maxSupply: https://...

treasury:
  - 170000000000
  - addr1qys30unn63qec630a5rrruvdt6lha7jjt6lrcml9yjmkseqj2hclg0prrv2apjuhr7w540dm60xu46p20lwysqwjvy8qk4xc4t
  - stake1uyf9tu058s33k9wsewt3l822hkaa8nw2aq48lhzgq8fxzrsylgnfp
  - https://astrobux-landing.web.app/
  - ABX

burn:
  - 2155380000
  - addr1q8v896z0yjrys3n290e3xsyq6fegvdz3ve8ftlwm0cnazx8xdqu0lhwdx4sm354le5yj7qpadhv7qlqp64ex2thr3zjqydkljm
  - stake1u8nxsw8lmhxn2cdc62lu6zf0qq7kmk0q0sqa2un99m3c3fqm020x3
  - https://astrobux-landing.web.app/
  - ABX

circulatingOnChain:
  - 500000000
  - addr1q89lpau8ruxveucqe43e504lx7vxtk23tyyjhrg934pyy35kmsaaq6vu338ru0sqnl4hqk9amtaxywt5rqzuu65mevsshsulrp
  - stake1uxtdcw7sdxwgcn378cqfl6mstz7a47nz896pspwwd2dukgghefacu
  - https://astrobux-landing.web.app/
  - ABX