# CSS-Color-Ratios
This page is a quick reference for HTML named colors and how they handle light or dark text. (These are the original 16 HTML colors from 1999, and the 124 Netscape X11 colors).  [Here's a list on Wikipedia.](https://en.wikipedia.org/wiki/Web_colors#X11_color_names)

## How it works
The text in each color field is the name of its background color. Each combination passes Chrome dev tools' color contrast check. The default "white" for this project is `azure` and default "black" is `midnightblue`. 
In dev tools if you hover over a particular color container, the ratio will be visible in the accessibility part of the tool tip, as well as the color hex code.

## Reasoning
This is a great tool if you're styling a webpage in five minutes and don't want to use midnightblue and lemonchiffon every single time like I do. This is especially helpful for button styling, where you often end up with three versions for one button because of `:hover` and `:active` versions.