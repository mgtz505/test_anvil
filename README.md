Stylesheet for the Anvil embedded documents we display in FundAdmin FE iframes. This stylesheet is ingested via the `White-label` settings for a Workflow. A link to the actual CSS must be provided, such as:
```
https://mgtz505.github.io/test_anvil/test.css
```

The stylesheet will eb deployed on every commit via GitHub pages. 

This implementation is a temporary solution as we ultimately want to host these static assets in a dedicated public bucket in S3 (See [this ADR]([url](https://github.com/carta/fund-admin/pull/37776))).
