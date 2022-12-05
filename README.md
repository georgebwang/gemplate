# Gemplate
This is a self-made LaTeX Article template. It includes all the common packages I use, as well as other configurations such as citations using BibLaTeX, font style, and document layout. Please check out the working example ([PDF](example.pdf)) for a preview of the document layout.

## Usage

For a one-time use, simply copy the `gemplate.sty` template file into the directory where your main article `.tex` file is located at. Type `\usepackage{gemplate}` in the preamble of your article file to use the template.

To conveniently allow for repetitive usage, copy the `gemplate.sty` template file into your `texmf/tex/latex/local` folder (which should have all the user-defined LaTeX packages). The actual location depends on how you installed LaTeX as well as your operating system, on MacOS and Linux operating systems the path should just be `~/texmf/tex/latex/local` (i.e., in the user home directory). Similarly, for Windows users the default path is `C:\Users\xxx\texmf\tex\latex\local`, where `xxx` is your Windows username. If the path does not exist, manually creating those directories will work. After the above steps are done, one could simply type `\usepackage{gemplate}` in the preamble of one's article file to use the template without having to copy the actual template file into their project directory every single time.
