This repository has a minimal working example of a R markdown template to create a UNC formatted dissertation.

The files create a formatted dissertation according to [UNC graduate school standards](http://gradschool.unc.edu/academics/thesis-diss/guide/). 

I want to note that all of the code I have here is really just modified scripts from other sources/people. 

1. The Rmd parts derive from [https://github.com/jvcasill/ua_thesis_rmd](https://github.com/jvcasill/ua_thesis_rmd) 
2. All LaTeX files are from [https://github.com/mmalahe/unc-dissertation](https://github.com/mmalahe/unc-dissertation). 
3. Lastly, the code  [here](https://rosannavanhespenresearch.wordpress.com/2016/02/03/writing-your-thesis-with-r-markdown-1-getting-started/) was also helpful. 

# Steps to run the file in R Studio

1. Must be able to run R and RStudio as well as compile LaTex files. If not, then the following steps will not be possible.
2. Download the repo to a local folder on your computer.
3. Open [dissertation.Rmd](dissertation.Rmd) in RStudio.
    * Hit the 'Knit PDF' button in the window containing the dissertation.Rmd code.
    * You should get a [formatted PDF](dissertation.pdf) with the content in this template.
4. Modify the files to fit your content. 
   * Note: Try not to modify the .cls file unless you are LaTex literate. Even adding one extra package could throw the whole formatting scheme off.

