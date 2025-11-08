# Note: this workflow has been deprecated, i now use kimpham54.github.io exclusively


# Introduction

Hugo site for [kimpham54.github.io](http://kimpham54.github.io/)

## Usage

### Content Editing Workflow

```
hugo new post/message.md
cd content/post/message.md
Make changes, edit metadata, make public not a draft. check date of post to publish


```

### Build

hugo -t=after-dark
just to test: go to hugo server -t=after-dark --buildDrafts

then run

```
./deploy.sh "commit message"
```

copy public/

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
