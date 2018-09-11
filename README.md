# Zh-beamer

Create Chinese Beamer & PDF with `rmarkdown` on Windows.

## Requirement

~~Must have installed `MikTex 2.9` and `pandoc 1.15`. To test whether have installed `pandoc` ,just run `pandoc -v` in the Windows Cmd (win+R -> cmd ->Enter).

- tinytex: <https://yihui.name/tinytex/>

## Usage

- [Chinese Beamer](#for-chinese-beamer)
- [Chinese PDF](#for-chinese-pdf)

### For Chinese Beamer:

1. download this repository
2. open the `test.Rmd`
3. press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>K</kbd> (knit PDF)
4. wait a minute and see what has been generated.

Just click new R Markdown -> presentation -> PDF(Beamer). Edit the file, then press knit. If you haven't run the code before, it wil take about 2minutes to render Rmd to PDF.

**Notice:** the `beamer_default.tex` & `_output.yaml` & the Rmd file should be in the same fold! 

You can also customise the beamer theme in the `Output Options`, which next to `knit PDF`. Or you can directly change default theme and fonttheme in the `_output.yaml` file.

*If you encounter a problem, please don't hesitate to creat an issue.* **You'd better print the error info.**

[Beamer.pdf](https://rawgit.com/BruceZhaoR/Zh-beamer/master/test.pdf),Here are the snapshots:

![img2](/beamer/beamer2.png)
![img3](/beamer/beamer3.png)
![img4](/beamer/beamer4.png)

### For Chinese PDF

1. the Rmd file is in the `Chinese-PDF` fold
2. open the `code.Rmd`
3. press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>K</kbd> (knit PDF)
4. you will encounter `43` error.

**Notice:** it's because that your MikTex lacks some related packages. So you need to open the `default.latex` and the `MikTex Packages Manager` to download the packages that are used in the `default.latex`.

I don't know how many times I have tried, but it worked at last. *Good luck, my friend!*

[Chinese.pdf](https://github.com/BruceZhaoR/Zh-beamer/tree/master/Chinese-PDF), Here are the snapshots:

![img1](/Chinese-PDF/1.png)
![img2](/Chinese-PDF/2.png)
![img3](/Chinese-PDF/3.png)

## License

Licensed under the[Apache License, Version 2.0](/LICENSE).
