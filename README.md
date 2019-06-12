# Shazam Series

Une démonstration de Google AutoML Vision pour la conférence Devfest Lille le 14 juin 2019.

Thanks to https://github.com/normankong/WhatAmIEating for the initial project.


# Build and Deploy

```
$ gcloud builds submit --tag gcr.io/PROJECT-ID/shazam_series
$ gcloud beta run deploy --image gcr.io/PROJECT-ID/shazam_series
```
