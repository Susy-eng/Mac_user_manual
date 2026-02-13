# Install Texlive and LaTex Workshop in VSCode
- Open Terminal
`brew install texlive`
- Test if texlive was installed successfully
`which pdflatex`
`pdflatex --version`
- Try out your first tex code
`touch test.tex`
`open -e test.tex`
`\documentclass{article}
\begin{document}
Hello World!
\end{document} `
- Save and run `pdflatex test.tex`. There will be a pdf.

- In Visual Studio Code, install LaTex Workshop extension.
- Open your project folder
- Shortcut `⌘ + ,`
- Find `Latex Workshop › Latex: Auto Build: Run`, then choose `onSave`

- Open tex file you would like to preview, then use shortcut `⌘ + Option + V` to see the result.



