# How to contribute

One of the easiest ways to contribute is to participate in discussions and discuss issues. You can also contribute by submitting pull requests with code changes.


## General feedback and discussions?
Please start a discussion on the [main repo issue tracker](https://github.com/thinktecture/Thinktecture.IdentityManager/issues).


## Bugs and feature requests?
Please log a new issue in the appropriate GitHub repo:

* [IdentityManager core](https://github.com/thinktecture/Thinktecture.IdentityManager)
* [ASP.NET Identity support](https://github.com/thinktecture/Thinktecture.IdentityManager.AspNetIdentity)
* [MembershipReboot support](https://github.com/thinktecture/Thinktecture.IdentityManager.MembershipReboot)

## Other discussions
https://gitter.im/thinktecture/Thinktecture.IdentityManager

## Filing issues
The best way to get your bug fixed is to be as detailed as you can be about the problem.
Providing a minimal project with steps to reproduce the problem is ideal.
Here are questions you can answer before you file a bug to make sure you're not missing any important information.

1. Did you read the [documentation](https://github.com/thinktecture/Thinktecture.IdentityManager/wiki)?
2. Did you include the snippet of broken code in the issue?
3. What are the *EXACT* steps to reproduce this problem?

GitHub supports [markdown](http://github.github.com/github-flavored-markdown/), so when filing bugs make sure you check the formatting before clicking submit.


## Contributing code and content
You will need to sign a [Contributor License Agreement](https://cla.dotnetfoundation.org/) before submitting your pull request. 

Make sure you can build the code. Familiarize yourself with the project workflow and our coding conventions. If you don't know what a pull request is read this article: https://help.github.com/articles/using-pull-requests.

We only accept PRs to the dev branch.

Before submitting a feature or substantial code contribution please discuss it with the team and ensure it follows the product roadmap. You might also read these two blogs posts on contributing code: [Open Source Contribution Etiquette](http://tirania.org/blog/archive/2010/Dec-31.html) by Miguel de Icaza and [Don't "Push" Your Pull Requests](http://www.igvita.com/2011/12/19/dont-push-your-pull-requests/) by Ilya Grigorik. Note that only contributions that meet a high bar for both quality and design/roadmap appropriateness will be merged into the source.

Here's a few things you should always do when making changes to the code base:

**Commit/Pull Request Format**

```
Summary of the changes (Less than 80 chars)
 - Detail 1
 - Detail 2

#bugnumber (in this specific format)
```

**Tests**

-  Tests need to be provided for every bug/feature that is completed.
-  Tests only need to be present for issues that need to be verified by QA (e.g. not tasks)
-  If there is a scenario that is far too hard to test there does not need to be a test for it.
  - "Too hard" is determined by the team as a whole.
