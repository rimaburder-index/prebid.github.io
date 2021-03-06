---
layout: bidder
title: TrustX
description: Prebid Trustx Bidder Adaptor
hide: true
biddercode: trustx
media_types: banner, video
gdpr_supported: true
---


### Bid Params

{: .table .table-bordered .table-striped }
| Name        | Scope    | Description                                                                                                                                                                                                         | Example                                   | Type      |
|-------------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------|-----------|
| `uid`       | required | Represents the TrustX bidder system Ad Slot ID associated with the respective div id from the site page.                                                                                                            | `42`                                      | `integer` |
| `priceType` | optional | Can take the values `gross` or `net`, default value is `net`. Net represents the header bid price with the TrustX header bidder margin already extracted. Gross price does contain the TrustX bidder margin within. | `'gross'`                                 | `string`  |
| `keywords`  | optional | A set of key-value pairs applied to all ad slots on the page. Values can be empty.                                                                                                                                  | `keywords: { topic: ['stress', 'fear'] }` | `object`  |
