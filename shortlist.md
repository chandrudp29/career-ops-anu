# Anu C Nanda — Legal Roles Shortlist (product-company focus)
_Generated 2026-08-07 · re-run 2026-08-09 · re-run 2026-09-28. Scores use the rubric in [profile.md](profile.md). Confirm each posting is still live on the company careers page before applying — legal postings rotate fast._
_Salary benchmark: in-house Legal Counsel, Bengaluru ≈ ₹18.5L–₹24.0L ([SalaryAsk](https://www.salaryask.com/salary/legal-counsel/bangalore))._

## ✅ 2026-09-28 ground-truth scan — real career-ops tool, live ATS APIs
Set up `career-ops-anu/portals.yml` with board tokens verified directly against Greenhouse/Lever's JSON APIs (not search snippets), then ran the scanner (`node scan.mjs`). As of 2026-09-28, `career-ops-anu/` is a **full standalone copy** of the career-ops tool (own `node_modules`, `config/profile.yml`, `cv.md`, `modes/_profile.md`, `portals.yml`, `data/`) — completely independent of your own `career-ops/` install. Result:
- **Razorpay, Groww, CRED**: zero legal postings live right now.
- **Meesho**: one real open posting — [Manager - Legal, Bangalore](https://jobs.lever.co/meesho/46754b37-ceb3-4a85-b59d-76b27a453f83), confirmed active Apply button. Needs **5–7 yr PQE** (above her ~3 yr) — CLM/vendor/SaaS/M&A contract work, no DPDP mention. Worth a stretch application given her CRO/MNC contract depth, going in aware of the gap.
- **PhonePe**: their Greenhouse board is currently broken (404 on both the API and the HTML board, even with a browser UA) — a real outage on their end, not a scan failure.
- Swiggy, Flipkart, Zerodha, Navi, ICON, Salesforce, etc. aren't on Greenhouse/Lever/Ashby under an obvious token — not yet covered by this scan; would need a custom parser or websearch fallback (which reintroduces the staleness risk below).

## ⚠️ 2026-09-28 link-verification pass — most prior leads are dead
Checked every specific posting by fetching the actual ATS page (not just search snippets). Result: **every one had already expired**, several months ago in one case. Search engines and aggregator blogs (opportunitycell, lawfoyer, builtin, etc.) keep indexing/serving these long after the real posting is pulled — don't trust a search summary saying a role "appears active" without opening the real page and checking for an explicit expired/closed banner.

| Posting | Verified status |
|---|---|
| ICON — Legal Counsel CRO/Pharma, Bangalore (jid-38083) | **Expired.** Page shows "This vacancy has now expired." |
| ICON — alternate Legal Counsel listing (jid-16677) | Also expired; was Dublin, not Bangalore anyway |
| Razorpay — Associate, Legal (Built In link) | **Dead since Aug 4, 2025** — "Sorry, this job was removed" (over a year stale) |
| Razorpay — Associate Manager, Legal, 5–7 yr (Greenhouse 4511746005) | Link now redirects to the general 25-job board; posting no longer resolves directly |
| PhonePe — Associate Manager, Legal and Secretarial (opportunitycell) | **404** on the underlying Greenhouse job ID — removed from the ATS entirely |
| Swiggy — Legal Counsel II Compliance (LawFoyer) | Unverifiable — page is paywalled, no application link exposed |

**Current live PhonePe legal board** (checked directly, 2026-09-28): only "Manager/Senior Manager – Company Secretary, Legal" — **7–9 yr PQE + ICSI membership required** — too senior for her.
**Current live Razorpay legal board**: general listing shows a legal-adjacent role at 5–7 yr — no 1–3 yr legal role currently posted.

**Bottom line: as of right now, none of the previously-flagged roles are actually open, and no confirmed opening at her exact level exists at these companies today.** This is a point-in-time snapshot problem — legal reqs at this level open and close within days. Manually re-verifying every link each time isn't reliable; see the recurring-scan option below.

## 2026-08/09 history — what changed
- **Flipkart Legal Counsel I** — the posting I had listed closed (deadline was "before Sept 6"). Not resurfacing yet; keep on watchlist.
- **Swiggy Legal Counsel I (Gen Corp)** — no longer surfacing; may be filled/closed. A **new, different** Swiggy role appeared instead: **Legal Counsel II (Compliance), 4–7 yr PQE** — too senior for her (~3 yr), moved to skip.
- **Razorpay Associate, Legal (1–2 yr PQE)** — this role *type* keeps recurring across multiple job boards (Built In, Lawbhoomi, Canonsphere) over 7+ weeks, suggesting Razorpay hires into this band fairly continuously — good signal, still the strongest live bet. Couldn't confirm one exact live posting ID via fetch (Greenhouse job IDs rotate/expire fast) — **check razorpay.com/careers directly** rather than the old link.
- Razorpay **Senior Associate, Legal (4–6 yr)** had an application deadline of 25/9 — likely just closed, and was too senior for her anyway.
- ICON plc (CRO match) not re-verified this round — treat as unconfirmed until checked again.

## Tier 1 — Apply now (product companies, right level)

| Company | Role | Level fit | Why it fits her | Score | Source / status |
|---|---|---|---|---|---|
| **PhonePe** ⭐ | Associate Manager — Legal and Secretarial (Bangalore) | **3–4 yr PQE — exact match** | Board minutes/resolutions, MCA/ROC filings, statutory compliance, Companies Act, FEMA/RBI filings, M&A support — this is functionally the same work as her current "Legal & Company Secretarial" role at Eurofins | ~36 | Confirmed live, [opportunitycell.com](https://opportunitycell.com/associate-manager-legal-and-secretarial-at-phonepe-bangalore/) → apply via PhonePe Greenhouse. **Caveat: lists ICSI (Company Secretary) membership as a qualification — her resume shows Enrolled Advocate + BBA LLB, not ICSI. Worth applying anyway given she does the identical work day-to-day, but flag this gap rather than assume it's not checked.** |
| **Razorpay** | Associate, Legal (Bengaluru) | 1–2 yr floor; she's ~3 → strong | Fintech, end-to-end contract negotiation/drafting/review — her exact CLM strength; RBI/DPDP-adjacent | ~32 | Role type recurs; verify live posting at [razorpay.com/careers](https://razorpay.com/careers/) directly |
| **ICON plc** | Legal Counsel — CRO/Pharma (Bangalore) | 3–5 yr PQE | Reconfirmed live this round. Same-industry (CRO) domain match to her current Eurofins role | ~30 | [ICON careers](https://careers.iconplc.com/job/legal-counsel-cro-pharma-in-india-bangalore-jid-38083) |

## Tier 1 (watch — recently closed, may reopen)
| Company | Role | Status | Source |
|---|---|---|---|
| Swiggy | Legal Counsel I — Gen Corp | Not resurfacing since Aug; check [careers.swiggy.com](https://careers.swiggy.com/) | — |
| Flipkart | Legal Counsel — I (Grade 10) | Deadline passed (~Sept 6); check [flipkartcareers.com](https://www.flipkartcareers.com/) for a reopened req | — |
| PhonePe | — | Last seen role was Manager, Legal (7+ yr, too senior); Associate/Assoc-Manager band still not reopened | — |

## New this round — too senior, skip
| Company | Role | Note |
|---|---|---|
| Swiggy | Legal Counsel II (Compliance) | 4–7 yr PQE required — above her ~3 yr band |
| Salesforce | Senior Corporate Counsel (Bangalore/Gurgaon) | "Senior" title strongly implies 7+ yr; couldn't confirm exact PQE (page is JS-rendered) — low priority unless she wants to try anyway |

## Tier 2 — Check level/JD, apply if it fits
| Company | Role | Note | Source |
|---|---|---|---|
| Nanonets | Legal (Bangalore, SaaS/AI startup) | SaaS contracts fit; startup = broader scope | [Greenhouse](https://job-boards.greenhouse.io/nanonets/jobs/5020276008) |
| Fintech (via recruiter) | Legal Counsel — 12-mo secondment | Mid-level; commercial contracting + data privacy + RBI. Contract not permanent | [Michael Page Bangalore](https://www.michaelpage.co.in/jobs/legal/bangalore) |
| Via Michael Page | Legal Consultant (M&A) · **PQE 3–5 yr · Bengaluru** | NEW (2026-08-09). Exact level match; M&A is adjacent to her core (corporate/contracts), stretch on domain | [MP JN-052026-7013984](https://www.michaelpage.co.in/job-detail/legal-consultant-ma-pqe-3-5-years-bengaluru/ref/jn-052026-7013984) |
| US-based product co (remote) | Legal Counsel — 4–8 yr, contracts + **data privacy** + IP/licensing | NEW (posted 2026-07-01). Above her band but remote + data-privacy-heavy (her edge); worth a stretch apply | [LawFoyer/Flexiple](https://news.lawfoyer.in/remote-legal-counsel-job-opportunity-through-flexiple-for-a-us-based-product-company/) |
| VC firm (Gurugram) | Legal Associate · **2–3 yr PQE · DPDP/DPAs/vendor privacy** | NEW (posted 2026-06-19). Perfect level + DPDP match, BUT Gurugram not Bengaluru — only if open to relocate/remote | [LawFoyer](https://news.lawfoyer.in/legal-associate-opportunity-at-stride-ventures-gurugram/) |

## Skip — too senior for ~3 yr PQE
- Wipro Corporate Counsel (7+ yr, also IT-services not product)
- Flipkart Legal Counsel II (6–8 yr) · Swiggy Legal Counsel II · Razorpay Senior Associate/Senior Manager Legal
- **PhonePe Manager, Legal (7+ yr)** — new posting, too senior
- Hitachi Senior Legal Counsel · Vahura India Legal Counsel (10–12 yr) · MP Legal Counsel IT Contracts (5+ yr)

## Target-company watchlist (product cos with Bengaluru legal teams — check careers pages weekly)
Fintech/consumer: Razorpay · PhonePe · CRED · Groww · Zerodha · Navi · Meesho · Swiggy · c
Global product w/ Blr legal: Google · Microsoft · Amazon · Walmart Global Tech · Adobe · Salesforce · Atlassian · Nutanix · Intuit · Cisco

## Aggregators to run weekly
- [foundit.in — legal Bengaluru](https://www.foundit.in/search/legal-jobs-in-bengaluru-bangalore) (24k+ listings)
- [Naukri — Razorpay](https://www.naukri.com/razorpay-jobs) · [productbased.in](https://www.productbased.in/) (Flipkart/Razorpay/CRED product jobs)
- [Michael Page — legal Bangalore](https://www.michaelpage.co.in/jobs/legal/bangalore) (recruiter; good for in-house mid-level)
- LinkedIn: "Legal Counsel" Bengaluru, past 24h · legal recruiters Vahura & iimjobs (India in-house legal)

## Two things she should lead with (her differentiators)
1. **DPDP Act 2023 / data-privacy** experience — India's data law rolls out through May 2027; demand is spiking, few have hands-on DPDP contract review. This is her sharpest edge for fintech/SaaS.
2. **In-house CRO experience** (multinational counterparties, India/Europe/APAC contracts) — directly relevant to any global product company's India legal team, and 1:1 for other CROs (ICON).

## Application tracker
| Company | Role | Score | Applied | Referral? | Response | Status |
|---|---|---|---|---|---|---|
| Razorpay | Associate, Legal | ~32 | | | | |
| Swiggy | Legal Counsel I | ~34 | | | | |
| Flipkart | Legal Counsel I | ~32 | | | | |
| PhonePe | Assoc Mgr, Legal | ~28 | | | | |
| ICON | Legal Counsel (CRO) | ~30 | | | | |
