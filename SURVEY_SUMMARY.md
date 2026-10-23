# Survey Summary — Checkout Outage Postmortem

## Survey

**Title:** Checkout Outage Postmortem - Team Feedback

**Responder-facing link:** https://docs.google.com/forms/d/e/1FAIpQLSfAU_FbDbWQoBPDkRDgsHZALE13T7iQiPKUhR6M0I1_ZZKvcQ/viewform

## Questions

1. **Which root-cause hypothesis do you consider most likely?** (multiple choice, required)
   - H1 - Connection pool exhaustion in the orders service
   - H2 - Cache stampede on the pricing service
   - H3 - Misconfigured express-checkout feature flag shipped in the 18:40 deploy
   - H4 - Migration lock on the customers table blocking writes
2. **What is one process change that would have shortened time-to-detect?** (free text)
3. **What is one process change that would have shortened time-to-mitigate?** (free text)
4. **Any additional comments for the postmortem doc?** (free text)

## Response count

0 responses collected so far.

## Incident one-liner

On 2026-10-02, checkout was unavailable for 47 minutes during the flash sale; browsing and cart were unaffected.

## Notes version

This summary is pinned to this exact version of the raw response-channel notes (`postmortem-raw.md`).

**SHA-256 checksum:** `1c964cd47f9e181afff56636a7a48327d5e6ecf3ca9919905caf47795d5ae7db`

## Notes

- Postmortem review is scheduled for Friday.
- Responses are being collected; this summary will be refreshed once the feedback window closes.
