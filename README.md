# Ghost Mirror Single Job Workflow
Join [@ghost_mirror](https://t.me/ghost_mirror)

## Dont use this bin Your main account, risk of account suspension

You can use [this repos](https://github.com/ghostmirrorlab/mirror-bot-repos) as a template
First setup everything then push to your main private Repository

## Prerequisite
Fork this Repo,
Setup secrets in settings --> Secrets

```text
GH_TOKEN :- Your github personal access token, from https://github.com/settings/tokens
MIRROR_REPOSLUG :- Your Secret Repository, as in "<username>/<reponame>"
```
After that done, it should look like this
![image](https://user-images.githubusercontent.com/77688759/120898707-a2224800-c649-11eb-8b5c-4f184736e717.png)


Then edit .github/workflows/mirror-bot.yml

Change `GitHubMail`, `GitHubName` and `Branch` environment variable as your own

![image](https://user-images.githubusercontent.com/77688759/120898733-c54cf780-c649-11eb-9b80-058d4500df29.png)

And That's it.

[©ElytrA8](https://github.com/ElytrA8)
