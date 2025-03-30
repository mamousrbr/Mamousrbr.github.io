yml_empty() %>%
  yml_site_opts(
    name = "my-website",
    output_dir =  "_site",
    include = "demo.R",
    exclude = c("docs.txt", "*.csv")
  ) %>%
  yml_navbar(
    title = "My Website",
    left = list(
      navbar_page("Home", href = "index.html"),
      navbar_page(navbar_separator(), href = "about.html")
    )
  ) %>%
  yml_output(html_document(toc = TRUE, highlight = "textmate"))
#> ---
#> name: my-website
#> output_dir: _site
#> include: demo.R
#> exclude:
#> - docs.txt
#> - '*.csv'
#> navbar:
#>   title: My Website
#>   left:
#>   - text: Home
#>     href: index.html
#>   - text: '---------'
#>     href: about.html
#> output:
#>   html_document:
#>     toc: true
#>     highlight: textmate
#> ---
#> 
