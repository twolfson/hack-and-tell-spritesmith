Title slide
- Spritesmith
- Include link to slides, github, and twitter [todo: github link]

What is a sprite?
- Show nyan cat. If you are familiar with this, disregard it.

What is a sprite?
- Show Google sprite sheet and Bootstrap sprite sheet
- As sprite is each image separate image. The entirety is known as a spritesheet.
- These are known as CSS sprite sheet and what we will be talking for the next 4 1/2 minutes.

The problem
- Spritesheet and the variables linked to them are either maintained by hand, Compass exclusive, or not cross-platform
- Show image of photoshop and link to canvas

The problem
- I fell into the first category, was at a JS all the things company, and was on a Windows machine.
- In other words, the perfect candidate.

Approach
- Looked at the landscape, settled of node.js, graphicks magick as the Windows preferred engine, and node-canvas as the Unix preferred engine.

Solving
- gm was the harder of the 2 engines. I had gotten frustrated at the lack of transparency support. However, after much trial and error I got through.

Going beyond
- The next step was to write a grunt wrapper and call it a day.
- However, I pondered for a while if I could modularize and where to draw the lines.
- I wound up writing *5* modules and am contemplating even more.

grunt-spritesmith, spritesmith, layout, json2css, json-content-demux

Current state
- Wrote up a phantomjs engine since then to lower barrier to entry
- Still looking for a hosted solution to be install free
- 5 CSS variable formats - JSON, SASS, SCSS, LESS, Stylus
- 1 project written on top of spritesmith by another person

Title slide
- Thank you.
- Spritesmith
- Include link to slides, github, and twitter
