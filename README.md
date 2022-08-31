# FGSN2022

## Proceedings for the FGSN2022 Conference
 - This is a template for the creation of conference proceedings for a small conference. It compiles the proceedings from individually submitted PDF files (some manual work required).
 - I used the https://ctan.org/pkg/confproc package to compile the proceedings. The package is rather old and has some compatibility problems with hyperref. I therefore changed the way hyperref is used from the examples.
 - Originally the package creates a link from proceedings to each individual paper. Since we only distributed the proceedings I altered the .cls in order to not generate this link (it uses https://ctan.org/pkg/pdfpages to include the individual papers). 
