# [University of Minho - Dissertation] Latex Template 

As of July 2021, this template follows every norm stated by the University of Minho in terms of structure of the dissertation, e.g., font (type and size), content structure, spacing, etc.).  

#### How to use the Template:

In order to use the Template, you need a Latex Editor. Personaly, I used [TexMaker](https://www.xm1math.net/texmaker/). As far as I know, this template is **not** compatible with Overleaf.

The first thing to do is to install the fonts (NewsGotT and NewsGotTLig), available [here](https://alunos.uminho.pt/PT/estudantes/Paginas/InfoUteisFormatacao.aspx). If you do not install the fonts properly, the document will not be be generated properly. The supra mentioned link contains a table were you can select the font file to download. After that, based on your operating system, you have to install the fonts to your machine, using the downloaded file. After all that, you are good to go. If you want to be sure that everything is all set, compare the [pdf file in the repository](https://github.com/citoplasme/UMinho_Dissertation_Template/blob/main/Dissertation/Latex/main.pdf) with the pdf generated in your machine. 

The cover and back cover are generate using the .ai files available at the academic portal of UMinho. You can edit them, e.g., using the program [Inkscape](https://inkscape.org). Make sure the fonts are not altered when editing the files. After generating pdf files from these, the back cover can be placed in the [chapters directory](https://github.com/citoplasme/UMinho_Dissertation_Template/tree/main/Dissertation/Latex/chapters), under the name **FOLHA-ROSTO-EE.pdf**. The cover can be added at the end, by merging the pdf generated using the Latex editor and the one from the .ai file.

##### Compilation:

To compile the acronymns, you have to run the following command (everytime you want to make sure they are up to date) in the directory where you have the main.tex file:

`makeglossaries main`

To fully compile the pdf, i.e., to generate the bibliography, references and text, you have to follow these steps:

* Compile using XeLatex
* Compile using BibTex
* Compile using XeLatex
* Compile using XeLatex (To update the labels on the pdf)

After that, just hit the **View** button, with **View PDF** selected and your document will be ready.

<hr/>

I hope this template helps you and saves you some time! 
