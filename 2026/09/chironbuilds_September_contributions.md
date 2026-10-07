# chironbuilds's September Contributions

A summary of security contributions by chironbuilds in September 2026:

* Reported an unauthenticated remote validator-crash vulnerability in `tari-ootle`, submitted through GitHub Security Advisories and tracked in `GHSA-wm29-g4mc-pgp3`.
* The report showed that an unauthenticated user could crash validators remotely.
* Provided root-cause analysis, a reachability walkthrough, a minimal proof of concept, and a suggested fix.
* Testing was performed locally only; no shared network was touched.
* Coordinated the finding through private disclosure; the fix was applied by the Tari team. Technical details remain in the advisory until it is published. The contribution is tracked in `tari-project/special_contributions#36`.

* Reported a security vulnerability in `tari-ootle` where `claim_burn` mints the claimed UTXO to the seal signer's key, submitted through GitHub Security Advisories and tracked in `GHSA-j9v4-vq99-f484`.
* The report showed that a relayer-sealed claim's funds would be locked behind the relayer.
* Provided root-cause analysis, a reachability walkthrough, a minimal proof of concept, and a suggested fix.
* Testing was performed locally only; no shared network was touched.
* Coordinated the finding through private disclosure; the fix was applied by the Tari team. Technical details remain in the advisory until it is published. The contribution is tracked in `tari-project/special_contributions#87`.