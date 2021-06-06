# Quick Start Guide
This "hacked" version allows you to automatically unlock the "AllSuperRank" and "MultipleLang" secret trophies.

Just use [my deployment (hacked-github-stat-trophies.vercel.app)](https://hacked-github-stat-trophies.vercel.app) and follow the general instructions from [the original repo](https://github.com/ryo-ma/github-profile-trophy).

If you want to configure which trophies you automatically get, configure these booleans in [src/card.ts](https://github.com/FlyN-Nick/hacked-github-stat-trophies/blob/master/src/card.ts) (you'll have to deploy to Vercel yourself, guide [here](/Vercel%20Deployment%20Guide.md)):
```
// LINE #50
let wantAllSuperRank = true;
let wantLongTimeAccount = false;
let wantAncientAccount = false;
let wantJoined2020 = false;
```
If you want to disable automatically getting the "MultipleLang" secret trophy, change this boolean to false in [src/trophies.ts](https://github.com/FlyN-Nick/hacked-github-stat-trophies/blob/master/src/trophies.ts):
```
// LINE #106
let wantMultipleLang = true;
```
If you choose to use my deployment, it would be really appreciated if you gave me a star 🙃.
