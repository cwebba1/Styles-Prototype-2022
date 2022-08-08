Read Me

# Read Me

This a a stylesheet prototype incorporating style sheets and systems from recent sources with the intention to create a stylesheet that can be quickly modified for client projects.

This is a first draft, August 8th, 2022. It is incomplete and not production ready.

The HTML document is a simple list of all HTML elements to target. Stylesheet-Master_02.html is the current iteration. Some elements are broken. compare to Pico_HTML_Elements_01.html and BS_HTML_Elements_01.html, which are resources.

Currently this iteration is mostly declarations from Pico.css which I have altered and mangled. There is very little of Open Props in this iteration. I have not looked at or processed Bootstrap yet. I plan to consider absorbing ideas from Bootstrap as well.

I have added a completely new sticky-footer set of declarations which I am still dissatisfied with. My own set of color custom properties are added and I have a very-basic font-stack borrowed from others. Fluid typography has dropped out and needs to be brought back in. Theme declarations and light/dark theme controls are not built. Resets and color variables are currently abstracted and added using @import because SASS in not yet setup for this project. I am using a combination of root{ }, [data-theme=(theme-name)] and :where(html) to organize variables. It is a random organization now and needs refinement. I would love to have comments and suggestions.

## This stylesheet pulls ideas and code samples from the following sources:
[Pico.css}(https://picocss.com/)
[Open Props]	(https://open-props.style)
[Normalize.css](https://github.com/necolas/normalize.css)
[Josh W Comeau's Custom CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/)

## Ideas from CSS Tricks:	
[https://css-tricks.com/notes-on-josh-comeaus-custom-css-reset/](https://css-tricks.com/notes-on-josh-comeaus-custom-css-reset/)
[https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/](https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/)

## Project Vision
A lot has changes with a plethora of new CSS declarations and patterns in the last few years. This project will incorporate many ideas.

There is a big wave of building projects styles using wireframe tools such as Figma and Sketch, or common libraries such as Bootstrap but this project will be my own synthesis of the current zeitgeist of website design and design system design. 

## I want to build these features:
* Theme-able using custom properties
* Base declarations on elements to avoid classes in markup
* Use modern reset techniques
* Scoped declarations for components
* Components separated and stand-alone dependency-free using SASS
* Accessibility baked in as much as possible
* A broad color scheme beyond Primary / Secondary color paradigm
* Additional progressive enhancements available as component add-ons such as animation
* Ready-to-go toolkit ready to incorporate into projects for fast prototype development
* Able to be installed into Figma or Storybook

## Tutorial resources I may incorporate in future:
[Elad Shechter's New CSS Reset](https://elad2412.github.io/the-new-css-reset/)
[Eric Meyer's Reset](https://meyerweb.com/eric/tools/css/reset/)
[Trys Mudford's Button reset:](https://www.trysmudford.com/blog/a-good-reset/?ref=heydesigner)

## Ideas to examine:
Don’t Fight the Cascade, Control It!, Mads Stoumann on Jan 11, 2022 
https://css-tricks.com/dont-fight-the-cascade-control-it/

CSS Cascading and Inheritance Level 5
W3C Candidate Recommendation Snapshot, 13 January 2022
https://www.w3.org/TR/css-cascade-5/#layering

The Future of CSS: Cascade Layers (CSS @layer)
Posted by Bramus! September 15, 2021
https://www.bram.us/2021/09/15/the-future-of-css-cascade-layers-css-at-layer/

Precise control over responsive typography
Creating fluid responsive typography with calc and viewport units.
Posted by Mike on 17th March 2015
https://www.madebymike.com.au/writing/precise-control-responsive-typography/

Writing Better CSS
Aleksander Hovhannisyan, Published Dec 08, 2021  Updated Jan 21, 2022
https://www.aleksandrhovhannisyan.com/blog/writing-better-css/#2-safe-global-defaults-with-where

gap property for Flexbox	https://caniuse.com/flexbox-gap

Creating Aspect Ratios in CSS
Aleksander Hovhannisyan, Published Sep 21, 2020  Updated June 12, 2021

https://www.aleksandrhovhannisyan.com/blog/css-aspect-ratio/#approach-2-aspect-ratios-with-percentage-padding

Creating a Fluid Type Scale with CSS Clamp
Aleksander Hovhannisyan, Published Dec 27, 2021  Updated June 24, 2022
https://www.aleksandrhovhannisyan.com/blog/fluid-type-scale-with-css-clamp/

Consistent, Fluidly Scaling Type and Spacing
Andy Bell
https://css-tricks.com/consistent-fluidly-scaling-type-and-spacing/

CSS {In Real Life}
Michelle Barker 2022
Logical Properties for Useful Shorthands
Tuesday July 19 2022, This article was updated on 28 July 2022
https://css-irl.info/logical-properties-for-useful-shorthands/

Bram.us
The Future of CSS: Variable Units, powered by Custom Properties
Posted by Bramus! July 8, 2022
https://www.bram.us/2022/07/08/the-future-of-css-variable-units-powered-by-custom-properties/

Beginner’s Guide to CSS Variables (aka CSS Custom Properties)
by Louis Lazaris, June 24, 2022
https://www.codeinwp.com/blog/css-variables/

Custom properties for layout
Manuel Matuzovic
https://codepen.io/matuzo/pen/xxWLRpb?editors=1100

A Complete Guide To CSS Variables [With Examples]
Harish Rajora, Posted On: July 29, 2021
https://www.lambdatest.com/blog/guide-to-css-variables-with-examples/

CSS variables: Scoping
Chidume Nnamdi, July 27, 2020 
https://blog.logrocket.com/css-variables-scoping/

CSS Variables: What They Are and How They Work
Jamie Juviler
https://blog.hubspot.com/website-2/css-variables

How to Use CSS Math Functions: calc, min, max, clamp
Alex Ivanovs, March 20, 2022
https://stackdiary.com/css-math-functions/#Using-CSS-Math-Functions-with-Variables

Using CSS math functions
Posted by: Carlos on June 13, 2022
https://publishing-project.rivendellweb.net/using-css-math-functions/

CSS @Import: This Is How You Can Organize Your Code
By Position is Everything, November 25, 2021
https://www.positioniseverything.net/css-import

With :focus-visible, you can have focus styles when it makes sense
Hidde de Vries, Published 19 DAYS AGO
https://hidde.blog/focus-visible-more-than-keyboard

:has(): the family selector
Jhey Tompkins, Published on Wednesday, August 3, 2022
https://developer.chrome.com/blog/has-m105/

## Tools:
Modern fluid typography editor
Created according to the Codex Astartes by Adrian Bece
https://modern-fluid-typography.vercel.app/

Fluid Type Scale Calculator
https://www.fluid-type-scale.com/

Modular Scale (Typography)
https://www.modularscale.com/?1,1400&em&1.625








