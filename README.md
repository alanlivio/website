# cv-site

This website uses [mkdocs](https://github.com/mkdocs/mkdocs) to generate static site and [moderncv latex class](https://github.com/moderncv/moderncv) for pdfs, both integrated through the `build.py` script with centralized data on `mkdocs.yaml`. 

### deps
To install moderncv on ubuntu, run 
  ```bash
  sudo apt-get install texlive texlive-latex-extra texlive-fonts-extra
  ```
while on windows, run
  ```bash
  winget install ChristianSchenk.MiKTeX
  ```
To install mkdcos, run: 
  ```bash
  pip install -r requirements.txt
  ```
### build

To build both latex pdfs and mkdocs, run 
  ```bash
  python build.py
  ```

To test locally, run 
  ```bash
  mkdocs serve
  ```

### deploy

To deploy into github pages, run 
  ```bash
  mkdocs gh-deploy --force
  ```

## thanks 

I took some inspiration from mkdocs-materal-based [Twarner491's website](https://github.com/Twarner491/Project-Documentation-Site).  
