RepData_PeerAssessment2
=======================

Reproducible Research Peer Assessment 2 on coursera. Link:https://class.coursera.org/repdata-016

Result html file is published here: http://rpubs.com/sheilazpy/repdataPA2

Important notices:

1. In order to read the complete data with 902297*37 dimension, be sure to set the correct envivonment first.
Sys.setlocale('LC_ALL', 'English')
Sys.setenv(LANG = "en_US.UTF-8")

2. When publishing html file to RPubs.com, follow the two steps before pressing the "publish" button in preview window.
-(1) Create a .Rprofile file in your working directory of this project  with two lines like below :
options(rpubs.upload.method = "internal")
options(RCurlOptions = list(verbose = FALSE, capath = system.file("CurlSSL", "cacert.pem", package = "RCurl"), ssl.verifypeer = FALSE))
-(2) Check the Rcurl and bitops passages in the "Packages" window of RStudio.
