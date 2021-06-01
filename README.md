## About

Author support service provides LaTeX style files and `.tex` file templates designed for *IOS Press* journal articles.

## Contents

The following files are given in the repository (or directly in `.zip` archive):

- `iosart2x.cls`, `iosart2x.cfg` - LaTeX style files designed for *IOS Press* journal articles. Please do not change them. These files are already loaded in the respective template files; 
- `ao_template.tex` - the main template file should be used for article preparation;
- `iosart2x.pdf` - instructions for the preparation of a
camera-ready paper in LaTeX. This document contains useful information regarding the structure of your document, proper tagging style, layout features, etc;
- `iosart2x.tex` - source file for the instructions paper `iosart2x.pdf`;
- `ios2-nameyear.bst`, `bibliography.bib` - BibTeX related files. If your bibliography is structured in BibTeX format, loading your `*.bib` file and provided BibTeX style `ios2-nameyear.bst` allows you to get the final format of the bibliography. Please note that `bibtex` program should be used to generate the `*.bbl` file. `bibliography.bib` is the minimal sample of `*.bib` file.
- `ao_template.bbl` is a sample bibliography file created by BibTeX using the `ios2-nameyear.bst` file.

## Setup

- Clone the repository or download the `.zip` archive;
- Read the instructions (`iosart2x.pdf`) for the preparation of your LaTeX document;
- Use the template file `ao_template.tex` to prepare your manuscript.

## Bug reports

Please submit bug report, issues or feature requests to `latex-support@vtex.lt`.
