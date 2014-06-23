
# rOpenSci lightning talks

If you are attending a conference, or have a chance to speak about the rOpenSci project at your institution, this slide deck will provide you with a useful starting point to quickly build and customize your own presentation. 

__How to use this repo__

1. Fork this repo into your own account
2. Edit the slides (at the very least edit [your name and url](https://github.com/ropensci/ropensci_intro/blob/master/index.Rhtml#L3-L5) of the presentation at the top of `index.Rhtml`).
3. Remove any slides that might be irrelevant to your audience.
4. To build `index.html`
```
make slides
# Or of you don't have Make
Rscript -e "library(knitr); knit('index.Rhtml', quiet = TRUE)"
```

Then make sure all the changes are on the `gh-pages` branch. Otherwise simply switch to `gh-pages` and merge master:

```
git checkout gh-pages
git merge master
```

Then you can present your talk at `http://YOUR_USERNAME.github.io/ropensci_intro`. This presentation, for example, is available at [`http://ropensci.github.io/ropensci_intro`](http://ropensci.github.io/ropensci_intro)

This frees you up from even bringing your own laptop if there already one at the venue. If you anticipate not having an internet connection, simply clone a copy first on to a thumbdrive before you no lose internet access.

---

[![](http://ropensci.org/public_images/github_footer.png)](http://ropensci.org)

