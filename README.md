# student-portal-staging
Built staging site for student-portal. Deployed automatically — do not edit by hand. DO NOT COMMIT HERE.

`Deploy staging site` (`.github/workflows/deploy-staging.yml`) runs when
student-portal's **Staging sync** workflow starts it after a merge to `master`,
twice a day as a backup (skipped when nothing changed), or by hand. How it fits
together, the token it relies on, and what to do when it fails:
[student-portal `docs/operations/STAGING_AUTOMATION.md`](https://github.com/Mission-Next-Technical-Academy/student-portal/blob/master/docs/operations/STAGING_AUTOMATION.md).
