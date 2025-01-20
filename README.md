# research-figures-miscellaneous
Collection of publication quality figures generation


# LaTeX Template for Combining Figures Without Margins

This repository contains a LaTeX script to combine multiple figures efficiently without compromising quality. The `standalone` document class is used to produce a borderless output, making it ideal for figure submission.

## Usage Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shuvo-dip/research-figures-miscellaneous.git
   cd research-figures-miscellaneous


\documentclass[varwidth, border=0pt]{standalone}: Ensures no extra page margins and outputs only the content.
\usepackage{graphicx}: Required for handling images.
% Insert figure commands here: Placeholder for actual figure inclusion.
\includegraphics[width=1.02\linewidth]{figure1.pdf}: Example of how to include figures.
The \\ ensures the figures are stacked vertically.
The resulting document will be borderless and aligned tightly around the figures.

Replace figure1.pdf and figure2.pdf with your actual figure filenames.

1. **Compile using pdflatex:**
   ```bash
   pdflatex combine_figures.tex

   
The output will be a cropped PDF containing the figures arranged as specified.
