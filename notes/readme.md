Scribing Guide
==================


## Installing LaTex

You need to install LaTex. LaTex is a programming language used in academia for writting documents. It will produce high quality document by default (compared with MS Word/Apple Pages etc).
You can find the guide of installing LaTex and how to use LaTex to write a report [here](https://www.latex-tutorial.com/tutorials/).

## Testing your LaTex Installation

1. Fork this project:
[instructions](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo)

2. Clone your forked repo

3. Check whether your can compile `template.tex` in `note` folder:
```
cd CS291D-20Fall/note
pdflatex template.tex

```
This step should produce a `template.pdf`


## Writing Lecture Note

Write a 2 - 3 page lecture note of your assigned lecture. Should cover the major concepts taught, problems, and the techniques used.
You should change the `template.tex` to fill in your own content. Please don't delete `template.tex`. Instead, copy `template.tex`, rename it to `lecture<N>.tex`, 
where `<N>` is the actual lecture number. You need to submit a `.tex` source code.
Don't forget to change Line 112 to the correct lecture number, title, and scribbers names.


## Submitting Your Lecture Note

Please create a pull request to this repo:
[instructions](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)

## Copyrights

The lecture notes will be audited by the instructor and will be published online. The orignial sribbers will be accredited.



