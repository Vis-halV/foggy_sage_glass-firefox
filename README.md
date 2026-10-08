Foggy Sage Glass

A soft sage-green glass-inspired Firefox theme based on the Foggy Sage Glass Obsidian theme.

Features
Soft sage-green interface colors
Frosted-glass-inspired color palette
Light color scheme
Dark green text
Coordinated tabs, popups, sidebar, and toolbar
Subtle hover and active states
Installation
Temporary Installation
Open Firefox.
Go to about:debugging.
Select This Firefox.
Click Load Temporary Add-on....
Select the manifest.json file from this project.
Using web-ext
Install web-ext

Install web-ext globally using npm:

npm install --global web-ext


Check the installation:

web-ext --version

Run the Theme

Run the theme directly in Firefox:

web-ext run

Lint the Theme

Check the theme for errors:

web-ext lint


Treat warnings as errors:

web-ext lint --warnings-as-errors

Build the Theme

Create a distributable ZIP package:

web-ext build


The package will be created inside:

web-ext-artifacts/


Overwrite an existing build:

web-ext build --overwrite-dest


Specify an output directory:

web-ext build --artifacts-dir ./dist


Specify the package filename:

web-ext build --filename foggy-sage-glass.zip

Useful Commands
web-ext run
web-ext lint
web-ext build
web-ext build --overwrite-dest
web-ext --help

Color Palette
Element	Color
Frame	#aec7b5
Inactive Frame	#a6c0ad
Toolbar	#b8d0be
Selected Tab	#c4d8c9
Borders	#8fa997
Hover	#9fbaaa
Active	#8fa997
Icons	#385842
Attention	#52745d
Loading	#70997b
Text	#101710
Theme Information

Name: Foggy Sage Glass

Version: 1.0.0

Manifest Version: 3

Color Scheme: Light

Project Structure
foggy-sage-glass/
├── manifest.json
└── README.md

Inspiration and Original Theme

This Firefox theme is based on the Foggy Sage Glass Obsidian theme.

Obsidian Community Theme:

https://community.obsidian.md/themes/foggy-sage-glass

Original Obsidian Theme Repository:

https://github.com/Vis-halV/foggysageglass-obsidian

The Firefox version adapts the original theme's visual style and color palette to Firefox's browser UI.

Credits

Inspired by and based on the Foggy Sage Glass Obsidian theme by Vis-halV.

Original project:

https://github.com/Vis-halV/foggysageglass-obsidian
