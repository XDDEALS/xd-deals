# Data Available on XD.deals

XD.deals combines game metadata, pricing data, store information, subscription data and compatibility information in a searchable catalogue.

This document describes information that can be visible on public XD.deals pages. It is not an API specification and does not imply that the full database is available for bulk download.

The exact fields available depend on the game, platform, store, source and region.

## Game catalogue

The public XD.deals catalogue contains more than 200,000 games, DLCs and bundles.

Users can search directly or browse the catalogue using filters and sorting:

https://xd.deals/games/browse

Depending on the title, game data may include:

- title
- release date
- developer
- publisher
- genres
- tags
- features
- product type
- age rating
- supported platforms
- related DLC
- bundles
- rating information
- current lowest offer

Not every game has every field.

## Pricing data

An XD.deals offer may include:

- current price
- regular or reference price
- discount percentage
- store
- seller category
- offer recency
- DRM or activation platform
- region restrictions
- availability
- historical low status

Multiple stores can be shown for the same game so users can compare current offers.

## Historical pricing

Where historical data is available, XD.deals can show:

- price history
- recorded historical low
- store associated with a historical low
- date associated with a historical low
- official store historical value
- keyshop historical value

Historical pricing represents observations recorded by XD.deals.

## Store data

XD.deals separates stores into broad categories.

### Official stores and authorized retailers

These can include:

- platform stores
- publisher stores
- authorized digital retailers

Examples visible across XD.deals include Steam, Epic Games Store, GOG, PlayStation Store and Microsoft Store.

### Keyshops and marketplaces

These are third-party sellers or marketplaces offering digital activation keys.

Store context can include ratings, reviews and other information useful when comparing sellers.

## PC and console platforms

XD.deals covers major PC and console ecosystems.

Platform information can include:

- Windows
- PlayStation 4
- PlayStation 5
- Xbox One
- Xbox Series X|S
- Nintendo Switch

Additional platform or compatibility data can include:

- macOS
- Linux
- Android
- iOS
- VR
- Steam Deck
- GeForce NOW

## Xbox Game Pass games

XD.deals can include Xbox Game Pass and PC Game Pass information where available.

This allows users to discover games that may already be included in a Game Pass subscription while also comparing normal purchase offers.

Subscription availability can change, so Microsoft remains the final source for the current Game Pass catalogue.

## PlayStation Plus games

XD.deals can include PlayStation Plus information where available.

This gives users another way to check whether a PlayStation game may already be accessible through a subscription.

PlayStation Plus catalogues change over time, so PlayStation remains the final source for current availability.

## EA Play and Ubisoft+

Subscription-related data can also include services such as:

- EA Play
- Ubisoft+

This allows subscription availability to be used as part of game discovery rather than looking only at purchase price.

## GeForce NOW games

GeForce NOW compatibility can appear as platform or compatibility information.

This helps users discover games that are both tracked by XD.deals and marked as compatible with NVIDIA GeForce NOW.

Cloud gaming support can change, so current compatibility should also be confirmed with NVIDIA.

## Steam Deck compatibility

Steam Deck information can be shown where available.

This is useful for users who want to compare prices while also checking whether a game is suitable for Steam Deck.

## DRM and launchers

XD.deals can show or filter activation methods such as:

- Steam
- EA App
- Ubisoft Connect
- GOG
- Epic Games Launcher
- Microsoft Store
- Battle.net
- Rockstar Games Launcher
- PlayStation Network
- Nintendo eShop
- DRM Free
- Other

DRM information matters because two offers for the same title may activate on different services.

## Deals data

The deals catalogue focuses on current offers.

Users can browse deal data using criteria such as:

- price
- discount
- platform
- DRM
- store
- historical low status
- recency
- ending soon status

Browse deals:

https://xd.deals/deals/browse

## Discovery data

XD.deals also organizes games using metadata and ranking signals.

Depending on the page, discovery can include:

- popularity
- wishlists
- ratings
- discounts
- release date
- new releases
- upcoming games
- preorders
- free games
- giveaways
- genre
- developer
- publisher
- subscription
- platform

Rankings are available at:

https://xd.deals/rankings

## Account features

A registered user can use personal features such as:

- XD.deals wishlists
- price alerts
- Steam library synchronization
- Steam wishlist synchronization
- collections
- ignore lists
- comments
- reviews

XD.deals supports registration and sign in through:

- Google
- Facebook
- Steam
- Discord
- Twitch

This document does not describe private user data structures. Account and privacy handling are covered by the official XD.deals policies.

## Regional data

XD.deals operates localized versions for multiple regions and currencies.

Region can influence:

- displayed currency
- available stores
- local prices
- offer availability
- activation restrictions

The official regional websites are listed in [README.md](README.md).

## RSS data

XD.deals provides RSS feeds for its main public content areas:

- News: https://xd.deals/rss.xml
- Games: https://xd.deals/games/rss.xml
- Deals: https://xd.deals/deals/rss.xml

These feeds can be used by compatible feed readers and applications.

## Data limitations

XD.deals aggregates information from external sources, so public data can change.

Important limitations include:

- prices can change after the latest refresh
- offers can expire
- stores can differ by region
- subscription availability can change
- cloud gaming support can change
- product editions can differ between stores
- activation methods can differ
- metadata completeness varies by title
- historical data covers observations recorded by XD.deals

Users should always verify final commercial terms on the destination store before purchase.

## Related resources

- Main website: https://xd.deals/
- Browse games: https://xd.deals/games/browse
- Browse deals: https://xd.deals/deals/browse
- [Methodology](METHODOLOGY.md)
- [FAQ](FAQ.md)
