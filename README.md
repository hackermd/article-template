# article-template

LaTeX template for the article document class


## Usage

1. Clone the repository

    ```None
    git clone https://github.com/hackermd/article-template ~/Documents/my-article
    ```

2. Add content to the `sections/*.tex` files and references to the `main.bib` bibliography file using your favorite text editor.

3. Compile the LaTeX document

    ```None
    cd ~/Documents/my-article
    pdflatex index
    biber index
    pdflatex index
    pdflatex index
    ```

4. Open the generated `index.pdf`.
