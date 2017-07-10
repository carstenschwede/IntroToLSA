Installation on Mac

- Make you sure you have R + RStudio installed https://www.r-project.org/about.html, https://www.rstudio.com/
- Make sure you have X11 installed (https://www.xquartz.org/)
- Make sure you have Homebrew installed (https://brew.sh/index_de.html)
- open terminal and install poppler: ```brew install poppler --with-glib```
- open terminal and make sure poppler-glib is installed: ```pkg-config --libs poppler-glib``` should give an output
- download the slam package binary for your OS X version (https://cran.r-project.org/web/packages/slam/index.html)
- install it from command-line (```Rscript -e "install.packages('slam_0.1-40.tgz', repos = NULL)"```)
- load R and try installing the packages (```install.packages(c("tm", "LSAfun", "Matrix", "RSpectra", "gplots"), dependencies=TRUE)```)
