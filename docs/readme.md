# Readme

This /docs directory contains the [Github Pages](https://pages.github.com) source code for the [website](https://open-health-manager.github.io/Design/) where you can learn more about the project and principles.

## Get started

To make changes to the website, you can edit the files directly in github, or, set it up locally. Once a pull-request has been approved and merged into the main branch, the site will re-build with those changes.

### Local set-up

1. Clone the repository locally:

```
gh repo clone Open-Health-Manager/Design
```

2. The site is built using [ruby](https://www.ruby-lang.org/en/documentation/installation/), [jekyll](https://jekyllrb.com/docs/installation/), and [bundler](https://bundler.io/). The [GitHub Docs](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll) are also a good resource.

3. Next, run `bundle install` in the `/docs` directory.

4. Finally, in the `/docs` directory run a local server using `bundle exec jekyll serve` and develop! You might want to develop on a separate branch from `main`, then create a pull request to merge your branch into `main` when your changes are ready for review.


Note: Ruby must be up to date to 3.1.2, for mac instructions for updating ruby (gloabally accross system) check here: https://mac.install.guide/ruby/13.html
