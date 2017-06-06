# Introduction

Hugo site for [kimpham54.github.io](http://kimpham54.github.io/)

## Usage

### Content Editing Workflow

```
hugo new post/message.md
cd content/post/message.md
Make changes, edit metadata
hugo -t=after-dark
test by going to hugo server -t=after-dark --buildDrafts
copy over public/ or docs/ to kimpham54.github.io repository
```

### Build

run

```
./deploy.sh "commit message"
```

### Theme

Currently using one theme, after-dark. This theme is a submodule, consequently there may be issues with compatibility.

Last confirmed working versions:
after-dark v.1.8.0

```
git submodule add https://github.com/comfusion/after-dark.git themes/after-dark
```
