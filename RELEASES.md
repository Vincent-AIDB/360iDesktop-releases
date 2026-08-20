Release index for 360i Desktop.

Each release must target its own commit: GitHub derives a release`s created_at from
the commit its tag points at, and /repos/OWNER/REPO/releases/latest - the endpoint
electron-updater reads for a private repo - picks the newest by created_at. When every
tag points at the same commit, every release ties and "latest" stops tracking the newest
release. Touch this file before cutting a release.

last release: 1.2.13
