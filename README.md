# BijbaanWiki

This will be our internal wiki and documentation site.
Always develop on the develop branch and never change anything on the master branch. Everything on master is auto generated.

# Prerequisites
1. install angular cli `npm i -g @angular/cli`
2. install angular github pages (already in project but useful to have global)  `npm i -g angular-cli-ghpages`

# Making changes
Make changes as you would to any angular project everything works exactly the same.

# Publishing changes
To publish your changes execute the following commands:
1. `ng build --prod`
2. `npx angular-cli-ghpages --dir=dist/bijbaan-wiki --branch=master` 
3. That's it! your changes should be live on [our site](https://studentportaal.github.io/)

## Always push to develop!