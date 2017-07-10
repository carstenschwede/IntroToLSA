** Installation on Mac **

- Make sure you have Homebrew installed (https://brew.sh/index_de.html)
- open terminal and install poppler: ```brew install poppler --with-glib```
- download the slam package binary for your OS X version (https://cran.r-project.org/web/packages/slam/index.html)
- install it from command-line (```Rscript -e "install.packages('slam_0.1-40.tgz', repos = NULL)"```)
- load R and try installing the packages (```install.packages(c("tm", "LSAfun", "Matrix", "RSpectra", "gplots"), dependencies=TRUE)
```)
