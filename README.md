# EyeDropper API demos

This repository contains a series of simple demo pages made to showcase the new JavaScript [EyeDropper API](https://wicg.github.io/eyedropper-api/).

## Why this API?

Sampling colors from your screen is a very useful feature in creative applications. PowerPoint lets you change things like the color of a shape by sampling from other shapes. Photoshop also allows you to sample the color of any pixel in the screen to reuse for your drawings. Finally browser DevTools also allow you to grab the color of elements in the web page when editing color properties in the Styles panel.

It is, unfortunately, not possible for web applications to do this today. Some browsers do support it if you use an `<input type=color>` element, but that means you're forced to use the input element for something you might want to do in JS only and customize to your needs.

The EyeDropper API aims to fill that gap.

## Implementation

At this time, the EyeDropper API is implemented in Chromium browsers. Try it in Microsoft Edge 95 or Google Chrome 95.

## The demos

There are 3 demos in the repository. Click below to try them in your browser. And use [GitHub](https://github.com/captainbrosset/eyedropper-demos) to review the source code.

* [Color game](https://captainbrosset.github.io/eyedropper-demos/color-game.html): Click play and find the matching color from the list at the bottom before the time runs out.
* [Photo color swap](https://captainbrosset.github.io/eyedropper-demos/photo-color-swap.html): Load a picture, then select a color from it, and finally select a second color to replace it with.
* [Mondrian generator](https://captainbrosset.github.io/eyedropper-demos/mondrian.html): Generate random Mondrian-like color grids, and click on any tile in the grid to swap its color.
* [Online color picker](https://pickcoloronline.com/): Just a simple color picker to pick a color on your screen.
* [Color Picker Extension](https://github.com/siddsarkar/color-picker-browser-extension): A minimial Chrome extension that let's you pick color from any pixel of your screen.
