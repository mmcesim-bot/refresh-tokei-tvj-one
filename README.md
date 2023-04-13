# refresh-tokei-tvj-one
Refresh tokei.tvj.one Every 5 Minutes

Since tokei.tvj.one is hosted on render.com as a free plan,
this action will keep the service on (which is automatically spun down after 15 minutes of inactivity).

This action will perform
```sh
wget "https://tokei.tvj.one/b1/github/mmcesim/mmcesim?style=flat"
wget https://tokei.tvj.one/b1/github/mmcesim/mmcesim
```

> **Note** Since the timing of GitHub Actions is not accurate, which sometimes can have interval of more than 15 minutes,
> a cron task is also set up on one Linux server.
