# Google Ads Agent

A deployment framework for Google Ads and Sklik campaigns via their APIs. The
workflow is brief-driven: fill in a structured brief, dry-run it, then deploy.

## What it does

- **Ten campaign types** across both platforms, including Search, Dynamic Search,
  Performance Max, Display, Shopping, Video and Demand Gen.
- **Brief first, deploy second.** Campaign structure is written down and reviewed
  as a document before anything is created in an ad account.
- **Dry run by default.** The run that shows what would be created is separate
  from the run that creates it, because a mis-scoped campaign spends real money.
- **Created paused.** Nothing starts serving until a human turns it on.
- **Two platforms, one brief format**, so a Czech account on Sklik and a Google
  Ads account are set up from the same source of truth.

## Code

This repository holds the description. The implementation lives in a private
repository.

Happy to walk through how it is built: **[jakubjamny.com](https://jakubjamny.com)**

## License

MIT, see [LICENSE](LICENSE).
