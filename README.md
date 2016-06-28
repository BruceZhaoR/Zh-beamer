# Zh-beamer

Create Chinese beamer PDF PowerPoint with `rmarkdown` on Windows.

## Usage

1. download this repository
2. open the `test.Rmd`
3. press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>K</kbd> (knit PDF)
4. wait a minute and see what has been generated.

You can customise the beamer theme in the `Output Options`, which next to `knit PDF`. Or you can directly change default theme and fonttheme in the `_output.yaml` file.

*If you encounter a problem, please don't hesitate to creat an issue.* **You'd better print the error info.**

## Requirement

Must have installed `MikTex 2.9` and `pandoc 1.15`. To test whether have installed `pandoc` ,just run `pandoc -v` in the Windows Cmd (win+R -> cmd ->Enter).