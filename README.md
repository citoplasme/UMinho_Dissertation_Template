# [University of Minho - Dissertation] Latex Template 

#### How to use the Template:

In order to use the Template, you need a Latex Editor. Personaly, I used [TexMaker](https://www.xm1math.net/texmaker/). As far as I know, this template is **not** compatible with Overleaf.

The cover and back cover are generate using the .ai files available at the academic portal of UMinho. You can edit them, e.g., using the program [Inkscape](https://inkscape.org). Make sure the fonts are not altered when editing the files. After generating pdf files from these, the backcover can be placed in the [chapters directory](https://github.com/citoplasme/UMinho_Dissertation_Template/tree/main/Dissertation/Latex/chapters), under the name **FOLHA-ROSTO-EE.pdf**. The cover can be added in the end, by merging the pdf generated using the Latex editor and the one from the .ai file.

You can view the pdf generated using the template [here](https://github.com/citoplasme/UMinho_Dissertation_Template/blob/main/Dissertation/Latex/main.pdf). 

##### Compilation:

To compile the acronymns, you have to run the following command (everytime you want to make sure they are up to date) in the directory where you have the main.tex file:

`makeglossaries main`

To fully compile the pdf, i.e., to generate the bibliography, references and text, you have to follow these steps:

* Compile using XeLatex
* Compile using BibTex
* Compile using XeLatex
* Compile using XeLatex (To update labels on the pdf)

After that, just hit the **View** button, with **View PDF** selected and your document will be ready.
