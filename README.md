# Frontend-UI

## HTML and less

#### HTML
Currently, there are two pages
-index.html
-about.html

#### less
The less files are broken into sections
- variables.less
  - This is for styles that are frequently reused
- mixins.less
  - This is also for styles that are reused, but with multiple attributes or with variables
- reset.less
  - This is the Eric Meyer reset code
- general.less
  - All common individual elements should be in here
- navigation.less
  - This contains the header and nav styles
- main.less
  - The styles for main content
- cta.less
  - Button styling is in here
- index.less
  - This file imports all the above files

#### css
- index.css
  - The less is compiled to this file.