# Qualtera

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

Qualtera was a French software company (founded 2010, backed by Serena) that built high-volume big
data analytics platforms for semiconductor test and manufacturing — real-time observability,
traceability and production control over test and assembly data for IDMs, foundries and OSATs,
including the SiliconDash decision-support product. **Synopsys acquired Qualtera on June 10, 2020**
and folded its analytics into Yield Explorer and TestMAX, now part of Synopsys Silicon Lifecycle
Management.

There is no Qualtera API surface left to profile. `qualtera.com` is delegated to Synopsys
nameservers and 301-redirects every path — including `/.well-known/agent-card.json`,
`/openapi.json` and `/llms.txt` — to
<https://www.synopsys.com/solutions/silicon-lifecycle-management.html>, and `https://qualtera.com`
fails the TLS handshake outright. No package exists on npm, PyPI, RubyGems or crates.io under this
name. This profile is retained as a historical record (`x-coverage: none / defunct`); any live
analytics API belongs to Synopsys and is profiled there.

Source: portfolio company of [serena](https://github.com/api-evangelist/serena) — https://www.serena.vc/portfolio-profile/qualtera/
