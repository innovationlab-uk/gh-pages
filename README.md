# gh-pages
git subtree push --prefix site origin gh-pages

This site uses mkdocs.
* To serve on local `mkdocs serve`
* To build the static files `mkdocs build`

# Updating the live site
Always working from `main` branch:

* Build the site `mkdocs build`
* Add a file `CNAME` with content of `innovationlab.uk` to the `site` folder.
* Run the update gh-pages .sh script.
