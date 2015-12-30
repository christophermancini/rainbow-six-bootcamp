+++
date = "2015-12-30T10:48:56-05:00"
tags = ["community"]
title = "Add your clan to the directory"
+++

Adding your clan to our directory is easy to do and will help you get new recruits as well as help the community. Follow the steps below to get your clan listed.

## Steps

All of the detailed instructions can be found on the [contributing]({{< ref "contributing.md">}}) page. The list of steps below is a brief overview of what needs to happen.

1. Fork the site repository
1. Install [Hugo](http://gohugo.io/overview/installing/)
1. Clone your fork of the repository to your computer
1. Use Hugo to create your clan page, `hugo new community/clan/clan-name.md -k clan` (replace clan-name with the name of your clan in all lower case separating words with hyphens)
1. Open your newly created clan page in a text editor, we recommend Atom if you don't already have a favorite
1. Fill out the details of your clan page and save the file
1. Commit your new file to the local repository on your computer
1. Push / sync the commit back to your fork on GitHub
1. Submit a pull request for your changes to the main site repository

## Clan page template

Each clan page uses the template that is located within the source code at `layouts/clan/single.md`. If your interested, you can look this over to see how the page will be rendered. Feel free to make suggestions or submit a pull request with any improvements you would like to see.
