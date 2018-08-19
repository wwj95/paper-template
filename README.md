# NVSL Paper Template

We will be using this template moving forward as the starting point for all papers.  You should fork the repo to create a new paper.

This repo works in conjunction with `libpaper` a set of common `.tex`, `.bib`, and other files we will use for writing papers.  That repo is here:  [git@github.com:NVSL/libpaper.git]

## Usage

Create a new paper, you need to:

1.  Get a copy of `libpaper`, e.g. with `git clone git@github.com:NVSL/libpaper.git ./libpaper` or 

```sh
$ git clone git@github.com:NVSL/paper-template.git
$ cd paper-template
$ make setup
```

Assuming the latter:
 
```sh
$ paper-template/libpaper/bin/newpaper.py --topic StarQuake --year 2019 --conference ASPLOS --github-user stevenjswanson
```

