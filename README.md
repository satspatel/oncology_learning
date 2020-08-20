## What's this repo about?

It's probably easier to talk about my objectives:

I want to:
- use git and github _properly_ (you know, through the terminal...)
- reaquaint myself with oncology and haematology
- host my findings/learning on a github pages site

## What I've done so far

### 2020-08-16
- made the index.md file
- learnt a bit about writing in markdown using the cheatsheet

### 2020-08-19
- used `git config --global user.name` and `user.email` to set up my details
- used an anonymised email address to keep my main one private
- `git init` becuase that's what you need to do
- `git add .`
- created the github repository on the website
    - can this be done a better way??
- linked it as a remote branch through terminal `git remote add origin https://github.com/satspatel/oncology_learning`
- had some difficulties pushing got some issues about the remote repo having work that I have not got locally
- so I ran `git pull` which also didn't work as the histories weren't linked
   - then ran `git pull --allow-unrelated-histories`
- we then managed to `git push origin master` where origin is the local and master is the remote branch that we want to merge
- went to settings and created github pages from the master branch and selected a jekyll theme

## To-do
- document the reading I've been doing for ward work
- maybe think about having a site map
    - review this document to look at structure https://jekyllrb.com/docs/structure/