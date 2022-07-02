---
title: Jekyll Static Website
nav: ZK Project
nav_order: 3
---
# ★ Jekyll Static Website
   ›[[202011250546]] 
   11-25-2020 05:46 AM

- #project #regex 

Tasks
[] - Move Image up
[] - Clean up bottom of each page.
[] - Set up Lojong Slogan page
[] - index.md (main_page.md)
[✔︎] - Move notes to GIT and remove from normal zettelkasten  
[] - restructure index and sections
[] - add cover art

Initial Workshop - University of Idaho - Evan Williams
https://github.com/evanwill/workshop-template-b repository 
https://evanwill.github.io/workshop-template-b/ site
My test/development from workshop
https://woodenzen.github.io/workshop-initial/ site

**Focus on writing good documentation**
 [Home | Just the Docs](https://pmarsceill.github.io/just-the-docs/) Cool Jekyll template that can run on GitHub Pages.

## Project definition 
- create a place to publish 'Being Ordinary'. Test the look and feel, the workflow, for connection with zettelkasten.

## GitHub Setup
- Documentation https://docs.github.com/en 
- Training https://lab.github.com

## Ruby Setup
- For local setup
- Laptop - https://github.com/monfresh/laptop shell script that installs:
    - Bundler for managing Ruby gems
    - chruby for managing Ruby versions (recommended over RVM and rbenv)
    - GitHub CLI brings GitHub to your terminal.
    - Heroku Toolbelt for deploying and managing Heroku apps
    - Homebrew for managing operating system libraries
    - Homebrew Cask for quickly installing Mac apps from the command line
    - Homebrew Services so you can easily stop, start, and restart services
    - Postgres for storing relational data
    - ruby-install for installing different versions of Ruby

## Jekyll Setup
- for local setup

## Atom 2 Setup
- Project Folders
- Sign in to git
- Add git-plus

## YAML
- YAML [[202012212159]]
- YAML Front Matter [[202003231450]]

## Themes
- Git-Wiki
    - https://github.com/Drassil/git-wiki-theme
- Henry
    - https://blog.jkl.gg/henry-jekyll-theme

## File Conversion for links

Link conversion RegEx https://regex101.com/r/cWkER7/1j
(^.*(?= \.))(.*(?=\[\[))\[\[(.*)\]\]
- Remedy obstacles with one intention ............................[[201904080510]]
Sub
$1$2[\\[\\[$3\\]\\]]($3 ₤ $1.md)
- Remedy obstacles with one intention ............................[\[\[201904080510\]\]](201904080510 ₤ Remedy obstacles with one intention.md)

For Conversion of index links
https://regex101.com/r/AMqkuF/1
(.*)(?= \[)(.*(?=\[\[))\[\[(.*)\]\] \((\d*)\) 
Sub
$4. $1$2[\\[\\[$3\\]\\]]($3 $1.md)

- Upload and use zettel with the #public tag first marking all links as private some how. Then do a search of all the matching links available in all the uploaded zettel changing the private marking to an active link.

Hugo Static Website
- convert links 
  - From
    - [[201911232040]] Bombs And Rhymes
  - To 
      - [[[201911232040]({{< relref "Bombs And Rhymes 202009212028.md" >}} "Bombs And Rhymes")]] Bombs And Rhymes 

Jekyll
- https://github.com/maximevaillancourt/digital-garden-jekyll-template
- Wikiklinks
  - https://www.libhunt.com/compare-jekyll-wikilinks-vs-jekyll?ref=compare
- Install digital garden
    - https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll
