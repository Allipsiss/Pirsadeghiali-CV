
# Personal Website Repository

This repository contains the content of my personal website hosted at [https://hassansaei.github.io/](https://hassansaei.github.io/). The website is built using [blogdown](https://bookdown.org/yihui/blogdown/), a package for creating static websites with R Markdown and Hugo.

## Getting Started

To build and serve the website locally, follow these steps:

1. **Install Hugo**: Ensure you have the correct version of Hugo installed.

```R
blogdown::install_hugo(version = "0.54.0", os = "macOS", arch = "64bit")

#Use the blogdown package to serve the site locally.
library(blogdown)
serve_site()

#Stop the Server
stop_server()

# Build the Site
build_site(build_rmd = TRUE)
```
## Publications

The BibTeX file is used for the ["Selected  Publications" section](content/home/publications.Rmd) section of the website. This section is generated using the RefManageR [RefManageR package](https://cran.r-project.org/web/packages/RefManageR/index.html)) package.

## Customization

To customize the appearance and functionality of the website, you can modify the content and configuration files located in the content/ and config/ directories, respectively.

## Deployment
The website is automatically deployed to GitHub Pages. Ensure that any changes are committed and pushed to the repository to trigger the deployment process.

## Acknowledgments

- blogdown
- Hugo
- RefManager
- Jean Monlong
