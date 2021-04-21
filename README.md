# Goost Website

This repository contains the source code for official Goost website.

## Development

As of now, the website uses [Jekyll](https://jekyllrb.com/) static site
generator hosted by GitHub.

Proceed to
[GitHub documentation](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)
on how to test GitHub Pages site locally with Jekyll.

### WSL caveats

If you develop on Windows using WSL, make sure to run server with `bundle exec jekyll serve --force_polling --livereload` if you'd like to have a smoother experience
developing the site on each change.
