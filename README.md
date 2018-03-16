# Latex Template for Research Proposals
Students at the Computer Science department of [University of Applied Sciences Darmstadt](https://www.fbi.h-da.de/fbi.html "Hochschule Darmstadt, University of Applied Sciences") frequently have to write seminar papers during their studies and in the end of their studies a thesis (Bachelor's Thesis or Master's Thesis, depending on the degree they aim for). 
During the creation of these papers (or theses), one of the major challenges for many students is to find the topic they are going to write about and shape it the way that it is interesting and of relevance.

The purpos of this template is to support students in developing and defining the essence of what they want to write their scientific paper about. 
As a supervisor I ask my students to fill it in and have them write down their ideas. 

The most important part is to have them answer the following four questions (within in the template they are described in much further detail as LaTeX comments):
- What is the problem?
    - The objective here is to have students give a very brief description (1 sentence) of the problem they want to adress in their work.
- Why is it a problem?
    - Why is the problem at all relevant? Why should we spend effort into investigating/solving it?
- What is the solution?
    - What results have been (or will be) produced? How do these results address the proposed problem?
- Why is it a solution?
    - What is the quality of the results? What shortcomings are there? How did the student ensure that the results are genuine?

Furthermore, I ask them to provide:
- A abstract of their proposed work
- A proposal for a table of contents
- relevant/significant pieces of related work they have already found




## <a name="FillInTemplate"></a> How to fill in the Template?! 
The intention of the setup of this template was to be as easily usable as possible. 
However, nevertheless there are a few things to keep in mind while using it. 
The following guide is supposed to assist you in using it. 


#### Step 0: Clone, Open, and Generate a PDF
Start by cloning of downloading the template and opening it in your favorit LaTeX environment. 
The template is set up the way that, at this point, you should be able to generate a PDF without any errors or warnings. 

In case you have trouble generating the PDF, please take a look to the below section on the [PDF generation tool chain](#ToolChain).
This may help you getting the PDF generated.


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
There is nothing special about the tool chain used to generate the pdf. 
It uses:
- pdflatex - to generate a pdf document
- biber - to process the bibliography

Assuming you are familiar with LaTeX it should easily be setup. 


