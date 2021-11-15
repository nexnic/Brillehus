# Brillehus

Exam at active learning front-end bootcamp

# Exam first assignment

The glass store must contain a front page, about us, products and contact us page. So four pages in total. The content of these pages is up to you, but it should be the content that builds up the page. Ask me if you are unsure of your content. A little hint can be to see how similar sites have solved this, and search for the concepts you are unsure of.

# File Management

1.  clean and folder structure
2.  You will work in a main folder that is located by itself.
3.  Divide the folders according to what kind of language you work with.
4.  No spaces in filenames.
5.  Engelske filnavn.

# HTML

1.  Neat and semantic code., You can use prettier.
2.  Correct syntax
3.  Using header, main, footer
4.  Use of different HTML tags, preferably HTML5 tags.
5.  All links should lead to the right page
6.  Add small comments along the way that give a brief explanation of the code.
7.  These comments should not be longer than two lines.

# CSS

1.  One CSS file for each html file. Can use Sass insted.
2.  Neat code, avoid redundant code that does nothing.
3.  Flexbox will be used.
4.  Import external fonts.
5.  Media screen: 362px , 768px, 992px
6.  Add small comments along the way that give a brief explanation of the code. These comments should not be longer than two lines.

# Design

1.  Using Figma
2.  Universal Design
3.  WCAG
4.  Design for all sides
5.  A design for mobile, and a design for desktop

# Setup of development environment

Tools

1.  VScode
    Link: https://code.visualstudio.com/
2.  Node.js
    link: https://nodejs.org/en/
3.  sass
    link: https://sass-lang.com/
4.  Figma
    link: https://www.figma.com/

VScode Extensions

1.  Prettier
    link: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
2.  Color Highlight
    link: https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight
3.  Bracket Pair Colorizer
    Link: https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer
4.  HTML CSS Support
    Link: https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css

VScode Color theme

1.  Monokai Pro
    Link: https://marketplace.visualstudio.com/items?itemName=monokai.theme-monokai-pro-vscode

# First time setup

install Node from https://nodejs.org/en/
Node ver (16.13.0 LST)
after install it test it in comandline windows (node.js), linux (terminal).
§npm version

1.  §npm init
2.  §name: BrilleHus
3.  §version (1.0.0)
4.  §description: Landing page for brillehus.
5.  §entry point (index.js)
6.  §test command: §
7.  §keyword: §
8.  §author: name of developer/ team
9.  §licensen: (ISC)
10. §is this ok? (yes)

Now need to install sass and live-server

1.  §npm install node-sass -save-dev
    Note from developer: it's importen to save as dev disse is note online yet.
2.  §npm install -g live-server
    Note from developer: if you have any problem install use google or ask.

Now need to edit (package.json)

1. line 6 "scripts"
   "scripts": {
   "compile:sass": "node-sass sass/main.scss css/style.css -w"
   },

Now we are ready to start code

You download need to change code
Need to update npm node-sass

1.  §npm update
    Note from developer: disse code update from paceage.json file download node-sass folder. if you have any problem ask og check google.com.
