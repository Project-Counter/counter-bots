## COUNTER Bots List

This is the official list of user agents that are regarded as robots/spiders by COUNTER Metrics.

## Purpose of this list
Web crawlers and other bots have the potential to inflate usage statistics. Only genuine, user-driven usage should be reported in COUNTER metrics. This is a non-exclusive list that can be used to determine whether a request is performed by a bot.

## Pull requests
This list is open for extension and anyone can make a new pull request with new additions to this list. When proposing new bots it is important to include the bot name and/or pattern, as well as a description of the bot activity.

## Versioning
Merges of changes to the branch will automatically trigger a new official release by the end of the day. A tag with the date is automatically made when a change is released.

## Format of the list
The list is available in a JSON format as well as in a simplified .txt file. 

## Case insensitivity of pattern-matching
We recommend advice case-insensitive matching, to catch any case-specific iterations of bots. For example, if we want to match 'bot', we can be fairly certain that 'BoT' is to be matched as well. Case insensitive matching thus reduces the number of configs to take into consideration.