# Lecture Notes

This is a repository of lecture notes for mathematics modules taught in Cardiff.

| [GCSE](L2) | [A-Level](L3) | [Year 1](L4) | [Year 2](L5) | [Year 3](L6) | [Year 4](L7) |

## Instructions for Authors
See [here](https://vknight.org/rsd/chapters/05/) for VK's introduction to git.

See [here](https://github.com/cardiffmaths/texmf/blob/master/tex/latex/camnotes/) for the `camnotes` package and examples of how to use it (including how to typeset question lists and multiple-choice/multiple-answer questions).

You can use the [GitHub Desktop](https://desktop.github.com/) graphical user interface.

## Command line (\*nix)
This assumes that git is installed on your system.

```bash
# clone the repository 
$ git clone https://github.com/cardiffmaths/notes 

# navigate to the module folder (create if necessary)
$ cd notes/L5
$ mkdir MA2500
$ cd MA2500

# get to work!
$ vim main.tex

# check status
$ git status

# add files to be committed (. adds everything)
$ git add .

# commit files (you will have to type a short message)
$ git commit

# push files to (the master branch of) the remote repository
$ git push origin master
```
TODO: fetch, branch, merge, ...
