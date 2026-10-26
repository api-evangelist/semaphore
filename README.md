# Semaphore (semaphore)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Semaphore is a cloud-based CI/CD platform designed for high-performance engineering teams, providing fast and reliable continuous integration and continuous delivery pipelines. The platform offers a comprehensive REST API that enables programmatic management of pipelines, workflows, jobs, secrets, projects, and deployment targets for software delivery automation. Semaphore supports OAS 3.0-compliant API definitions with Swagger documentation, covering resources such as artifacts, test results, self-hosted agents, and build insights. Teams can use the API to integrate with external tools, build custom interfaces, trigger promotions, and automate their entire software delivery lifecycle.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/semaphore/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=semaphore-api-evangelist&utm_content=repo

## Tags

- CI/CD
- Continuous Integration
- Continuous Delivery
- Pipelines
- Workflows
- DevOps
- Build Automation
- Software Delivery
- Deployment
- Artifacts

## APIs

| Name | Description | Human URL | Base URL |
|------|-------------|-----------|----------|
| Semaphore API | REST API for managing CI/CD pipelines, workflows, jobs, deployment targets, artifacts, and test results with OAS 3.0 compliance | https://semaphore.io/product/api | https://{organization}.semaphoreci.com/api/v1alpha |

## Plans, Rate Limits, and FinOps

| Resource | File |
|----------|------|
| Plans and Pricing | [plans/semaphore-plans-pricing.yml](plans/semaphore-plans-pricing.yml) |
| Rate Limits | [rate-limits/semaphore-rate-limits.yml](rate-limits/semaphore-rate-limits.yml) |
| FinOps | [finops/semaphore-finops.yml](finops/semaphore-finops.yml) |

**Pricing Summary:** Pay-as-you-go compute from $0.003/min (Ubuntu ARM 2vCPU) to $0.09/min (macOS). Free tier includes $15/month credits (~2,000 Ubuntu x64 2-vCPU minutes). Optional support plans from $50–$750/month.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://semaphore.io |
| Documentation | https://docs.semaphore.io |
| GitHub Org | https://github.com/semaphoreci |
| LinkedIn | https://www.linkedin.com/company/semaphore-software |
| Blog | https://semaphore.io/blog |
| Pricing | https://semaphore.io/pricing |
| Status Page | https://status.semaphore.io |
| X | https://twitter.com/semaphoreci |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
