If you want to host an rmarkdown document as a standalone page you have to render it named index.html. 

rmarkdown::render("C:\\Users\\Faton\\Desktop\\R-ovning\\Books\\tuftetest\\testtint.Rmd",
                  output_format = "tint::tintHtml",
                  output_file = "index.html")
