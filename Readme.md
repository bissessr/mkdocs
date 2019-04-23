
# How to Setup MkDocs and GIT integration

---

## Overview

MkDocs is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation. Documentation source files are written in Markdown, and configured with a single YAML configuration file. MkDocs builds completely static HTML sites that you can host on GitHub pages, Amazon S3, or anywhere else you choose.

The built-in dev-server allows you to preview your documentation as you're writing it. It will even auto-reload and refresh your browser whenever you save your changes. Get your project documentation looking just the way you want it by customizing the theme.

## GIT Setup

Create GIT Repository

```git init
git add .
git commit -m "first commit"
git remote add origin <https://github.com/user_name/repo_name.git>
git push -u origin master ```

setup gitpages

Push existing repository

```git remote add origin <https://github.com/user_name/repo_name.git>
git push -u origin master```

## mkdoc setup

- mkdocs new [dir-name] - Create a new project.
- mkdocs serve - Start the live-reloading docs server.
- mkdocs build - Build the documentation site.



## more info

tba


## Publish on Git

run ```mkdocs gh-deploy```

~~~INFO - Cleaning site directory INFO - Building documentation to directory:C:\Users\Raj\Documents_LAB_PROJECTS\iaac-docs\siteWARNING - Version check skipped. No version specified in previous deployment. INFO - Copying 'C:\Users\Raj\Documents_LAB_PROJECTS\iaac-docs\site' to 'gh-pages' branch and pushing to GitHub.PS C:\users\raj\Documents\_LAB\_PROJECTS\tf-hub-spoke> mkdocs gh-deployINFO    -  Cleaning site directoryINFO    -  Building documentation to directory: C:\users\raj\Documents\_LAB\_PROJECTS\tf-hub-spoke\siteINFO    -  Copying 'C:\users\raj\Documents\_LAB\_PROJECTS\tf-hub-spoke\site' to 'gh-pages' branch and pushing to GitHub.INFO    -  Your documentation should shortly be available at: https://bissessr.github.io/azure-hub_spoke/PS C:\users\raj\Documents\_LAB\_PROJECTS\tf-hub-spoke> mkdocs gh-deployINFO    -  Cleaning site directoryINFO    -  Building documentation to directory: C:\users\raj\Documents\_LAB\_PROJECTS\tf-hub-spoke\siteINFO    -  Copying 'C:\users\raj\Documents\_LAB\_PROJECTS\tf-hub-spoke\site' to 'gh-pages' branch and pushing to GitHub.INFO    -  Your documentation should shortly be available at: https://bissessr.github.io/azure-hub_spoke/PS C:\users\raj\Documents\_LAB\_PROJECTS\tf-hub-spoke>## Access DocumentationINFO - Your documentation should shortly be available at:https://bissessr.github.io/iaac-docs/ ~~~

## Project layout

- mkdocs.yml # The configuration file.
- docs/
- index.md # The documentation homepage.


