# Apna Grocery test APK releases

Public download links for internal test APKs. See Releases.

## Customer app versionCode ladder (package in.apnagrocery.customer, same upload key)

Android installs only equal-or-higher versionCodes over an installed build. Current codes:

- vc46 = 0.8.7, latest store/track build (branch fix/customer-payment-map-oct16)
- vc100 = 1.0.0-rn.0, RN Phase 0 spike, unminified (Drive cap fallback only)
- vc101 = 1.0.0-rn.1, RN spike, minified slim build (Drive)
- vc102 = 1.0.0-rn.2, RN spike, unminified fallback over vc101
- vc103 = 0.8.7-recovery.103, 0.8.7 source rebuilt to restore the working app over any spike build

**Next customer build must use versionCode 104 or higher.** RN line continues from vc104+; when the RN rebuild ships for real, keep climbing - never reuse or lower codes.
