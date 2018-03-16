# Latex Template for Research Proposals
Students of Computer Science at the Computer Science department of [h_da University of Applied Sciences Darmstadt](https://www.fbi.h-da.de/fbi.html "Hochschule Darmstadt, University of Applied Sciences") frequently have to write seminar papers and in the end of their studies a thesis (Bachelor's Thesis or Master's Thesis, depending on the degree they aim for). 

Basing idea with 4 key questions, abstract, ToC, and Literature

The purpos of this template is to support students in developing and defining the essence of what they want to write their scientific paper about. 


## <a name="FillInTemplate"></a> How to fill in the Template?! 
The intention of the setup of this template was to be as easily usable as possible. 
However, nevertheless there are a few things to keep in mind while using it. 
The following guide is supposed to assist you in using it. 


#### Step 0: Clone, Open, and Generate a PDF
Start by cloning of downloading the template and opening it in your favorit LaTeX environment. 
The template is set up the way that, at this point, you should be able to generate a PDF without any errors or warnings. 

In case you have trouble generating the PDF, please take a look to the below section on the [PDF generation tool chain](#ToolChain).
This may help you getting the PDF generated.

If you require more assistance setting up your LaTeX Environment, please refer to the section below on [setup from scratch](#SetupFromScratch).



#### Step 1: Choose Language
Please acknowledge that the template is bilingual.
It can be used to create a research proposal in english or in german. 

This means the first thing you have to do, is choose the language that you want to use. 
This is done by opening _researchproposal.tex_ and stating the language in the following comment block.

    % ##########################################
    % # Choose the language for the document
    % # de = German
    % # en = English
    \newcommand{\lang}{en}
    % ##########################################


#### Step 2: Create your Proposal
Obviously, filling in your content is the most important step. 
In order to do that, you will find a lot of comment blocks in the document. 
These you have to fill in. 
These blocks will also give you further explanations about what you need to consider and keep in mind.

__Important:__ Read and follow the explanations for each comment block!

## <a name="ToolChain"></a> PDF generation Tool Chain

Description of the tool chain



## <a name="SetupFromScratch"></a>How to use this Document from Scratch?
If you have no LaTeX environment running and want still fill in this template using LaTeX, you may try the following combination of tools - which is Setup Visual Studio Code as IDE, LaTeX Workshop as extension for VS Code to edit LaTeX, and Tex Live as LaTeX distribution. 

Please understand, if you have a running environment that makes sense for you - stick with it. It is by no means necessary to use the one poposed below. 
Further, there are probably better environments out there. 
However, I personally find this setup highly usable.
This is due to the points that, it is available for all major operating systems, it is light weight, and easy to use. 

If you want to give it a shoot, here is how to set it up:

#### Step 1: Install TeX Live
The [project's website](https://www.tug.org/texlive/ "TeX Live Website") descibes [TeX Live](https://en.wikipedia.org/wiki/TeX_Live "Wikipedia on TeX Live") as: "an easy way to get up and running with the TeX document production system. It provides a comprehensive TeX system with binaries for most flavors of Unix, including GNU/Linux, and also Windows. It includes all the major TeX-related programs, macro packages, and fonts that are free software, including support for many languages around the world."

It is available for all major operating systems. 
You will find how tos for installing it on your machine on the [project's website](https://www.tug.org/texlive/ "TeX Live Website").

I would recommend to go for a full installation, as this may prevent any trouble of missing packages later. 
As an example, as a Fedora user I simply installed the _texlive-scheme-full_ package though _dnf_ (installing all LaTeX packages that TeX Live has to offer)

#### Step 2: Install Visual Studio Code

2. [Visual Studio Code](https://en.wikipedia.org/wiki/Visual_Studio_Code "Wikipedia on VSCode")


#### Step 3: Install the VS Code extension "LaTeX Workshop"




#### Step 4: Setup Tool Chain
3. Install the VS Code Extension called [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop "LaTeX Workshop - Visual Studio Marketplace")



install ___texlive-scheme-full___



Make sure you have a LaTeX distribution installed 
Install Visual Studio Code on your System https://code.visualstudio.com/





