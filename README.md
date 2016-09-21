[PaperBon.net](http://paperbon.net)

This is a Jekyll website hosted via Github Pages.

Each project has:

* A Markdown file in `_posts/`
* A teaser image in `images/724/` with the dimensions of 724x408
* A header image in `images/tops/` with maximum width of 1140 and recommended height between 200-300
* A series of extra images in `images/other/` with a suggested with of 727

To build the project locally:

* `vagrant up`
* `vagrant ssh`
* `cd /vagrant`
* `jekyll serve`
* go to [localhost:4000/paperbonnet/]() in your browser

To incorporate drafts:

* `jekyll serve --drafts`
