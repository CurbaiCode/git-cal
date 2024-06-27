# git-cal

> GitHub-like contributions calendar in terminal

## Description

![screenshot with black theme](https://raw.github.com/CurbaiCode/git-cal/main/screenshots/img1.png)
![screenshot with white theme](https://raw.github.com/CurbaiCode/git-cal/main/screenshots/img2.png)

 * git-cal is a simple script to view commits calendar (similar to GitHub contributions calendar) on the command line
 * Each block in the graph corresponds to a day and is shaded with one of the 5 possible colors, each representing relative number of commits on that day.
 * Option to choose `--ascii` or `--unicode` to denote the same instead of the ANSI colors.
 * Option to use `git config` to set options.

## Installation

 * with root access:
```shell
perl Makefile.PL
make
sudo make install
```

 * without root access:
```shell
perl Makefile.PL PREFIX=~/.local
make
make install
```
