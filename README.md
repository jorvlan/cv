## My pagedown rendered CV

This repo contains the source-code and results of my CV built with the [pagedown package](https://pagedown.rbind.io) and a modified version of the 'resume' template. 

The main files are:

- `index.Rmd`: Source template for the cv, contains a variable `PDF_EXPORT` in the header that changes styles for pdf vs html. 
- `index.html`: The final output of the template when the header variable `PDF_EXPORT` is set to `FALSE`. 
- `jordyvanlangen_cv.pdf`: The final exported pdf.
- `resume.Rmd`: Source template for single page resume. 
- `positions.csv`: A csv with columns encoding the various fields needed for a position entry in the CV.
- `css/`: Directory containing the custom CSS files used to tweak the default 'resume' format from pagedown. 

The source code was derived from Nick Strayer (www.github.com/nstrayer/cv)


