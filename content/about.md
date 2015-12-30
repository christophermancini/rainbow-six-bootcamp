+++
date = "2015-09-21T21:11:14-04:00"
title = "About"
tags = []
+++

Rainbow Six Bootcamp is an informational site for the community of the Rainbow Six video game series, with its primary attention focused on [Rainbow Six Siege](http://www.amazon.com/gp/product/B00KUYQZAU/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=B00KUYQZAU&linkCode=as2&tag=xboxonenation-20&linkId=QI5TMJ33WUM6SLVD). [Rainbow Six: Siege](http://rainbow6.ubi.com/siege) is the latest (8th) installment in Tom Clancy's legendary [Rainbow Six game series]({{<ref "franchise-history.md">}}). We aim to provide the best content to help keep you up to date with the series as well as get the most from your gameplay.

[Get started with your Rainbow Six Basic Training](/basic-training/) to be the best operator you can be!

## Contribute

The site is generated using the [Hugo Website Engine](http://gohugo.io/). The content has been released under the [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/) which means that you may share content we have created as long as it is not for commercial purposes and you credit [Rainbow Six Bootcamp](http://rainbowsixbootcamp.com) as the source.

The code and content for the site is available in [Github](https://github.com/christophermancini/rainbow-six-bootcamp). If you notice an error in the content, a problem with the code, or want to contribute new content, feel free to fork the repository, make your changes and submit a pull request. After your pull request has been reviewed and approved, it will get merged and pushed to the site with the next release. Any work you contribute to the site will be protected under the Creative Commons license mentioned above as well.

**[Learn how to contribute content to Rainbow Six Bootcamp]({{< ref "contributing.md" >}})**

## Technology

Hugo is written in the [Go](https://golang.org) programming language and is a static site generator. The entire website is build using static files with meta data at the beginning of the file followed by [Markdown](https://daringfireball.net/projects/markdown/) syntax for the content allowing rapid development of content with a consistent appearance. Because all of the content is stored within files, there is no use of a database which makes the site more portable and easier to backup.

The site is powered on a SSD backed virtual machine from [Digital Ocean](https://www.digitalocean.com/?refcode=76ac42e5dcf8). We have been using them for a few years now, they have excellent support, are inexpensive and those SSDs are so very fast. We recommend them if you are in the market for a new provider.

## Running the site locally

To run the site locally on your computer, you simply need the Hugo binary for your platform (Windows, Mac, or Linux). Then you just execute `hugo server -w` and then navigate to the url in your browser output by Hugo. For instance, the url provided to me is `http://localhost:1313/`, navigating to that url, I can use the site as I normally would at `http://rainbowsixbootcamp.com`. Now I can write new content, edit existing content, or make changes to the style of the site and see my work immediately.
