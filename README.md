# REVIEWS.io (reviews-io)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

REVIEWS.io is a product and company reviews and user-generated content (UGC) platform that helps brands collect, manage, and display verified customer reviews. Its REST API (https://api.reviews.io) lets developers queue review invitations, retrieve product and company reviews, fetch ratings and widget data, manage questions, and subscribe to webhooks using store + apikey authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/reviews-io/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/reviews-io/refs/heads/main/apis.yml)

## Tags

- Reviews
- UGC
- Ratings
- Reputation
- eCommerce

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### REVIEWS.io Invitations / Collect API

Queue product and company review invitations via email or SMS, list queued invitations, and edit pending invitations to collect verified reviews from customers after a purchase.

- **Human URL:** [https://developer.reviews.io/reference/product-review-invitations](https://developer.reviews.io/reference/product-review-invitations)
- **Base URL:** `https://api.reviews.io`

#### Tags

- Invitations
- Collect
- Email
- SMS

#### Properties

- [Documentation](https://developer.reviews.io/reference/product-review-invitations)
- [API Reference](https://developer.reviews.io/reference)
- [OpenAPI](openapi/reviews-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/reviews-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reviews-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### REVIEWS.io Product Reviews API

Retrieve product reviews by SKU or MPN with rich filtering, create new product reviews, and add to the helpful-vote count of an individual product review.

- **Human URL:** [https://developer.reviews.io/reference/09a10508634b01f463d1beacf3471b6a](https://developer.reviews.io/reference/09a10508634b01f463d1beacf3471b6a)
- **Base URL:** `https://api.reviews.io`

#### Tags

- Product Reviews
- Reviews
- eCommerce

#### Properties

- [Documentation](https://developer.reviews.io/reference/09a10508634b01f463d1beacf3471b6a)
- [API Reference](https://developer.reviews.io/reference)
- [OpenAPI](openapi/reviews-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/reviews-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reviews-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### REVIEWS.io Company Reviews API

Retrieve company (merchant) reviews for a store, including ratings, review bodies, author details, and pagination for building reputation displays and reports.

- **Human URL:** [https://developer.reviews.io/reference](https://developer.reviews.io/reference)
- **Base URL:** `https://api.reviews.io`

#### Tags

- Company Reviews
- Merchant Reviews
- Reputation

#### Properties

- [Documentation](https://developer.reviews.io/reference)
- [API Reference](https://developer.reviews.io/reference)
- [OpenAPI](openapi/reviews-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/reviews-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reviews-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### REVIEWS.io Ratings / Widgets API

Retrieve aggregate product ratings, basic review statistics, review nuggets, and user-generated content used to build star ratings, badges, and on-site display widgets.

- **Human URL:** [https://developer.reviews.io/reference](https://developer.reviews.io/reference)
- **Base URL:** `https://api.reviews.io`

#### Tags

- Ratings
- Widgets
- Statistics

#### Properties

- [Documentation](https://developer.reviews.io/reference)
- [API Reference](https://developer.reviews.io/reference)
- [OpenAPI](openapi/reviews-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/reviews-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reviews-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### REVIEWS.io Questions API

Create new customer questions and retrieve a combined feed of reviews and questions for custom-built filtering and on-page question-and-answer displays.

- **Human URL:** [https://developer.reviews.io/reference](https://developer.reviews.io/reference)
- **Base URL:** `https://api.reviews.io`

#### Tags

- Questions
- Q&A
- UGC

#### Properties

- [Documentation](https://developer.reviews.io/reference)
- [API Reference](https://developer.reviews.io/reference)
- [OpenAPI](openapi/reviews-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/reviews-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reviews-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### REVIEWS.io Webhooks API

Subscribe to review-submitted webhooks (company and product, positive and negative variants) and list configured webhooks to push review data into your systems in real time.

- **Human URL:** [https://developer.reviews.io/reference/2966f9313240bd3856bb4045dac3731f](https://developer.reviews.io/reference/2966f9313240bd3856bb4045dac3731f)
- **Base URL:** `https://api.reviews.io`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://developer.reviews.io/reference/2966f9313240bd3856bb4045dac3731f)
- [API Reference](https://developer.reviews.io/reference)
- [OpenAPI](openapi/reviews-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/reviews-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reviews-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/reviewscouk)
- [LinkedIn](https://www.linkedin.com/company/reviews-io)
- [Website](https://www.reviews.io)
- [Documentation](https://developer.reviews.io/reference)
- [Plans](plans/reviews-io-plans-pricing.yml)
- [Rate Limits](rate-limits/reviews-io-rate-limits.yml)
- [Fin Ops](finops/reviews-io-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
