---
title: Updated Blog to use Gatsby 5
date: "2026-01-08T22:11:00.000Z"
description: "I updated this blog to use the latest version of Gatsby and made a couple tweaks along the way."
---
Tonight I decided to upgrade to Gatsby 5 for this blog. I faced update issues and decided to do a fresh install of Gatsby in a separate repo. Then I discovered I was probably facing issues because this version of Gatsby doesn't like Node versions greater than 20. I was able to use Node Version Manager to switch to 20's LTS version, install Gatsby starter blog in a separate folder, and then simply tweak some settings and copy the markdown files over. It took only a few minutes.

One tweak I made was to add a "Read more..." link at the bottom of each entry on the index.js page. I also of course updated the author bio information and removed the Twitter link since I don't use it, as well as copying over the same avatar.jpg I had previously been using. Overall this Gatsby starter is so simple to use, I really enjoy it. I would be pleased to work with Gatsby more in the future.