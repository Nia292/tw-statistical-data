# tw-statistical-data

Statistical data gathered!

## Pippi Wallet Data 

Represents player pippi wallets

Found in "playerWallets".

* clanId is the persistent ID of the clan of the player's character
* charName is the character name of the player's character. This may change over time! If it changes, the wallet contents should be erased, too.
* gold is the parsed gold value
* rawGoldValue is a hexedecimal representation of the gold value
* silver is the parsed silver value
* rawSilverValue is a hexedecimal representation of the silver value
* bronze is the parsed bronze value
* rawBronzeValue is a hexedecimal representation of the bronze value
* server is an enumarted value, either TWEL, TWSIPTAH or TWSW
* timestampUTC is the string representation of the timestamp at which the data was taken (UTC)

## Clan Banker Wallet

Found in "clanBankerWallets"
* ownerId is the persistent ID of the owner, in this case, the clan 
* clanId is the persistent ID of the clan
* gold is the gold value
* silver is the silver value
* bronze is the bronze value
* timestampUTC is the string representation of the timestamp at which the data was taken (UTC)
* server is an enumarted value, either TWEL, TWSIPTAH or TWSW

## Player Banker Wallet

Found in "clanBankerWallets"
* ownerId is the persistent ID of the owner, in this case, the player 
* playerId is the persistent ID of the player
* gold is the gold value
* silver is the silver value
* bronze is the bronze value
* timestampUTC is the string representation of the timestamp at which the data was taken (UTC)
* server is an enumarted value, either TWEL, TWSIPTAH or TWSW

## Players
* playerId is the persistent ID of the player, does not change with name changes
* charName is the name of the character, which might change over time
* level is the character level
* clanId is the persistent ID of the clan the player was in at the time
* lastTimeOnlineTS is a unix timestamp in second, representing the time when the player had last logged in
* clanName is the name of the clan, which may change over time
* timestampUTC is the string representation of the timestamp at which the data was taken (UTC)
* server is an enumarted value, either TWEL, TWSIPTAH or TWSW


