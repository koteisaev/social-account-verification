# Social accounts Verification

This is proposal of an unified mechanism can be used to verify social accounts ownership across social networks 
and decouple account verification from the social media and protocols themeselves 
Following mechanisms expected:

* via `/.well-known/social-accounts.json` file. That JSON file would contain list of social accounts related to organization or company domain represents. 
Specified URL picken with plans to eventually add this URL to https://www.iana.org/assignments/well-known-uris/well-known-uris.xhtml list.
* `WebFinger` support for `acct:` scheme to get details about single account, to be used by a company or organization providing account verification services 
for social networks and other communication platforms where concept of user profiles present and concept of a verified profile can be useful and meaningful.

# Goal of this spec

Goal of this spec to define a common cross-platform mechanism to describe a proof that a social account is an official account of a government official, 
elections candidate, NGO, international organization, public figure, goverenment-affiliated media, company, media outlet, brand or celebrity, expert, 
or just a citizen who want get verification status for sake of prevent spoofing of his digital identity.

This mechanism must be provided in a way to unify verification process and make verification criterias transparent and unified, without obscure mentions of "newsworthy" 
and other non-trunsparent criteria.

This spec defines verification mechanism to be used by multiple providers of verificaiton service. It is possible that some of verification providers that can be an NGO, 
a commercial company, a government institution or international organization itself.

This spec also should provide a recommendation for a ways to provide a clear visual markets of verified status of accounts, to be shown at profile page and/or as part of 
an activity visualizer in some activity stream, list, feed, or other context where account has been referenced or mentioned.
