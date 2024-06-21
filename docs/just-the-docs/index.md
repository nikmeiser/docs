# Setting up a site with 'Just the docs'

- click "[use this template]" to create a GitHub repository
- pull the repo down 
- set up a PAT under 'settings'
 - scope it to the specific repo
 - give it content permissions to allow it to push changes
 - login with your username and PAT
- remove '.github' dir
- move everything under a subdir called 'docs'
- update '\_config.yml'
- push changes
- go to the rep settings and set up the github pages deployment under 'pages'
- look for status under 'actions' and fix errors


[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
