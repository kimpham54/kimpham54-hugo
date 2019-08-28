# Introduction

Hugo site for [kimpham54.github.io](http://kimpham54.github.io/)

## Usage

### Content Editing Workflow

```
hugo new post/message.md
cd content/post/message.md
Make changes, edit metadata, make public not a draft
hugo -t=after-dark
test by going to hugo server -t=after-dark --buildDrafts
```

### Build

clear public/

run

```
./deploy.sh "commit message"
```
pull down https://github.com/kimpham54/kimpham54.github.io
copy over the public/ or docs/ to kimpham54.github.io repository
keep kimpham54.github.io's README.md, .git, .gitignore


### Theme

Currently using one theme, after-dark. This theme is a submodule, consequently there may be issues with compatibility.

Last confirmed working versions:
after-dark v.1.8.0

```
git submodule add https://github.com/comfusion/after-dark.git themes/after-dark
```
