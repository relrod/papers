papers
======

**This is a heavily modified fork of
[ocharles/papers](https://github.com/ocharles/papers)**.

A Git annex repository of academic papers.

Changes:
- Added papers that I find interesting
- Laid out the repository differently (trying to categorize papers into
  subdirectories, but this is hugely a work in progress)

Using this
==========

To use this repository you need to have Git and Git Annex installed. Then:

    git clone git://github.com/relrod/papers
    git annex init local-copy
    git annex get .
    
This will downloaad everything. You can of course just selectively `git annex get` the papers that interest you.

To stay up to date, just run

    git annex sync origin

Alternatively, if you are running the git annex assistant, click on the top right, choose `add another local repository` and select the directory you cloned the repo into.  It will then be automatically kept up to date by the assistant
