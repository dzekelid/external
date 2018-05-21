---
name: Stripe
x-slug: stripe
description: 'Stripe is a simple, developer-friendly way to accept payments online.
  They believe that enabling transactions on the web is a problem rooted in code,
  not finance, and they want to help put more websites in business. '
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
x-kinRank: "10"
x-alexaRank: ""
tags: External
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/stripe/apis.md
specificationVersion: "0.14"
apis:
- name: Stripe Get Account External Accounts
  x-api-slug: stripe
  description: Get Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/external_accounts
  tags: Account, External, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/stripe/accountexternal-accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/stripe/accountexternal-accounts-get-openapi.md
- name: Stripe Add Account External Accounts
  x-api-slug: stripe
  description: Post Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/external_accounts
  tags: Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/stripe/accountexternal-accounts-post-openapi.md
- name: Stripe Delete Account External Accounts
  x-api-slug: stripe
  description: Delete Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/external_accounts/{id}
  tags: Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/stripe/accountexternal-accountsid-delete-openapi.md
- name: Stripe Get Account External Accounts
  x-api-slug: stripe
  description: Get Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/external_accounts/{id}
  tags: Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/stripe/accountexternal-accountsid-get-openapi.md
- name: Stripe Add Account External Accounts
  x-api-slug: stripe
  description: Updates the metadata of a bank account belonging to a Custom account,
    and optionally sets it as the default for its currency. Other bank account details
    are not editable by design.You can re-enable a disabled bank account by performing
    an update call without providing any arguments or changes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///account/external_accounts/{id}
  tags: Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/stripe/accountexternal-accountsid-post-openapi.md
- name: Stripe Get Accounts Account External Accounts
  x-api-slug: stripe
  description: Get Accounts, Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/external_accounts
  tags: Accounts, Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/stripe/accountsaccountexternal-accounts-get-openapi.md
- name: Stripe Add Accounts Account External Accounts
  x-api-slug: stripe
  description: Post Accounts, Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/external_accounts
  tags: Accounts, Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/stripe/accountsaccountexternal-accounts-post-openapi.md
- name: Stripe Delete Accounts Account External Accounts
  x-api-slug: stripe
  description: Delete Accounts, Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/external_accounts/{id}
  tags: Accounts, Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/stripe/accountsaccountexternal-accountsid-delete-openapi.md
- name: Stripe Get Accounts Account External Accounts
  x-api-slug: stripe
  description: Get Accounts, Account, External, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/external_accounts/{id}
  tags: Accounts, Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/stripe/accountsaccountexternal-accountsid-get-openapi.md
- name: Stripe Add Accounts Account External Accounts
  x-api-slug: stripe
  description: Updates the metadata of a bank account belonging to a Custom account,
    and optionally sets it as the default for its currency. Other bank account details
    are not editable by design.You can re-enable a disabled bank account by performing
    an update call without providing any arguments or changes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///accounts/{account}/external_accounts/{id}
  tags: Accounts, Account, External, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/stripe/accountsaccountexternal-accountsid-post-openapi.md
- name: Stripe
  x-api-slug: stripe
  description: Web and mobile payments, built for developers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: External
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/external/master/_listings/stripe/openapi.md
x-common:
- type: x-base
  url: https://api.stripe.com/
- type: x-blog
  url: https://stripe.com/blog
- type: x-blog-rss
  url: https://stripe.com/blog/feed.rss
- type: x-change-log
  url: https://stripe.com/docs/upgrades
- type: x-crunchbase
  url: http://www.crunchbase.com/company/stripe
- type: x-github
  url: https://github.com/stripe
- type: x-pricing
  url: https://stripe.com/us/pricing
- type: x-twitter
  url: https://twitter.com/stripe
- type: x-website
  url: https://stripe.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---