# XD.deals Price Comparison Methodology

This document explains how XD.deals presents game prices, stores, historical pricing and related information.

It describes the public service and its user-facing behavior. It is not a specification of internal infrastructure.

## Price aggregation

XD.deals collects pricing information from external stores and marketplaces and groups comparable offers for the same game.

An offer may include:

- current price
- regular or reference price
- discount percentage
- store name
- official store or keyshop classification
- DRM or activation platform
- region restrictions
- update recency
- historical low information

Users can compare offers without opening every retailer separately.

## Price freshness

Game prices can change quickly during seasonal sales, short promotions and key marketplace changes.

XD.deals public pages describe price monitoring as real-time. In practice, different data sources and internal processes may refresh at different times, so the service should be treated as a near real-time comparison layer.

The destination store is always the final source for the checkout price and availability.

## Official stores and authorized retailers

Official store coverage can include:

- first-party platform stores
- publisher stores
- authorized digital retailers

Examples visible across XD.deals include Steam, Epic Games Store, GOG, PlayStation Store, Microsoft Store and other authorized PC retailers.

## Keyshops and marketplaces

XD.deals also compares offers from keyshops and third-party marketplaces.

These offers can sometimes be cheaper, but users should also review:

- seller reputation
- activation region
- buyer protection
- refund policy
- key validity
- product restrictions

XD.deals keeps official store and keyshop offers identifiable so users can decide which seller type they prefer.

## Current price and discount

Where the required data is available, XD.deals can show:

- current price
- regular or reference price
- discount percentage

A large discount does not always mean that the game is at its lowest recorded price.

For that reason, price history and historical lows provide additional context.

## Price history

Price history helps users understand how a game's recorded price changed over time.

Where historical data is available, XD.deals can help answer questions such as:

- Is the current price typical?
- Has the game been cheaper before?
- Is the current discount close to a previous low?
- Are official store prices different from keyshop prices?

Historical data represents prices recorded by XD.deals. It should not be treated as proof that every temporary price from every store was captured.

## Historical lows

A historical low is the lowest price recorded by XD.deals within the relevant historical data.

Where available, XD.deals can show separate historical lows for official stores and keyshops.

The platform may also show:

- the recorded low price
- the store associated with that low
- the date associated with that low

A historical low therefore means the lowest price recorded by XD.deals in the relevant data set.

## Wishlists

Users can create wishlists on XD.deals and use them to track games they are interested in.

Users can also connect Steam and synchronize their game library and Steam wishlist.

This makes it easier to keep owned games and wanted games organized without manually rebuilding the same list.

## Price alerts

A price alert is based on a user-defined target price.

The process is simple:

1. Select a game.
2. Set a target price.
3. XD.deals continues monitoring tracked offers.
4. When an eligible offer reaches or falls below the target, XD.deals can send a notification.

This allows users to wait for a better price without repeatedly checking the same game.

## Subscriptions

XD.deals can also show subscription availability where the relevant data exists.

Examples include:

- Xbox Game Pass
- PC Game Pass
- PlayStation Plus
- EA Play
- Ubisoft+

This adds useful context because a user may not need to buy a game if it is already included in a subscription they use.

Subscription catalogues change over time. The subscription provider remains the final source for current availability.

## GeForce NOW and cloud gaming

GeForce NOW compatibility can be shown as platform or compatibility data.

This helps users discover games that are tracked by XD.deals and are also marked as available through NVIDIA's cloud gaming service.

Cloud gaming support can change, so NVIDIA remains the final source for current GeForce NOW compatibility.

## Regional prices and currencies

XD.deals operates localized versions for multiple markets.

Region can affect:

- currency
- store availability
- local price
- product availability
- taxes
- activation restrictions
- regional promotions

A price shown for one region should not automatically be assumed to apply in another.

Official regional websites are listed in [README.md](README.md).

## DRM and activation platforms

Two offers for the same game can activate on different platforms.

XD.deals can show or filter DRM and launcher information such as:

- Steam
- Epic Games Launcher
- GOG
- Ubisoft Connect
- EA App
- Microsoft Store
- Battle.net
- Rockstar Games Launcher
- PlayStation Network
- Nintendo eShop
- DRM Free
- Other

Users should verify activation requirements before buying.

## Deal discovery

XD.deals supports several ways to browse current offers, including:

- best deals
- new deals
- historical lows
- ending soon offers
- price thresholds
- discount thresholds
- platform filters
- store filters
- DRM filters

Browse deals:

https://xd.deals/deals/browse

## Rankings and discovery signals

XD.deals also provides rankings and discovery lists based on specific data points or user activity.

Depending on the page, this can include signals such as:

- wishlists
- ratings
- popularity
- release date
- discount
- sales-related data

Rankings are intended for discovery and should not be interpreted as editorial recommendations unless a page explicitly says so.

## Affiliate relationships

XD.deals participates in affiliate programs and may receive a commission when a qualifying purchase is made through one of its links.

The commission does not increase the purchase price paid by the user.

An affiliate relationship does not make XD.deals the seller. The transaction remains between the user and the destination store.

## Final store verification

XD.deals is a comparison service. External stores control the final transaction.

Before buying, users should verify:

- final price
- currency
- taxes
- game edition
- DRM
- activation region
- availability
- refund policy
- payment methods

## Limitations

External offers can change independently of XD.deals.

Users should keep in mind that:

- a store can change or remove an offer at any time
- checkout price can differ because of taxes or currency conversion
- different stores can sell different editions
- keys can be region restricted
- subscription catalogues can change
- cloud gaming support can change
- historical data is limited to prices recorded by XD.deals
- not every metadata field is available for every game

## Related documentation

- [README.md](README.md): product overview
- [DATA.md](DATA.md): data and taxonomy
- [FAQ.md](FAQ.md): common questions

Official website: https://xd.deals/
