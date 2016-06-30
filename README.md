# Zh-beamer

Create Chinese beamer PDF PowerPoint with `rmarkdown` on Windows.

## Requirement

Must have installed `MikTex 2.9` and `pandoc 1.15`. To test whether have installed `pandoc` ,just run `pandoc -v` in the Windows Cmd (win+R -> cmd ->Enter).

## Usage

1. download this repository
2. open the `test.Rmd`
3. press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>K</kbd> (knit PDF)
4. wait a minute and see what has been generated.

Just click new R Markdown -> presentation -> PDF(Beamer). Edit the file, then press knit. If you haven't run the code before, it wil take about 2minutes to render Rmd to PDF.

**Notice:** the `beamer_default.tex` & `_output.yaml` & the Rmd file should be in the same fold! 

You can also customise the beamer theme in the `Output Options`, which next to `knit PDF`. Or you can directly change default theme and fonttheme in the `_output.yaml` file.

*If you encounter a problem, please don't hesitate to creat an issue.* **You'd better print the error info.**

Here are the snapshots:

![img1](/beamer/beamer1.png)
![img2](/beamer/beamer2.png)
![img3](/beamer/beamer3.png)
![img4](/beamer/beamer4.png)

[test.pdf](https://rawgit.com/BruceZhaoR/Zh-beamer/master/test.pdf)

## License

Licensed under the[Apache License, Version 2.0](/LICENSE).