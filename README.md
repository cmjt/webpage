Repository for webpage.

Webpage was built using the `R` package `blogdown` and the (academic theme)[https://sourcethemes.com/academic/]

Resources used to built this webpage
 - (`blogdown` book)[https://bookdown.org/yihui/blogdown/]
 - (academic documentation)[https://sourcethemes.com/academic/docs/get-started/]

In brief, to build a simlar webpage

 1. install `blogdown` and download/deploy a new site with the academic theme
 `blogdown::new_site(theme = "gcushen/hugo-academic")` into an empty directory.
 2. edit the `.md` files in the content directory (remove as required)
 3. edit the `.toml` files in the config directory to controt menu options .etc.
 4. `blogdown::serve_site()` will open the site in your browser to check layout
