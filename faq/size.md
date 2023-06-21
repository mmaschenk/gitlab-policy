---
title: What can be the size of my repository?
parent: FAQ
---
## Repository size
{{site.data.naming.servicename}} is primarily meant for researchers storing program code. That means we are optimized for repositories that do not grow above a few hundreds of megabytes. To allow maximum freedom for researchers however, we do not enforce a limit, trusting our researchers to make responsible use of the service.

We encourage the use of [git-sizer](https://github.com/github/git-sizer/#getting-started) for you to keep an eye on the size of your repo.[^1]

### Fixing repository size
When your repository is larger than you would like it to be, you cannot just delete any large file in your repo and commit that. This will not shrink your repo since the file is still present in the commit history. 

There is a [very useful help page](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository) on github for this situation (and yes the github recipe also works on gitlab).

As stated on the page, you also have a friend in the [BFG Repo-cleaner](https://rtyley.github.io/bfg-repo-cleaner/), an open source tool advertising its ability to remove *crazy big files*.

---
[^1]: This blog entry gives a nice overview on how to use the git-sizer tool: [https://github.blog/2018-03-05-measuring-the-many-sizes-of-a-git-repository](https://github.blog/2018-03-05-measuring-the-many-sizes-of-a-git-repository)