# ShinyIBL

This is the landing page for ShinyIBL, a Shiny app that allows a user to run basic decisions-from-experience simulations based on the Instance-Based Learning Theory (Gonzalez et al, 2003). 

## Demo 

The app can be demoed at http://ddmlab.com:3838/shinyibl/.

## Run Remotely

### Install R and RStudio

To install R and RStudio, follow the instructions here for your operating system: https://rstudio-education.github.io/hopr/starting.html

It is important to install R first, then RStudio.

### Run App

- After installing both R and RStudio, open the RStudio program.
- Download the code for this repository by clicking "Code" and downloading as a ZIP. Alternatively, you can clone the repository if you are comfortable with GitHub.
- Unzip the folder. You will now work with the unzipped folder.
- Open RStudio. 
- Set the working directory to be the unzipped folder. There are two main ways to do this. 
1. Run the following in the console, substituting YOURFILEPATHHERE with the file path to the folder.
```
setwd("YOURFILEPATHHERE")
```
2. Or, navigate to the folder using the bottom right panel of RStudio by clicking through the "Files" tab. Then, click "More" and then "Set As Working Directory".
- Once you have set the working directory, open the app.R file in RStudio.
- Run the following in the console and follow the instructions to install the necessary packages:
```
install.packages("shiny")
install.packages("ggvis")
install.packages("dplyr")
install.packages("reshape2")
install.packages("tidyr")
install.packages("rhandsontable")
install.packages("data.table")
```
- Type shiny::runApp() in the console or click the "Run" button on the upper right. The app should run locally.

Email Erin Bugbee (ebugbee@andrew.cmu.edu) with any questions about the app.
