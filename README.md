# LL-V

Defensive security researcher working on network protocol parsing, traffic
heuristics, and responsible vulnerability research.

## Public repositories

- [http-framing-diff](https://github.com/LL-V/http-framing-diff) — offline HTTP/1.1 framing variants + multi-backend observation harness (never labels incomplete streams as smuggling)
- [http11-parser-corpus](https://github.com/LL-V/http11-parser-corpus) — labeled HTTP byte samples for differential research
- [traffic-analyzer](https://github.com/LL-V/traffic-analyzer) — stdlib libpcap beacon / DNS-tunnel candidate detector
- [proto-cve-disclosures](https://github.com/LL-V/proto-cve-disclosures) — research notes, invalidated candidates, and **reproductions only** of public CVEs
- Notes: [ll-v.github.io](https://ll-v.github.io)

## Research standard

A parser anomaly is not a CVE. Framing claims need specification reference,
negative controls, complete/fragmented/EOF cases, two real components when
the impact is a differential, and an impact oracle.

I currently claim **no assigned original CVE ID**. Vendor reports in progress
are listed in [proto-cve-disclosures](https://github.com/LL-V/proto-cve-disclosures)
and are not described as CVE-pending. Known-CVE work is labeled reproduction.
An earlier nodejs/http-parser candidate was invalidated after review.

All testing is limited to local systems or explicitly authorized targets.
