# BDRC etext demo

## Generating epub

Install [pandoc](https://pandoc.org), then run the following command from the cloned repo directory:

    pandoc -f markdown -t epub3 "བྱང་ཆུབ་སེམས་དཔའི་སྤྱོད་པ་ལ་འཇུག་པ།.md" -o "བྱང་ཆུབ་སེམས་དཔའི་སྤྱོད་པ་ལ་འཇུག་པ།.epub" --toc-depth=2 --epub-chapter-level=3 --epub-stylesheet="./document_files/epub.css" --epub-embed-font="./document_files/MonlamUniOuChan2.ttf" --epub-cover="./document_files/cover.png"