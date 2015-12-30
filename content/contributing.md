+++
date = "2015-12-30T11:01:29-05:00"
title = "Contributing"
+++

Contributing to the site, no matter how small a contribution, is incredibly valuable to the Rainbow Six community. Whether your contribution is fixing a typo or a strategy guide, it will provide players a better overall experience within the community with the end result of a strong and long lasting community. The stronger the community, the more resources Ubisoft will invest in improving or adding content to the game. Not to mention, you get added to the list of contributors of the site.

Contributing to the site is also easy to do. The site does not have a database and there are no logins, the only requirement is that you need to create a [GitHub](http://github.com) account. For those unaware, GitHub is the largest [source code hosting](https://en.wikipedia.org/wiki/Comparison_of_source_code_hosting_facilities) provider and has been a key player in the explosion of [open-source software](https://en.wikipedia.org/wiki/Open-source_software) development powering nearly every website and application in the world.

## Instructions to contribute

### TL;DR

1. Fork the site repo.
1. Add or change content
1. Commit the changes to your fork
1. Submit a pull request to merge your changes with the sites code
1. Play more Rainbow Six Siege

### Forking repo

1. Navigate to the [Rainbow Six Bootcamp website repository](http://github.com/christophermancini/rainbow-six-bootcamp) on GitHub. Create an account if necessary.
1. Fork the code for the site. If your first thought is "what the fork", check out [GitHub's guide to forking a repo](https://help.github.com/articles/fork-a-repo/).

Once you have forked the sites repo once, you don't have to do this again. You merely need to [sync your fork](https://help.github.com/articles/syncing-a-fork/) with the latest changes from the sites repository.

### Adding / changing content

There are two methods to add or change content. Which method you choose should be determined based on the magnitude of the change. If you are attempting to make a very minor change, for instance fix the spelling or grammar of content, then changing the file directly in your GitHub fork is reasonable. If you are adding a new page of content or modifying a template file, then you should go the route of cloning the site to your computer and modifying the code so you can test your changes.

To understand the structure of the site, the syntax of the pages variables (the text between the `+++` symbols) or the syntax of [markdown](https://daringfireball.net/projects/markdown/), visit [Hugo's Getting Started](http://gohugo.io/overview/quickstart/) page.

#### Change on GitHub

1. Navigate to the fork you created above in [Step 1: Forking]({{< ref "#step-1-forking" >}}).
1. Navigate to the content file you want to modify.
1. Click the pencil icon to Edit the page.
1. In the text-area displaying the code, scroll to the content we want to change and make the change.
1. Below the text-area enter a comment for your change and click `Commit Changes`

**Example**
Say we want to fix a typo on Ash's operator page in the description.

1. In the "<> Code" browser of our fork, we would navigate to `content/advanced-training/operator/fbi-swat/ash.md`.
1. Then click the pencil icon on the right side of the header bar of the preview of Ash's page.
1. In the text-area displaying the code of Ash's page, scroll to the content we want to change and make the change.
1. Below the text-area enter a comment for your change, e.g. "Fix typo in description" and `Commit changes`

#### Change locally

1. Clone the repository onto your computer.
  * There are several ways to do this but if you are new, I recommend using [GitHub's Desktop](https://desktop.github.com) app which is easy to use and has great [user guides](https://help.github.com/desktop/guides/getting-started/).
1. Install [Hugo](http://gohugo.io/overview/installing/)
1. If you are adding a new page, please use [Hugo's new content](http://gohugo.io/commands/hugo_new/) command as it will setup your file properly for the type of content it is. E.g. `hugo new community/clan/clan-name.md -k clan`
1. Open the file you are modifying in a text or code editor. I recommend [Atom](https://atom.io/) but any text editor will do.
1. Modify the file as needed.
1. Test your changes by using Hugo's builtin [web server](https://gohugo.io/commands/hugo_server/) `hugo server -w`
1. Commit your changes to your local repository and push/sync them back to your fork

### Submit pull request

At this point, you have modified the site within your own copy of the sites code. In order to get your changes uploaded to [Rainbow Six Bootcamp](http://rainbowsixbootcamp.com), you need to submit a [GitHub pull request](https://help.github.com/articles/using-pull-requests/), or PR, to the main site repository. After I receive the PR, I will review your changes and either comment on the PR or approve the changes, merging them into the main source code for the site.

### After PR approval

After a PR is approved for merge into the main site source code, I will use Hugo, `hugo -b http://rainbowsixbootcamp.com`, to build the site and then deploy it to the web server. Your changes are not officially on the site until that is complete.
