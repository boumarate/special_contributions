# chironbuilds's September Contributions

A summary of security contributions by chironbuilds in September 2026:

* Reported an unauthenticated remote validator-crash vulnerability in `tari-ootle`, submitted through GitHub Security Advisories and tracked in `GHSA-wm29-g4mc-pgp3`.
* The report showed that an unauthenticated user could crash validators remotely.
* Provided root-cause analysis, a reachability walkthrough, a minimal proof of concept, and a suggested fix.
* Testing was performed locally only; no shared network was touched.
* Coordinated the finding through private disclosure; the fix was applied by the Tari team. Technical details remain in the advisory until it is published. The contribution is tracked in `tari-project/special_contributions#36`.

* Reported a security vulnerability in `tari-ootle` where the wallet applies an unverified transaction-finalization diff, submitted through GitHub Security Advisories and tracked in `GHSA-p5x5-x636-37pg`.
* The report showed that the wallet applied an unverified transaction-finalization diff taken from a single committee member's first answer, allowing a single malicious validator to mark real inputs spent, record phantom change, or release the locks of committed transactions.
* Provided root-cause analysis, a reachability walkthrough, a minimal proof of concept, and a suggested fix.
* Testing was performed locally only; no shared network was touched.
* Coordinated the finding through private disclosure; the fix was applied by the Tari team. Technical details remain in the advisory until it is published. The contribution is tracked in `tari-project/special_contributions#108`.