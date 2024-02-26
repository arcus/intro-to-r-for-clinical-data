# Intro to R for Clinical Data

This is the GitHub repository for the workshop called Introduction to R for Clinical Data, given at the Children's Hospital of Philadelphia (CHOP) by Arcus Education and the CHOP R User Group.  

**Looking to learn this content?** Check out the section on [how to sign up for a workshop, and how to review material from previous workshops](#upcoming-and-previous-workshops).

This repository contains the files you need to be able to complete the exercises in the workshop.  Exercises for you to complete are in the [exercises](exercises) folder, and working solutions files are found in [solutions](solutions).

This workshop is aimed at people who have never used R or RStudio and is appropriate for brand new beginners.  In it, you'll learn the basics of R, RStudio / Posit, and Quarto / R Markdown.  You'll work with fabricated clinical data and learn to ingest, visualize, reshape, and communicate findings, all using the R language.  

Not interested in clinical data?  If you work with any kind of tabular (table-shaped, with rows and columns) data, like data in spreadsheets, you might find this workshop useful.  

This workshop is free and does not require any paid software.  You will need a computer and a robust internet connection, however.

## Before the Workshop

Before the workshop, please do the following.  

**Necessary**:

* Create a free [Posit.cloud](https://posit.cloud) account.  We will use this as our training environment and you will have continued access to your code and materials after the workshop, through your account at Posit.cloud.
* Please review our [Code of Conduct](conduct.md).

**Highly Recommended**:

* Install or update the [Google Chrome browser](https://www.google.com/chrome/) on the computer you'll use.  We highly recommend you use Chrome to access our workshop training environment.
* Download and install the latest version of [Teams](https://www.microsoft.com/en-us/microsoft-teams/download-app) (you may also choose to join in a browser).
* To help us better understand our learners, please complete the [pre-course survey](https://redcap.link/pre_r_for_clinical_data). We appreciate it!
* Consider installing [R](https://cloud.r-project.org/) and [RStudio Desktop](https://rstudio.com/products/rstudio/download/) on your computer, so you can hit the ground running after the workshop finishes!
* If you haven't already, and you're a CHOP or Penn employee, please consider [joining CHOP's R User Group](http://bit.ly/chopRusers).

On the day of the workshop, we suggest the following:

* If available to you, use two monitors (or another two-screen setup such as a laptop and a tablet or two laptops).
* Follow along in the [slides](https://joy-payton-chop.quarto.pub/intro-to-r-for-clinical-data-2023/), if you like.

## Where to do the exercises

### Use Posit.cloud

The easiest way to do the workshop exercises is to create a free account at <https://posit.cloud> and then go to [our workshop project](https://posit.cloud/content/6121691) and make your own permanent copy of this project so you can make changes and work with it later.

Alternately, in Posit Cloud you can also add a new project and select "New Project from Git Repository" and enter the url of this repository, namely <https://github.com/arcus/intro-to-r-for-clinical-data>.

### Use Your Own R/RStudio

If you want, you can install R and RStudio Desktop for free on your computer, following the [instructions Posit offers](https://posit.co/download/rstudio-desktop/).  Then you can either:

* Use File > New Project to create a new project from version control and add the URL of this repository (namely, <https://github.com/arcus/intro-to-r-for-clinical-data>)
* Download the files in this repository (the green "Code" button will allow you to download a zip file of this repository's contents) and then use File > New Project > Existing Directory to create an R project in the directory where you stashed those files.

## Dependencies

The files here depend on several R libraries, which you can install using the following command:

```r
install.packages(c(
  "tidyverse",
  "rmarkdown",
  "flexdashboard",
  "plotly",
  "DT"
))
```

## Slides

[Slides](https://joy-payton-chop.quarto.pub/intro-to-r-for-clinical-data-2023) of the teaching presentation that accompany the workshop are available and you are welcome to follow along or refer back to them at a later date.  The source code for these slides is included in the directory [quarto_slides](quarto_slides) in this repository.

## Upcoming and previous workshops

This workshop was last offered in December 2023. 
If you want to be notified when the next workshop gets scheduled [sign up for the CHOP R User Group](http://bit.ly/chopRusers).

You can watch a recording of the [August 2023 session of this workshop](https://www.youtube.com/watch?v=gU4HRzlZ7po).

Much of the material from this workshop has also been adapted into interactive online tutorials you can work through at your own pace. We recommend the following sequence to learn the same content that is generally covered in this workshop: 

- [R Basics: Introduction](https://liascript.github.io/course/?https://raw.githubusercontent.com/arcus/education_modules/main/r_basics_introduction/r_basics_introduction.md)
- [R Basics: Visualizing Data with ggplot2](https://liascript.github.io/course/?https://raw.githubusercontent.com/arcus/education_modules/main/r_basics_visualize_data/r_basics_visualize_data.md)
- [R Basics: Transforming Data with dplyr](https://liascript.github.io/course/?https://raw.githubusercontent.com/arcus/education_modules/main/r_basics_transform_data/r_basics_transform_data.md)
- [R Basics: Practice](https://liascript.github.io/course/?https://raw.githubusercontent.com/arcus/education_modules/main/r_basics_practice/r_basics_practice.md)

## License

All of the material in this GitHub repository is copyrighted under the [Creative Commons BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) copyright to make the material easy to reuse. We encourage you to reuse it and adapt it for your own teaching as you like!

## Acknowledgements

Much of the material here owes its existence to Stephan Kadauke, MD, PhD, with important updates undertaken by other members of CHOP's R User Group.  This is a collaborative effort and we are grateful to all who have contributed to these materials.  This group includes Arcus Education, a CHOP group of data science educators, which is made up of:

* Elizabeth Drellich, PhD
* Rose Franzen
* Rose Hartman, PhD
* Meredith Lee
* Joy Payton, MS

We are also indebted to the dozens of people who have served as presenters, behind-the-scenes coordinators, TAs, and to the hundreds who have been our students.  Without you, this workshop would not exist.
