# Open Source Project for Quick and Collaborative Creation of Economic Education Books/Articles

Shared book explaining how the world works based on the ideas mostly associated with free-market economists Ludwig von Mises and 1974 Nobel Laureate in Economics F.A. Hayek and like-minded friends


Current versions in <a href="./books/EconoGospel.pdf" target="_blank">PDF</a> and in <a href="./books/Econogospel.md" target="_blank">markdown</a>



To contribute and "assemble" the books you need the following.

Python and install [the markdown preprocessor](https://github.com/jreese/markdown-pp)

pip install MarkdownPP

From the books directory run:

markdown-pp EconoGospel.mdpp -o EconoGospel.md -e latexrender

which will process the .mdpp file and create the markdown EconoGospel.md

See how the .mdpp file is mostly references to "snippets"

Also install https://pandoc.org/  to convert markdown to html

pandoc EconoGospel.md -f markdown -t html -o EconoGospel.html




