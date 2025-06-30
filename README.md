# 📚 My Book Title

Welcome to the public repository for my upcoming book(tbh, I'm still brainstorming titles). This project is being written in LaTeX and shared in the spirit of transparency and learning — but it is *not* a free/open-source book.

## 🚧 Status

This book is currently a **work in progress**. Expect updates, edits, and refactors as I write and refine each chapter.

## ⚠️ License [![License: CC BY-NC-ND 4.0](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

This project is licensed under a **Creative Commons Attribution-NonCommercial-NoDerivs 4.0 International License (CC BY-NC-ND 4.0)**.

You **may**:
- Read and share the material for non-commercial purposes

You **may not**:
- Modify, remix, or adapt the content
- Use it for commercial purposes

👉 Full license text: [LICENSE](LICENSE)

## 🙏 Support

I'm writing this book on my own, and your support means the world to me. If you find it helpful or want to see it completed faster, consider donating:

- [🌐 Support me via Paypal](#) (Broken link)
<!-- - [☕ Buy Me a Coffee](https://www.buymeacoffee.com/kevinthebiologist) unconnected due to technical challenges -->
- [📘 Pre-order the final book](#) (Coming Soon)

## 🛠️ How to Compile

You'll need a LaTeX distribution (like [TeX Live](https://www.tug.org/texlive/)) and your favorite LaTeX editor.

```bash
cd tex  # the directory with the tex files
pdflatex main.tex && biber main && makeglossaries main && pdflatex main.tex && pdflatex main.tex  # creates the complete pdf with all the expected bells and whistles
rm *.aux *.log *.out *.toc *.bcf *.blg *.bbl *.xml *.glo *.gls *.glg  # removes all the unnecessary files generated from the pdf creation. This is useful for debugging too.
```

