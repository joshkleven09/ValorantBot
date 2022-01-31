# ValorantBot
## Usage

The bot should have role that allows it to send messages and create custom emojis.

- Login using `/login`
- Show information about your current match `/match`
- Get your daily shop using `/shop`, only visible to you
- Get your daily shop using `/shop-share`, visible to channel
- Set alerts using `/alert`
- Manage your alerts using `/alerts`
- Show your Valorant Points & Radianite using `/balance`

By default, the bot doesn't store your username/password, it only uses them to get the cookies that can be used to generate access tokens needed to get your shop.  
You can log in using [your auth.riotgames.com cookies](https://github.com/giorgi-o/SkinPeek/wiki/How-to-get-your-Riot-cookies) using `/cookies` to avoid sending your password, and you can delete your account from the bot using `/forget`.  
Obviously, only log in if you trust whoever is hosting the bot, as they can theoretically do anything with your account.  

## Acknowledgements

- Forked from [SkinPeek](https://github.com/giorgi-o/SkinPeek) for the shop and shop alert functionality
- Match up idea from [WAIUA](https://github.com/Soneliem/WAIUA)
- [Valorant-api](https://dash.valorant-api.com/) for images
