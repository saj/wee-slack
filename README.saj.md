saj's personal [fork][saj/wee-slack] of [wee-slack][rawdigits/wee-slack].

This is a [TopGit]-controlled repository.  This repository tracks my personal
patches to upstream wee-slack.  Many of these patches have not been subject to
peer review or consideration for upstream inclusion.

[saj/wee-slack]: https://github.com/saj/wee-slack
[rawdigits/wee-slack]: https://github.com/rawdigits/wee-slack/
[TopGit]: https://github.com/greenrd/topgit


# Branch layout

 * `r/saj`: Release branch.  My machine executes code from this head.  Commits
   from TopGit-controlled feature branches are cherry-picked to this branch
   (sans TopGit metadata).

 * `t/saj/*`: TopGit-controlled feature branches.  These branches will contain
   TopGit metadata and are thus unsuitable for direct use as heads in GitHub
   pull requests.
