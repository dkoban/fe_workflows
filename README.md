# Feasibility of conducting accuracy prime experiments on platforms other than Twitter

## Reddit

It is possible to replicate the accuracy prime experiment on Reddit, but shadow bans and user restrictions on direct messaging would make it difficult to interact with users.  Identifying users of interest and monitoring activity is easy; interacting with users is not. Automated accounts may need to generate karma to post on some reddits. Karma farming does not appear to be banned, but it often can result in accounts being banned.

## Telegram

The lack of information about post authors and individual user activity makes it infeasible to replicate an accuracy primes experiment on Telegram. We could search for links from untrustworthy websites across a large number of channels, but we would not be able to view who posted the links for most channels due to privacy settings. Likewise, we cannot query the API to retrieve the posting history of individual accounts. We must collect activity across numerous channels and will only be able to view the posting author on a small subset of channels.

Creating bots is relatively easy in that we don't have to formally request authorization to create them. However, bot accounts are limited in the actions they can perform. Bots cannot join channels; bots must be added to channels by administrators. Bots cannot initiate a chat conversation with other users.

## Gab

It is possible to replicate the accuracy prime experiment on Gab, but all interactions would have be done manually. Since the native search function only allows for hashtag-based searching, identifying posts that contain specific URLs would require us to retrieve large volumes of posting activity and use regex to search the downloaded data. Likewise, extensive development work would be needed to pull complete network data via the Gab API.

## Twitter

Code to replicate the original study is provided in `twitter.ipynb`.