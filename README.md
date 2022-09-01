# t-r-ffnung

$ mkdir docs
# Creates a new folder called docs
$ cd docs

$ git checkout --orphan gh-pages
# Creates a new branch, with no history or contents, called gh-pages, and switches to the gh-pages branch
$ git rm -rf 
# Removes the contents from your default branch from the working directory

$ jekyll new --skip-bundle .
# Creates a Jekyll site in the current directory
gem "github-pages", "~> GITHUB-PAGES-VERSION", group: :jekyll_plugins
