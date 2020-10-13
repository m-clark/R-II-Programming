R-II-Programming

This is the repo for the workshop that focuses on Part II of [Practical Data Science](https://m-clark.github.io/data-processing-and-visualization) document. You can see the workshop slides [here](https://m-clark.github.io/R-II-Programming/index.html).


Run the following in your R session to get the notes and materials for the workshop.  If you want, change the `destdir` to save the project in a specific place (not necessary, should default to desktop).  It will open the RStudio project for you, after which you can close the one you have open now.


```r
install.packages('usethis')

usethis::use_course(
  'https://github.com/m-clark/R-II-Programming/blob/master/workshop_programming.zip?raw=true', 
  destdir = NULL
)
```

If you have issues, just download that zip file (click or paste the link above into your browser), unzip it to a location of your choosing, then:

- Click on the blue .Rproj icon inside

OR

- With RStudio - File/Open Project - Navigate to the folder - Open


With your RStudio project set up, you may read the `ReadMe.md`, open `code/install_script.R` and run it.
