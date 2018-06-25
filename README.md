R markdown template for UNC formatted dissertation

This repository contains files to create a formatted dissertation according to [UNC graduate school standards](http://gradschool.unc.edu/academics/thesis-diss/guide/). All of the code elements are modified versions from other people. The Rmd parts derive from [https://github.com/jvcasill/ua_thesis_rmd](https://github.com/jvcasill/ua_thesis_rmd) and the UNC formatting .cls file from [https://github.com/mmalahe/unc-dissertation](https://github.com/mmalahe/unc-dissertation). Lastly, the code  [here](https://rosannavanhespenresearch.wordpress.com/2016/02/03/writing-your-thesis-with-r-markdown-1-getting-started/) was also helpful. This formatted dissertation would not be possible without their code!

# Steps to run the file in R Studio

1. Must have be able to run R, RStudio and LaTex files. If not, then the following steps will not be possible.
2. Download the repo to a local folder on your computer.
3. Open [dissertation.Rmd](dissertation.Rmd) in RStudio.
    * Hit the 'Knit PDF' button in the window containing the dissertation.Rmd code.
    * You should get a [formatted PDF](dissertation.pdf) with the content in this template.
4. Modify the files to fit your content. 
   * Note: Try not to modify the .cls file unless you are LaTex literate. Even adding one extra package could throw the whole formatting scheme off.

