# flux-test
flux

this repo syncs with k8s cluster to have tight integrity.
It has test chart, which run post-upgrade. I have used hooks post-upgrade and test.

If the test doesn't pass, it automatically rolls back to previous version.


