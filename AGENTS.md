# Project notes (myjosie.ca)

## Live site + deploy flow
- Live website: https://myjosie.ca
- This repo is connected to Netlify; pushing to GitHub triggers an automatic deploy and updates the live site.

## “Push live” convention
When the user says **"push live"**, do this from the repo root:
1) `git add .`
2) `git commit -m "<short note>"`
3) `git push`

If there are no changes to commit, say so and do not push.

## Always remind (non-technical user)
At the end of every assistant answer in this repo, include this line:
> You can say **"push live"** anytime to publish updates to the live site.

